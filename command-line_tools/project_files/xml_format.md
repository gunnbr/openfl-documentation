# XML Format

## Overview

Usually a simple project file is all you need to build projects using OpenFL, but it can be extended based on your needs. Here is a reference of what you can do.

### Conditionals

First, every node in the project file format supports `if` and `unless` attributes. These are conditional values to help you customize your build process, based upon a number of values. Here are some of the default values:

 * mobile, desktop or web
 * ios, android, blackberry, tizen, windows, mac, linux or html5
 * cpp, neko, flash or js

You can create more defines using the `<set />` or `<unset />` tags:

    <set name="define" />
    <window width="640" height="480" if="define" />

You can add defines using the command-line as well:

    openfl test flash -Ddefine

If you need to have multiple values in a conditional, spaces imply an "and" and vertical bars imply an "or", like this:

    <window width="640" height="480" if="define define2" unless="define3 || define4" />

### Duplicates

You can include more than one copy of each tag, so do not worry about putting it all in one place. All of the values you define will be used. If you define the same value more than once, the last definition will be used.

    <window width="640" />
    <window height="480" />

### include.xml

If you create a haxelib, you can add "include.xml" to the top-level directory. The build tools will automatically add the contents of the file to the user's project. You can use this to add binary dependencies, additional classpaths, etc.

## Common Tags

### `<meta />`

Use `<meta />` tags to add information about your application, which usually will not affect how the application runs, but how it is identified to the target operating system or on an application store:

    <meta title="My Application" package="com.example.myapplication" version="1.0.0" company="My Company" />

### `<app />`

The `<app />` tag sets values important to building your project, including the entry point (main class), the output file directory, or if you want to customize the executable filename or define a custom preloader for a web platform:

    <app main="com.example.MyApplication" file="MyApplication" path="Export" preloader="CustomPreloader" />
    <app swf-version="11" />

### `<window />`

You can use `<window />` tags to control how an application will be initialized. This includes the screen resolution and background color, as well as other options, such as whether hardware should be allowed or display mode flags.

By default, mobile platforms use a window width and height of 0, which is a special value that uses the resolution of the current display. This is available on desktop platforms, but usually it is recommended to enable the `fullscreen` flag instead, and to set the `width` and `height` values to a good windowed resolution. There is a special `fps="0"` value for HTML5, which is default, which uses "requestAnimationFrame" instead of forcing a frame rate.

    <window width="640" height="480" background="#FFFFFF" fps="30" />
    <window hardware="true" allow-shaders="true" require-shaders="true" depth-buffer="false" stencil-buffer="false" />
    <window fullscreen="false" resizable="true" borderless="false" vsync="false" />
    <window orientation="portrait" />

The `orientation` value expects either "portrait" or "landscape" ... the default is "auto" which allows the operating system to decide which orientation to use.

### `<source />`

Use `<source />` tags to add Haxe class paths:

    <source path="Source" />

If you are using `@:file`, `@:bitmap`, `@:sound` or `@:file` tags in your project, be sure that the asset files are available within your Haxe source paths.

### `<haxelib />`

Use `<haxelib />` tags to include Haxe libraries:

    <haxelib name="actuate" />

You can also specify a version, if you prefer:

    <haxelib name="actuate" version="1.0.0" />

### `<ndll />`

You can use `<ndll />` tags to include native libraries. These are usually located under an "ndll" directory, with additional directories based upon the target platform. Usually an `<ndll />` tag will be included as a part of an extension, and is rare to be used directly:

    <ndll name="std" haxelib="hxcpp" />

### `<include />`

Use `<include />` tags to add the tags found in another project file, or to find an "include.xml" file in the target directory:

    <include path="to/another/project.xml" />
    <include path="to/shared/library" />

### `<icon />`

Use `<icon />` nodes to add icon files to your project. When the command-line tools request icons for a target platform, it will either use an exact size match you have provided, or it will attempt to find the closest match possible and resize. If you include an SVG vector icon, it should prefer this file over resizing bitmap files.

    <icon path="icon.png" size="64" />
    <icon path="icon.png" width="96" height="96" />
    <icon path="icon.svg" />

### `<assets />`

Use asset nodes to add resources to your project, available using `openfl.Assets`.

The path attribute can point to either a file or a directory. These files will be copied (or embedded) in your final project, and can be accessed using the `openfl.Assets` class.

For example, if you include the following node in your project file:

    <assets path="images/MyImage.jpg" />

You can access it in your application like this:

    var bitmapData = Assets.getBitmapData ("images/MyImage.png");

The target path will mirror the source path by default, but you also can include a rename attribute, if you wish to use a different target path. The `openfl.Assets` class will use the *target* path by default, so using the rename attribute will alter the names you use to reference your files.

If you would prefer to set the ID for your asset file yourself, use an "id" attribute. This only applies to asset nodes which point to a file, not a directory path.

When pointing to a directory, you can use the include or exclude attributes to specify patterns for including files automatically. Wildcards are supported. To include all the files under the directory, for example, use an include value of "*". You can separate multiple patterns using "|" characters.

You can nest assets nodes inside of each other. If you specify a directory in the top assets node, its path will be appended to the paths you specify in subsequent nodes.

The type for each file will be determined automatically, based on each file extension, but you can use the type attribute to set it for the file or directory yourself. If you are nesting a node inside of another assets node, you can also use the name of the type as the name of your node.

These are the current types:

 * binary
 * font
 * image
 * music
 * sound
 * template
 * text

Some targets can only support playing one music file at a time. You should use "music" for files which are designed to play as background music, and "sound" for all other audio. "binary" and "text" are generic types which are available as a ByteArray or String in your application. Most targets can use them interchangeably.

If an asset is specified as "template", it will not be copied/embedded as an ordinary asset, but instead will be copied to the root directory of your project, so you can replace any of the template HX, HXML or platform-specific files for the target.

    <assets path="assets" include="*" />
    <assets path="../../assets" rename="assets" include="*" />
    <assets path="assets/images" rename="images" include="*.jpg|*.png" exclude="example.jpg" />
    <assets path="assets">
    <assets path="images" include="*" type="image" />
    <assets path="assets">
        <sound path="sound/MySound.wav" id="MySound" />
        <music path="sound/BackgroundMusic.ogg" />
    </assets>

## Additional Tags

### `<template />`

Use `<template />` tags to add paths which can override the templates used by the command-line tools.

You can add a full template path like this:

    <template path="templates" />

Otherwise, you can override a single file like this:

    <template path="Assets/index.html" rename="index.html" />

### `<haxeflag />`

Use `<haxeflag />` tags to add additional arguments in the Haxe compile process:

    <haxeflag name="-dce" value="std" />

### `<haxedef />`

Use `<haxedef />` tags to add Haxe defines (similar to using a `<haxeflag />` with "-D"):

    <haxedef name="define" />

### `<setenv />`

Use `<setenv />` tags to set environment variables:

    <setenv name="GLOBAL_DEFINE" />

### `<java />`

Use `<java />` tags to add Java classes to the project when targeting Android:

    <java path="to/classes" />

### `<certificate />`

Use `<certificate />` tags to add a keystore for release signing on certain platforms.

If you do not include the password attribute, you will be prompted for your certificate password at the command-line.

For Android, the alias will be set to the file name of your certificate by default, without the extension. If the alias name is different, you can use the alias attribute.

If you have set the password attribute, the alias_password attribute will default to the same value. Otherwise you can add an alias-password attribute to specify a different value.

BlackBerry does not use the `alias` or `alias-password` attributes.

    <certificate path="to/certificate.crt" password="1234" alias="my-alias" alias-password="4321" />

### `<ios />`

Control iOS-specific values when compiling.

The `deployment` attribute can set the minimum iOS version you wish to target. The `binaries` attribute can be "armv6", "armv7" or "fat". The `devices` attribute can specify "ipad", "iphone" or "universal".

If you select a device, it can set the binaries. For example, if you only want to target the iPad, only armv7 will be required, or if you wish to target both, it will create a universal binary by default.

    <ios deployment="5" binaries="armv7" devices="universal" />
    <ios linker-flags="" prerendered-icon="false" />

### `<android />`

Use `<android />` tags to set Android-specific values:

    <android install-location="preferExternal" />
    <android permission="com.android.vending.BILLING" />
    <android target-sdk-version="16" />

### `<architecture />`

Use `<architecture />` tags to set or exclude Android-specific architectures. These can be `ARMv7`, `ARMv6`, `ARMv5` and `X86`.

By default the only architecture built will be `ARMv7`.

For example, if you want to enable `ARMv6` and disable `ARMv7` you would set the `<architecture />` tag to:

    <architecture name="armv6" exclude="armv7" if="android" />

### `<dependency />`

Use `<dependency />` tags to specify native frameworks or references that are required to compile your project, as well as additional libraries you need copied.

    <dependency name="GameKit.framework" if="ios" />

### `<path />`

Use `<path />` tags to add directories to your system's PATH environment variable.

    <path value="path/to/add/to/system/PATH" />

### LogHelper.error

Use `LogHelper.error` to throw your own errors during the build process, if necessary.

    LogHelper.error ("Something is wrong");

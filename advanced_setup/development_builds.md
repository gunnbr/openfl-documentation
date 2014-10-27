# Development Builds

## Haxe

## Lime

If you are just getting started, we recommend you to stick with Lime release builds, but if you would like to contribute to Lime, here are the steps to using Lime from GitHub, and rebuilding the binaries manually.

Most of the time, you do not need to use development versions of every library, for example, you may choose to contribute to `lime`, but to keep a release version of `lime-tools` installed. Keep in mind that there can be some incompatibilities between development/release versions.

### lime

To use a development version of `lime`, install or use Git in order to clone the repository.

We collaborate with the NME project to develop a shared C++ codebase. You will need to clone `nme` and `nme-dev` as well as `lime` in order to build from the source.

    git clone https://github.com/openfl/lime
    git clone https://github.com/haxenme/nme
    git clone https://github.com/haxenme/nme-dev
    haxelib dev lime lime
    haxelib dev nme nme
    haxelib dev nme-dev nme-dev

If you prefer so, you can also use the `haxelib git` command. It allows haxelib to pull the repository using `haxelib upgrade` command, but may otherwise make it more difficult to use:

    haxelib git lime https://github.com/openfl/lime
    haxelib git nme https://github.com/haxenme/nme
    haxelib git nme-dev https://github.com/haxenme/nme-dev

Lime includes a `rebuild` command to rebuild the native binaries for each platform. You can specify one target, or multiple targets separated by commas. For example, to rebuild the native binary for Windows the command would be:

    lime rebuild windows

The `rebuild` supports additional flags, such as `-32`, `-64` or `-clean` if you wish to perform a clean build or target only a certain architecture.

### lime-tools

To use a development version of `lime-tools`, make sure that you have `format` and `svg` libraries installed:

    haxelib install format
    haxelib install svg

Then you can clone the `lime-tools` repository, and set the haxelib dev directory:

    git clone https://github.com/openfl/lime-tools
    haxelib dev lime-tools lime-tools

Before rebuilding the Lime command-line tools, make sure that you have `lime` installed, and that the binary for your desktop platform is valid and up-to-date. If you are using `lime` as a release version, you should be fine already. Otherwise, make sure that you run `lime rebuild` for your desktop first.

Here is how you can rebuild `lime-tools`:

    lime rebuild tools

You may also choose to combine this with another command:

    lime rebuild linux,tools

If you are using development versions of `lime` and `lime-tools`, you can also use the `-rebuild` flag when you test any other project. It will rebuild the binary specific to that target and configuration (such as release, 64-bit) as well as the tools:

    lime test linux -rebuild

Additional flags, such as `-clean` or defines, will also pass into the rebuild process.

## OpenFL

To use OpenFL from the source, use:

    git clone https://github.com/openfl/openfl
    haxelib dev openfl openfl

Depending on the features used, you may also need development versions of `lime` or `lime-tools`. More information [[here.|1.2.-Install-Lime#development-builds]]

## Forums

If you encounter any problems while installing Lime, or need help in using a development version of Lime from the source, please visit the [forums](http://www.openfl.org/forums/#!/installation)!

# Manual Install

## Haxe

Although we recommend that you use an automatic install, there is information available at [http://www.haxe.org/download](http://www.haxe.org/download) if you wish to install Haxe manually, or to build from the source.

If you have any problems using a manual install, please try an automatic install before reporting issues. Thanks!

## Lime

If there is a problem using "setup", you may also download and install Lime manually. First download each of the latest releases from lib.haxe.org:

 * [http://lib.haxe.org/p/lime](http://lib.haxe.org/p/lime)
 * [http://lib.haxe.org/p/lime-tools](http://lib.haxe.org/p/lime-tools)
 * [http://lib.haxe.org/p/hxcpp](http://lib.haxe.org/p/hxcpp)

Once they are downloaded, use `haxelib` to install them:

    haxelib local lime-VERSION.zip
    haxelib local lime-tools-VERSION.zip
    haxelib local hxcpp-VERSION.zip

Where `VERSION` is the version of the library. For example, if you've downloaded a zip called `lime-1,5,7.zip` the command will be `haxelib local lime-1,5,7.zip`

Run `haxelib run lime setup` to install the `lime` command shortcut. This will enable you run `lime` rather than `haxelib run lime` in the future.

Since you have installed the dependencies for Lime already, the `setup` command should go directly to installing the shortcut.

## OpenFL

If there is a problem with the `lime install` command, you may also download and install OpenFL manually. First download each of the latest releases from lib.haxe.org:

 * [http://lib.haxe.org/p/openfl](http://lib.haxe.org/p/openfl)
 * [http://lib.haxe.org/p/openfl-samples](http://lib.haxe.org/p/openfl-samples)
 * [http://lib.haxe.org/p/swf](http://lib.haxe.org/p/swf)
 * [http://lib.haxe.org/p/actuate](http://lib.haxe.org/p/actuate)

You can then install manually:

    haxelib local openfl-VERSION.zip
    haxelib local openfl-samples-VERSION.zip
    haxelib local swf-VERSION.zip
    haxelib local actuate-VERSION.zip

Where `VERSION` is the version of the library. For example, if you've downloaded a zip called `openfl-2,0,1.zip` the command will be `haxelib local openfl-2,0,1.zip`

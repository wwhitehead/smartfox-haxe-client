SmartFoxServer 2X Haxe client API
=======================

Haxe openfl translation of the as3 client for the Smartfox server http://www.smartfoxserver.com/

**WARNING : HTML5 support is a work in progress!**

Check html5 current support status here : https://github.com/boorik/smartfox-haxe-client/projects/1

Tested on flash, windows, ios and android targets.

You can have a look at https://github.com/boorik/smartfox-haxe-fullstack to check a sample project that use the api and haxe all the way.

Pull requests are welcome

Let me know how it works on other targets

----------------------------------
CURRENTLY WORKING WITH :

haxe: 3.4.2

lime: 5.4.0

openfl: 6.1.0

haxe-crypto: 0.0.7

----------------------------------


Instructions:
=====
Installation
```
haxelib git smartfox-haxe-client https://github.com/boorik/smartfox-haxe-client
```

add in your project.xml :
```
<haxelib name="smartfox-haxe-client"/>
```

Then you can use it like the as3 api, check the as3 exemples there :
http://docs2x.smartfoxserver.com/ExamplesFlash/introduction

TODO:
====
* test app
* improve typing
* make it framework agnostic pure haxe without openfl dependency
* make it work with html5 target

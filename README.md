Windows Store Icon Maker
=============

When creating applications for the Windows stores (RT & Phone), there are numerous icons that need to be created. This utility to help generate all the required icon sizes, including the scaled versions for higher DPI devices.

Downloading
--------
I will upload a compiled version in the future. For the moment you can download and compile the application.

Usage
--------
1. Drag and drop an image onto the workspace.
2. Select the region of the image you want to crop
3. Click *Save* to have the icons be generated

It is recommended to use an image that is at least 300x300 for best results.

Features
--------
* Automatically generate icons for:
	* Windows Phone 7
	* Windows Phone 8
	* Windows Store Applications

###Generated icons
**Windows Phone 7**

* StoreTile.png (300x300)
* BackgroundImage.png (173x173)
* ApplicationIcon.png (62x62)


**Windows Phone 8**

* ApplicationIcon.png (100x100)
* ~~FlipCycleTileLarge.png (691x336)~~
* FlipCycleTileMedium.png (336x336)
* FlipCycleTileSmall.png (159x159)
* ~~IconicTileMediumLarge.png (134x202)~~
* ~~IconicTileSmall.png (71x110)~~

**Windows Store Application**

* Logo
	* Logo.scale-180.png (270x270)
	* Logo.scale-140.png (210x210)
	* Logo.scale-100.png (150x150)
	* Logo.scale-80.png (120x12)
* SmallLogo
	* SmallLogo.scale-180.png (54x54)
	* SmallLogo.scale-140.png (42x42)
	* SmallLogo.scale-100.png (30x30)
	* SmallLogo.scale-80.png	(24x24)
	* SmallLogo.target-256.png (256x256)
	* SmallLogo.target-48.png	(48x48)
	* SmallLogo.target-32.png	(32x32)
	* SmallLogo.target-16.png	(16x16)
* StoreLogo
	* StoreLogo.scale-180.png (90x90)
	* StoreLogo.scale-140.png (70x70)
	* StoreLogo.scale-100.png (50x50)

Building
--------
I develop and compile this using Visual Studio 2012 Ultimate. 
However if you are using Visual Studio Express to developer, there are reports that you can use [Visual Studio Express 2012 for Desktop](http://www.microsoft.com/visualstudio/eng/products/visual-studio-express-for-windows-desktop) to compile it.

Acknowledgments
--------
This utility is based off the original source code of [Windows Phone Icons Maker](http://wpiconmaker.codeplex.com/) by [Hiroyuki Kawanishi](http://www.codeplex.com/site/users/view/hiroyuk). The source code had not been updated since September 2011, so I decided to fork it and update it to support the new platforms (WP7/WP8/WinRT).

License
--------
The code is MS-PL as that is what the original source code was licensed as.
[http://wpiconmaker.codeplex.com/license](http://wpiconmaker.codeplex.com/license)


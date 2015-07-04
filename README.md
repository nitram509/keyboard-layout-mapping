
Keyboard layout mappings for Karabiner
========================================

[Karabiner](https://pqrs.org/osx/karabiner/)
 is a powerful and stable keyboard customizer for OS X.
 

Motivation 
----------------------------------------
As a developer I prefer to use English keyboard layout.
But as lots of my colleagues used to German layout,
[pair programming](https://en.wikipedia.org/wiki/Pair_programming) 
with two keyboards is hard to practice.

To lower the barriers for two-keyboard-setups, I've built this keyboard mapping.
It enables a German and English layout used simultaneously via Karabiner tool.


Supported keyboard models
-----------------------------------------

* Speedlink
   * Comet Trackball Mini Keyboard (Model:SL-6497-SBK, VendorId: 0x05af, ProductId: 0x0906)


Usage
-----------------------------------------

First you need to download the ```speedlink-comet_trackball_mini_keyboard.xml``` to your harddisk.
Then go to Karabiner preferences -> misc -> custom settings -> open private.xml.
Alternativly, create&open ```~/Library/Application Support/Karabiner/private.xml```.


```xml
<?xml version="1.0" ?>
<root>
	<include path="/Users/username/keyboard-layout-mapping/speedlink-comet_trackball_mini_keyboard.xml" />
</root>
```
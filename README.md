
Keyboard layout mappings for Karabiner
======================================== 

Motivation 
----------------------------------------
As a developer I prefer to use English keyboard layout.
But as lots of my colleagues used to German layout,
[pair programming](https://en.wikipedia.org/wiki/Pair_programming) 
with two keyboards is hard to practice.

To lower the barriers for two-keyboard-setups, I've built this keyboard mapping.
It enables a German and English layout used simultaneously via Karabiner tool.

[Karabiner](https://pqrs.org/osx/karabiner/)
 is a powerful and stable keyboard customizer for OS X.

![A German keyboard and an US keyboard working on one MacBookPro side by side with thir native layouts.](german_and_us_layout_working_side_by_side_on_one_Mac_OS_X.jpg?raw=true)

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

After changing your private.xml file, you need to click 'reload xml' within Karabiner's preferences.
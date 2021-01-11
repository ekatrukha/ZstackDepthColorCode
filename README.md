# Z-stack Depth Color Code

[ImageJ](https://imagej.nih.gov/ij/)/[FIJI](http://fiji.sc/) plugin to colorcode Z-stacks/hyperstacks (8-,16-,32 bit). Allows to uses available LUTs + invert them. 

The plugin creates an output as Composite or RGB stack. So there is conversion to 8-bit, depending on the current Brightness/Contrast settings.

**NB:** After installation plugin appears in *Plugins->Stacks->Z-stack Depth Colorcode* menu.

It is loosely based on [Temporal-Color Code](https://imagej.net/Temporal-Color_Code) macro (but does not create Z-projection) and it is rewritten version of Z_Code_Stack function from [FIJI Cookbook](https://github.com/fiji/cookbook).

Generated colorcoded stacks can be visualized by different 3D renders ([3D Viewer](https://imagej.nih.gov/ij/plugins/3d-viewer/) or [3Dscript](https://bene51.github.io/3Dscript/) pligin).

Example: EB comets (by Boris Shneyer), grayscale before: 


![EB BW](http://katpyxa.info/software/ZstackDepthColorCode/EB_colored_BW.gif "EB stack BW")


and coded with Thermal LUT, after:


![EB color](http://katpyxa.info/software/ZstackDepthColorCode/EB_colored_thermal.gif "EB stack color")



## How to install plugin

To install plugin in FIJI:

* add https://sites.imagej.net/Ekatrukha/ to the list of update sites, as follows
* go to Help -> Update and press "Manage update sites" button
* press "Add update site" button and put the following link there http://sites.imagej.net/Ekatrukha/

To install plugin manually in ImageJ:

* download and copy the [latest version of plugin](https://github.com/ekatrukha/ZstackDepthColorCode/blob/main/target/ZstackDepthColorCode_-0.0.1.jar?raw=true) 
* plugin will appear in _Plugins->Stacks->Z-stack Depth Colorcode_ menu

## Updates history

2021.01.11 First version.

---
Developed in [Cell Biology group](http://cellbiology.science.uu.nl/) of Utrecht University.  
Email katpyxa @ gmail.com for any questions/comments/suggestions.
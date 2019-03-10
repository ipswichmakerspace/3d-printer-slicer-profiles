# Cura 15.04

This folder contains slicer profiles for Cura version 15.04.  These profiles cannot be used for the 2.x.x or 3.x.x versions of Cura, which are actually newer than 15.04, dispite the lower version numbers.

## Usage
There are three stages required to use these profiles:
1. Install the software
2. Setup the machine parameters
3. Install the appropriate slicer profiles

### Install  the software
Download Cura version 15.04 for your operating system from [here](https://ultimaker.com/en/products/ultimaker-cura-software/list).  Versions are available for Windows, Mac OS and GNU/Linux

### Setup the machine parameters
After installing Cura 15.04 you will probably be faced with a setup wizard.

* Select Machine - select `other`
* Other Machine Info - select `next`
* Custom RepRap info:

  Enter the basic machine info, you can get this from the [3D printers wiki page](https://home.ipswichmakerspace.com/mediawiki/index.php/3D_printers)

  Note, only select `bed centre is 0,0,0` if setting up the NFire Delta.

### Install the appropriate slicer profiles
Download the appropriate slicer profile or clone this entire repository to your local machine.

Select `File`, `Open profile` from the Cura menu, locate the slicer profile you want to use and click `ok`

You can now edit slicer settings to suit your requirements, such as layer height etc. Slice your model and export the gcode file.  This gcode file can then be loaded into OctoPrint on your selected printer to print.  This will not need further slicing, OctoPrint can print this gcode file directly.

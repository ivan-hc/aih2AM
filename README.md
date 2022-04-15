# aih2AM
A script to convert apps from AppImage.Github.io to installation scripts for "AM" Application Manager

### USAGE

    aih2am convert $APPNAME
where `$APPNAME` is the name of the AppImage as it appear on the AppImage catalogue of [AppImage.GitHub.io](https://appimage.github.io/apps/).

NOTE: this works only if the AppImage is hosted on GitHub.com.

For more alternative templates, see the `-t` option of the main project, ie "AM" Application Manager.

WARNING: This script supports multiple arguments, so be sure to enter "`_`" or "`-`" in the names as they appear on the catalog's page.

### TEST
Run the script in the terminal, it will create a `tmp` and `icons` folder in your home directory:
- if `wget` is downloadinding an AppImage, the script works as expected, you can safelly press CTRL+C to abort;
- if `wget` is not downloading what you need (baybe an AppImage for different architectures), then edit the created script (maybe the lines 28 and 54, or just the line 11).

## This script is part of https://github.com/ivan-hc/AM-Application-Manager

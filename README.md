# AppImageHub To "AM" (aih2AM)
A script to convert apps from AppImage.Github.io to installation scripts for "AM" Application Manager.

### INSTALL
Use "AM" to install this script, run the command:

    sudo am -i aih2am
    
### UNINSTALL
With "AM":

    sudo am -r aih2am
Without "AM":

    sudo /opt/aih2am/remove

### USAGE

    aih2am convert $APPNAME
where `$APPNAME` is the name of the AppImage as it appear on the AppImage catalogue of [AppImage.GitHub.io](https://appimage.github.io/apps/).

NOTE: this works only if the AppImage is hosted on GitHub.com.

For more alternative templates, see the `-t` option of the main project, ie "AM" Application Manager.

WARNING: This script supports multiple arguments, so be sure to enter "`_`" or "`-`" in the names as they appear on the catalog's page.

### TEST
All you have to test is the download of the AppImage. During the download you can always press CTRL+C to abort.
Create a new empty folder and run the scripts there in a terminal window (the script will create a `tmp` and `icons` folder):
- if `wget` is downloadinding an AppImage, the script works as expected;
- if `wget` is not downloading what you need (maybe an AppImage for different architectures), then edit the created script (maybe the lines 28 and 54, or just the line 11) and try again.

## This script is part of [ivan-hc/AM-Application-Manager](https://github.com/ivan-hc/AM-Application-Manager).

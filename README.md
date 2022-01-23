# Wallpaper maker

This is a quick and dirty script creating wallpapers that will fit the entire screen without cutting off parts of the image. It's achieved by copying a blurred version of the image to the background.

The script takes the following arguments:

- source directory
- destination width
- destination height
- delay (seconds, optional) - the script is intended to be run on system startup so by default it waits a little to avoid immediately starting any heavy processing

To store the adjusted wallpapers, it will create a directory called "XYZ - adjusted" where XYZ is the name of the source directory.

Check the source code before using. The script shouldn't mess up your original wallpaper directory, but there isn't a lot of error checking, so you might want to familiarize yourself with the code before trying it for the first time.

It's best to run it manually the first time (with delay argument set to 0) to create the initial wallpaper directory and check for any major errors. Then set it up to run on launch.  
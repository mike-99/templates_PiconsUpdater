templates_PiconsUpdater
=============================

This GIT Repository is used for enigma2-plugin-extensions-piconsupdater. 

How does the plugin work?
The plugin downloads picons and backgrounds from this repository - based on channels which are in your bouquets.
Within the plugin you can select target size of picons, target background of picons and the target location to generate the picons to.

Feel free to add additional picons or backgrounds you want to have selectable in the plugin.

PiconsUpdater creates a logfile with missing picons and needed filename:

>Picons not found for '1' channels

>/tmp/piconsupdater/picons-all/1_0_1_372C_8D_270F_FFFF0000_0_0_0.png;https://raw.github.com/gigablue-support-org/templates_PiconsUpdater/master/picon_all/travel-channel-deutschland.png

* Added picons need to be:
  * Size 220x132 pixel
  * RGB PNG
  * Transparent - no background!
  * Service logo should have a safety distance of about 10 pixel to borders
  * Filename basically is the servicename in your channellist (lowercase and spaces replaced by minus):
    * "Das Erste HD" -> das-erste-hd.png
    * "BR Süd HD" -> br-sued-hd.png
* Added backgrounds need to be:
  * Size 220x132 pixel
  * RGB PNG


How to download the plugins: 

The current version of the development / testing plugin you can play with is here: 
https://github.com/scottbragg/GroundControl/tree/development/LightwavePlugins/GroundControl/plugins

Download the groundcontrol.p  file and copy it to wherever you're putting your 3rd party plugins.  Add it to Layout and Modeler.  And you're good to go.   I'll write up documentation on this eventually.   

Testing for Lightwave 2020 will continue soon (no, really, I mean it this time).  If anyone with LW2020 has given this a try, let me know how it worked or didn't work in the issues area.  Thanks. 


NOTE: I am in need of test files for the edge cases you have had issues with or that have pushed GC to it's limits.  I am testing and debugging GC for 2018-2020 fixes (and will backport to 2015 if there's enough interest.   

NOTE 2:  I am going to be creating a new project soon to host the a rewrite of GC in python to allow me to use some of the fabulous data libraries available out there and provide platform agnosticism across both Windows and Mac releases.   I may even roll a standalone version with it's own interface that includes export as image based heightfields and OBJ, FBX*, and of course, LWO2 and LWO3 formats.   

I need help and feedback from users of this plugin to continue.  I need to know what works, what doesn't work, what you want changed.   A vast majority of my landscape and geoform work now goes through Gaea, Terragen, World Machine and lately (experimentally as I learn it) World Creator before moving to Lightwave.   I still want an integrated "click and load" option for LW and I assume all of you GC fans do too.  



(And now, for the rest of the story)
The awesome folks at DCG have open sourced their great suite of plugins for Lightwave.  Others have taken on the quest to update the shaders to the new model for LW 2018.   I'm much more involved in projects that need landscape and geodata and have taken a stab at getting this working under LW 2018 and 2019.   

Modifications needed to get GroundControl working with LW 2018 and 2019 are in place.  It appears to be stable and consistent across versions.  I do not have any versions prior to 2015 to test against.  If you do, and encounter issues, open an Issue with as much detail as you can and I'll see what can be done to track it down.   

I am looking for sample files for each of the data types GC supports to add to my test suite.  If there's something you use regularly, please let me know what it is and where I can get it so I can make sure it continues to be supported and stable going forward.  

If all you want is the plugin, download the groundcontrol.p file, copy it to wherever you store your plugins, and add it to Modeler and Layout. The GUI comes up when you attempt to load a supported file type so there's no need to add a menu item to any of the Menu bars.

Scott

The development branch is always going to the be most recent build and may or may not be stable.  Use at your own risk.  

Scott






Original plugin written by and open sourced by:

dcg

Digital Carvers Guild plug-ins
http://www.digitalcarversguild.com
https://github.com/ewinemiller/dcg

(Moved to the top so people can find it more easily)
The current version of the development / testing plugin you can play with is here: 
https://github.com/scottbragg/GroundControl/tree/development/LightwavePlugins/GroundControl/plugins

Download the groundcontrol.p  file and copy it to wherever you're putting your 3rd party plugins.  Add it to Layout and Modeler.  And you're good to go.   I'll write up documentation on this eventually.   

Testing for Lightwave 2020 will happen soon.  If anyone with LW2020 has given this a try, let me know how it worked or didn't work in the issues area.  Thanks. 


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

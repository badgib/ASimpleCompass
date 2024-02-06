## a simple compass for MUSHClient ##

made for sailing in discworld

images weren't that important
* i'm tired
  * will fix it
soon

### what's new ###

added auto show/hide on start/end of sail
window is resizable

### installation ###

* go to MUSHCLient directory, make my_plugins or select some path
  * put all the files in there
  * open the _compass.xml_ file in any text editor
    * edit the _plugin_dir_ variable to point to selected diredtory
* in MUSHClient:
  * file
    * plugins (or __ctrl + shift + p__)
  * click the _add_ button
  * browse to the .xml and select it
  * close the window
  * save! (__ctrl + s__)
  * enjoy

### commands ###

* !sailwin - toggles the window visibility
* !sailpos - resets the window position
* !sailres - resets the heading 

### one more thing ###

existing triggers might interfere with the functioning of this plugin
it is highly advised to remove them

anything that captures lines:

* (Squinting up at the sun|Gazing up at the stars), you determine that the ship is heading (HEADING) and that you're (NUMBER) miles rimwards and (NUMBER) miles (widdershins|turnwise) of Ankh-Morpork.

* The ship shudders around you as it turns (sharply) to (port|starboard).

* The powerful headwind causes the ship to drift off course to (port|starboard).

* The ship abruptly starts spinning in circles.  After a few rounds, it manages to escape the whirlpool, heading in a different direction from before.

should be removed

## TODO ##
* fix graphics
* add proper window scaling

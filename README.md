## a simple compass for MUSHClient ##

made for sailing in discworld
keeps track of current heading based on messages being displayed

### thanks go to ###

Kiki totally for testing, finding issues i didn't notice and, of course, the new, beautiful graphics!

### what's new ###

* all new graphics provided by Kiki!
* added auto show/hide on start/end of sail
* window is resizable (__!compass size \<value\>__)
* background colour can be switched without editing the plugin
* size can be reset with '!compass size
* no need for full path! just the plugin directory name

### installation ###

* go to MUSHCLient directory and select a directory for the plugin 
  * put all the files in there
  * open the _compass.xml_ file in any text editor
    * edit the _plugin_dir_ and put the selected name inside
* in MUSHClient:
  * file
    * plugins (or __ctrl + shift + p__)
  * click the _add_ button
  * browse to the .xml and select it
  * close the window
  * save! (__ctrl + s__)
  * enjoy

### commands ###

* !compass toggle - toggles the window visibility
* !compass position - resets the window position
* !compass heading - resets the heading
* !compass size \<value\> - changes the size of the window
* !compass colour \<name\> - changes background colour (string name)

### one more thing ###

existing triggers might interfere with the functioning of this plugin
it is highly advised to remove them

anything that captures lines:

* (Squinting up at the sun|Gazing up at the stars), you determine that the ship is heading \<heading\> and that you're \<number\> miles rimwards and \<number\> miles (widdershins|turnwise) of Ankh-Morpork.

* The ship shudders around you as it turns (sharply) to (port|starboard).

* The powerful headwind causes the ship to drift off course to (port|starboard).

* The ship abruptly starts spinning in circles.  After a few rounds, it manages to escape the whirlpool, heading in a different direction from before.

should be removed

## TODO ##

* think of new things to break
* think of new things to add

# Apple-Sticky-Desktop
Display the contents of any Apple Stickies note on your desktop using
[GeekTool](http://projects.tynsoe.org/en/geektool/).


![Screenshot](/screenshot.png)

# Installation

1. Install [GeekTool](http://projects.tynsoe.org/en/geektool/)
2. Open DisplayStickly.glet with GeekTool
3. Open Refresh.glet with GeekTool, modify script to replace PATHTOSCRIPT with the path to ReadToDoSticky.scpt
4. Refresh GeekTool twice
5. Most recently selected sticky will display

**Note:** The most recently selected sticky will display. GeekTool does rerun the scripts regularly, but if you want to immediately update the displayed text, refresh GeekTool twice.

**Another Note:** The file .todo.txt will be created in your User directory. It will be invisible (assuming hidden files are hidden). If you have any interest in using this file for any other reason, you can always change where it is saved by changing the initial value of ```the_path``` in the script.

Inspired by [Claudio d'Angelis'](https://github.com/claudiodangelis) [Stickies Exporter](https://github.com/claudiodangelis/tools/blob/master/Stickies.app%20exporter/Stickies%20Exporter.applescript).

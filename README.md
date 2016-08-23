### Welcome to Sumo Robot League's fork of the BlocklyDuino fork of MakeWithArduino

[![Join the chat at https://gitter.im/okhiroyuki/BlocklyDuino](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/okhiroyuki/BlocklyDuino?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

BlocklyDuino is a **web-based visual programming editor for [Arduino](http://www.arduino.cc/)**.

BlocklyDuino is based on [Blockly](https://developers.google.com/blockly/), the web-based, graphical programming editor. Provide static type language blocks and code generators for Arduino programming.


[We also have Google+ Page](https://plus.google.com/111979846292233941175).

### Features

* Programming Arduino with visual drag and drop blocks 
* Generate fully compatible Arduino source code

### Demo

We hope to have a demo online soon, but you can still...

### Run locally on your web browser

If you want to install it locally. Get code from github and open `blockly/apps/blocklyduino/index.html` in your browser.

The preffered way is to put the BlocklyDuino/web folder into a web server and open the url like localhost/public/blockly/demos/blocklyduino/index.html for use.

### Integrated Arduino upload

To avoid the tedious step of manually pasting code to the Arduino IDE, you can run a mini webserver that uses
[ino](https://github.com/gumbypp/ino) to upload the code to a connected Arduino board on Mac OS X and Linux systems.
Invoke this command from the BlocklyDuino root folder:

```
python ino_web_server.py
```

### Usage

1. Open browser to BlocklyDuino, drag and drop blocks to make an Arduino program
2. Select the 'Arduino' tab and copy all of the source code into an existing or new project in the Arduino IDE
3. Press the 'Upload' button in the Arduino IDE to burn the code into a connected Arduino board

OR (if running `ino_web_server.py`):

1. Open browser to BlocklyDuino, drag and drop blocks to make an Arduino program.
2. Select the 'Arduino' tab and press the 'Upload' button. (press the 'Reset' button to upload an empty program)

### ChangeLog

Check changelog [here](https://github.com/gasolin/BlocklyDuino/blob/master/CHANGELOG.txt)

### Authors and Contributors
Fred Lin (@gasolin) .
Thanks Neil Fraser, Q.Neutron from Blockly https://developers.google.com/blockly/
Thanks Dale Low (gumbypp) for contribute the python server to pipe BlocklyDuino source to arduino board.
Thanks Arduino and Seeeduino guys for Arduino and Grove blocks.
Thanks okhiroyuki for developing the MakeWithArduino fork

The project is also inspired by [arduiblock](https://github.com/taweili/ardublock) and [modkit](http://www.modk.it/)

### License

Copyright (C) 2016 Sumo Robot League  [web] www.sumorobotleague.com

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *   http://www.apache.org/licenses/LICENSE-2.0

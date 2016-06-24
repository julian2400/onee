# onee.moe #
![banner depencies](https://david-dm.org/daswolke/onee.svg)
![banner dev-depencies](https://david-dm.org/daswolke/onee/dev-status.svg)
![banner travis](https://travis-ci.org/DasWolke/onee.svg?branch=nightly)
[![Code Climate](https://codeclimate.com/github/julian2400/onee/badges/gpa.svg)](https://codeclimate.com/github/julian2400/onee)
---
Version 0.2
## Setup ##
#### Requirements ####
- Graphicsmagick
- gulp
- node
- mongodb

---
#### Steps ####
1. npm install
2. in Node_modules/dhash/index.js
change this line
``var gm = require('gm').subClass({
                   	imageMagick: true
                   });
                   ``
to this:
``var gm = require('gm');``
3. node server.js

#### UI Changes ####
The Ui is build with React and Redux for State,
after Changes to it the bundle.js has to be recreated,
to do that type ``gulp bundle`` in the project root or use gulp and let the filewatcher do its thing

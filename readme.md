# standard-format

  [![Build Status](https://travis-ci.org/videojs/standard-format.svg)](https://travis-ci.org/videojs/standard-format)
  [![Dependency Status](https://david-dm.org/videojs/standard-format.svg?style=flat-square)](https://david-dm.org/videojs/standard-format)

  **experimental** auto formatter for the easier cases in [videojs-standard](https://www.npmjs.com/package/videojs-standard)

  [![NPM](https://nodei.co/npm/videojs-standard-format.png)](https://nodei.co/npm/videojs-standard-format/)

## Installation

  Install with npm

    $ npm install -g videojs-standard-format

## Example Usage

  Output all formatted javascript in a directory and subdirectories to stdout

    $ standard-format

  Format all javascript files, overwriting them into standard format

    $ standard-format -w

  Format javascript over stdin

    $ standard-format < file.js > formatted-file.js

  Format and overwrite specific files

    $ standard-format -w file1.js file2.js

### Editor plugins

  - Sublime Text: [sublime-standard-format](https://packagecontrol.io/packages/StandardFormat)

# Credits

This is a fork of [maxogden/standard-format](https://github.com/maxogden/standard-format)

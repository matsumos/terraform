# polymer

Pre-processor for the Harp APF.

## Usage

    var polymer = require('polymer')

    polymer.process("foo.jade", { root: __dirname }, function(error, body){
      console.log(body)
    })


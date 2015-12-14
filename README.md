
# WebGL

A WebGL demo experiment

## Description

A collection of primitive shapes and basic effects.

- based on [Three.js](http://www.threejs.org), a WebGL wrapper library. Link to official Three.js [Documentation Manual] (http://threejs.org/docs/)

## Setup

    $ npm install

## Test

    $ npm test

## Usage

    $ var config = require(./config);
    $ var path = require(path)
      var viewGL = require('view-gl)
    $ var scene = viewGL()
    
    function onError(error){
        console.log(error);
    }
    
    function onInitialized(){
        var createIfNotExisted = true;
    }
    
    //start the test
    scene.initialise().then(onInitialized, onError);
    
    
## License

    [MIT License](http://opensource.org/licenses/MIT).

## Written by
    
    [Parvez K](emailto:flamboyanz@gmail.com)
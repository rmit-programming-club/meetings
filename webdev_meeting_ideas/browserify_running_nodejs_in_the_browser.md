## Browserify: Running Node JS in the browser

### Prerequisites

1. Install [Node JS](https://nodejs.org/en/download/)
2. Check installation of NodeJS and NPM (installed with NodeJS): `npm -v` and `node -v`

### The Problem

If you want to develop some Javascript the needs to run in a browser **and** want to make use of the NodeJS development and package ecosystem, much of which involves code that is incompatible with a browser, then you'll need a way to transform browser-incompatible code into compatible code.

### *1* Solution

http://browserify.org/

I made use of it recently for [thundergolfer/better-hackerrank-test-workflow](https://github.com/thundergolfer/better-hackerrank-test-workflow). (currently private)

### Meeting activities

* Use browserify to transform some NodeJS script into browser compatible code and run it in your browser
* Talk about exactly *what* browserify is doing under the hood
* Talk about alternatives to browserify that solve the same problem, possibly in different contexts (eg. webpack)




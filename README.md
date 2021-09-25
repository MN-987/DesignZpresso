## Introduction

DesignZpresso is a design tool for Mac, Windows, Linux, ChromeOS and the Browser made
in the spirit for Freehand and Fireworks. It is completely written in HTML5,
Javascript and CSS3. DesignZpresso consists of the core engine called "Infinity", the
actual Application and the core Module called "DesignZpresso".

We'd like to encourage everyone in getting involved with this project. You can
develop new features or take a ticket and fix it. Or if you're a UX/Designer, you
could help designing new icons or improving the UI. To get started contributing,
read the [GitHub Guide](https://guides.github.com/activities/contributing-to-open-source/)

## Prerequisites

* NodeJS + NPM
* Grunt Client
* Bower
* SASS + Compass

## Quick Start

Install all prerequisites and make sure they're available on your path.

Then run `npm install` to install all nodejs dependencies
Then run `bower install` to install all client javascript libraries

Finally run `grunt`. You can then open DesignZpresso in your
webbrowser at http://127.0.0.1:8999/.

We recommend using Chrome as this is the browser also used for the standalone
version.

## Quick Overview

+ assets - contains all relevant assets like fonts, images, etc.
+ shell - contains platform-specific code for standalone version
+ src - contains all source code
  + application - contains the application framework
  + development - contains the development addon automatically loaded when developing
  + DesignZpresso - contains the core module that is loaded by the application and provides all UI of DesignZpresso
  + infinity - contains the core rendering engine as well as core classes used everywhere else
  + infinity-editor - contains editors, tools, guides and more based on infinity
+ style - contains all styling files for the application
+ test - contains all test files



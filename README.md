## ADON Transaction Visualizer ##

<div align="center">

[![GitHub license](https://img.shields.io/github/license/AdonisNetwork/ADON-Visualizer)](https://github.com/AdonisNetwork/ADON-Visualizer/blob/gh-pages/LICENSE)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/AdonisNetwork/ADON-Visualizer)
[![GitHub commits](https://badgen.net/github/commits/AdonisNetwork/ADON-Visualizer/gh-pages)](https://GitHub.com/AdonisNetwork/ADON-Visualizer/commit/gh-pages/)
[![GitHub latest commit](https://badgen.net/github/last-commit/AdonisNetwork/ADON-Visualizer/gh-pages)](https://GitHub.com/AdonisNetwork/ADON-Visualizer/commit/gh-pages/)

</div>

Current version hosted at [**visualizer.adonis.network**](https://visualizer.adonis.network). Forked from a project formerly known as "Listen to Bitcoin" (ListenToBitcoin.com has been sold.)

Realtime ADON transaction visualizer written in HTML/Javascript. See and hear new transactions and blocks as they propagate through the ADON Network.

### Building ###

The project is built and ready-to-go. If you change any of the javascript, you will need to re-build the `bitlisten.min.js` file using Grunt. If you haven't used Grunt before, here is a short tutorial:

1. [Install Node.js](https://nodejs.org/download/).

2. Install grunt-cli using `sudo npm install -g grunt-cli`.

2. Cd into the project directory and run `npm install` to install the proper Grunt version and dependencies for this project.

3. Run `grunt` to build ADON-Visualizer. Alternatively, run `grunt watch` to build ADON-Visualizer, host it at http://localhost:8000, and watch for and rebuild changes in the source files.

The compiled/minified script will be output to `bitlisten.min.js`.

### APIs and Libraries ###

ADON-Visualizer uses these libraries:

* [Howler.js](http://goldfirestudios.com/blog/104/howler.js-Modern-Web-Audio-Javascript-Library) by James Simpson

ADON-Visualizer uses these APIs:

* ADON Block Explorer REST API (For Transactions and Blocks)


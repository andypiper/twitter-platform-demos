# Twitter Platform Demos

This repository contains the source code for demos using the Twitter APIs. They are all written in JavaScript using Node, HTML5, WebSockets and more.

These demos were originally created by [Romain Huet](https://twitter.com/romainhuet) as part of his speaking engagements while he was part of [the @TwitterDev team](https://twitter.com/TwitterDev).

## Overview

Here is an overview of the demos in this repository:

 * Monitoring and filtering Tweets in real time from the public [Streaming APIs](https://dev.twitter.com/streaming/public)
   * Count Tweets from the [sample](https://dev.twitter.com/streaming/reference/get/statuses/sample) endpoint
   * Display Tweets on a map based on browser geolocation
   * Find and curate Tweets into a [Collection](https://dev.twitter.com/rest/collections)
 * Tweeting pictures from a [Raspberry Pi](http://www.raspberrypi.org/) and its Camera Module
 * Controlling a [Parrot AR.Drone](http://ardrone2.parrot.com/) from Tweets and acknowledging commands

## Setup

You will need to obtain Twitter App credentials from [apps.twitter.com](https://apps.twitter.com/) to setup your own `config.js` based on the sample file in each demo folder.

Install the package dependencies from npm by running `npm install` and you are all set!

To get started with the demos, just run the corresponding Node program, for instance using `node streaming/server.js` for the Streaming APIs demos in the browser.

## Questions?

The Twitter Developer Relations team at [@TwitterDev](https://twitter.com/TwitterDev) is here to help for any questions related to the Twitter platform. You can also find assistance on our [developer forums](https://twittercommunity.com).

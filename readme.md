## Introduction

Feathers is a light weight web application framework that rides on top of [Express](http://expressjs.com), one of the most popular web frameworks for [NodeJS](http://nodejs.org/). It makes it easy to create RESTful web services and real-time applications using SocketIO and several other NodeJS real-time libraries.

If you are not familiar with Express head over to the [Express Guides](http://expressjs.com/guide.html) to get an idea. Feathers works the exact same way except that `var app = require('express')();` is replaced with `var app = require('feathers')()`. The most important concept that Feathers adds to Express middleware is data oriented **Services**. How services work and the API additional to the available [Express API](http://expressjs.com/api.html) is outlined in the following documentation.


## Why?

We know! Oh God another NodeJS framework! We really didn't want to add another name to the long list of NodeJS web frameworks but also wanted to explore a different approach than any other framework we have seen. We strongly believe that data is the core of the web and should be the focus of web applications.

We also think that your data resources can and should be encapsulated in such a way that they can be scalable, easily testable and self contained. The classic web MVC pattern used to work well but is becoming antiquated in today's web.

With that being said there are some amazing frameworks already out there and we wanted to leverage the ideas that have been put into them, which is why Feathers is built on top of [Express](http://expressjs.com) and is inspired in part by [Sails](http://sailsjs.org), [Flatiron](http://flatironjs.org) and [Derby](http://derbyjs.com).

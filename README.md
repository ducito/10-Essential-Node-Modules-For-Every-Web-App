# 10 Essential Node Modules For Every Web App

Are you new to developing Node.js based web apps? If yes, here is a list of 10 essential Node modules you will need in almost every web project.

## [Express](http://expressjs.com/)

Express is a Sinatra inspired minimal web framework for Node.js. Express 4 is even more powerful and simpler to use. Since its inception Express has acquired the status of de-facto web framework for Node.js. No doubt we have several other good web frameworks like [Locomotive](http://locomotivejs.org/), [Sails](http://sailsjs.org/#/) etc. But Express is the first choice for many developers when it comes to developing Node.js web apps.

## [Mongoose](http://mongoosejs.com/)

MongoDB is Node's best friend. Mongoose, the ODM library for Node.js, helps you interact with MongoDB easily. It offers a beautiful schema based solution for modelling your application data. If you are using MongoDB as your database, MongooseJS is definitely useful as the ODM solution.

## [Node_Redis](https://github.com/mranney/node_redis)

Node Redis is the redis client for Node.js. If you are not aware, redis is an advanced in-memory key-value cache and store. Redis can be used for different purposes in different web apps. Although Redis is a great pub/sub messaging system, many use it for simple caching as well. So, at one point you may need to have redis and node_redis installed in your app.

## [Async](https://github.com/caolan/async)
Async is a node module that provides powerful functions to work with asynchronous JavaScript. In Node.js many times you will need to process several things in parallel or follow a particular control flow. This is where async module comes in handy.

## [Request](https://www.npmjs.org/package/request)
Request is a simple utility that helps you make HTTP calls easily from your Node.js app. Almost every web app needs to make external API calls. Request module supports all types of HTTP requests including GET, POST, PUT, and DELETE. This makes request an excellent choice for interacting with REST APIs.

## [Forever](https://github.com/nodejitsu/forever)
Forever is a Node module (also available as CLI tool) keeps your server up forever. If your app ever crashes or enters an invalid state it's necessary to restart it. This is exactly what Forever does. So, as you can imagine the need of Forever module can't be ignored in a production app.

## [Underscore](https://www.npmjs.org/package/underscore)

Underscore is a utility library that provides 100+ functional programming helpers without extending core JS objects. You can use functions like each, map, reduce, filter etc easily within your app. If you are starting a new Node.js project it's a good idea to include underscore.

## [CSURF](https://github.com/expressjs/csurf)
A web application must take measures to prevent CSRF attacks. CSURF is a middleware that can help you protect your app from CSRF attacks. This module needs either [session](https://github.com/expressjs/session) middleware or [cookie-parser](https://github.com/expressjs/cookie-parser) in order to work. So, you need to include these modules as well.

## [Grunt/Gulp](https://www.npmjs.org/package/grunt)

Every app needs a build tool. [Grunt](https://www.npmjs.org/package/grunt) is a popular Node module that helps you automate repetitive tasks. [Gulp](http://gulpjs.com/), on the other hand, is relatively new and relies on code-over-configuration to keep build process simple. If you are starting a new project you are going to need either Grunt or Gulp.

## [Jade/EJS](http://jade-lang.com/)

[Jade](http://jade-lang.com/) and [EJS](http://www.embeddedjs.com/) are template engines for your Node.js web app. Both are good and it's difficult to say if one is better than the other. But if you need a template engine try out these two and use the one you like.

I think every Node.js web app needs these 10 modules. Did I miss anything? Let us know your favourite Node modules without which you can't imagine the next project.

Thanks for reading! If you liked the article keep sharing and subscribe to our cool newsletter using the form below.

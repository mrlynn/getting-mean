![MongoDB](../images/header.png "MongoDB")
# Getting MEAN
## An Introduction to API-Centered Application Development with Node.js and MongoDB
## Quest 4: Building an APP and an API

In the last [quest](../workshop/quest3.md), we created a server process that will listen for incoming requests.  We created a dummy response to those requests in that quest.  Now, we'll build on that and create an application which will intelligently handle those requests rather than just responding with static text.

Let's start the process of building our application by installing another super helpful tool called `ExpressJS`.  ExpressJS is a web development framework that simplifies a lot of the tasks associated with building an application.  It also embraces the `MVC` - or Models, Views and Containers methodology of development. 

To install ExpressJS:

```
npm install express --save
```

This will download all necessary components and install ExpressJS.  It's important to note that the libraries associated with ExpressJS will be installed into the `node_modules` subdirectory.

Once installed, we can now begin the process of using ExpressJS in our application.  Let's create a minimal ExpressJS application.

```javascript {.line-numbers}
const express = require('express');
const app = express();

app.use((req, res, next) => {
    res.status(200).json({
        message: "You're becoming a hero!"
    });
});

module.exports = app;
```



## Weapons, Tools and Resources

## Concepts

## Helpful Hints

## Next Quest

Next quest: `workshop/quest4.md` - Creating an API

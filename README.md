#React Universal Blog
#####[View a demo here]
#####[Go to Cosmic JS to set up a bucket for your blog content](https://cosmicjs.com/)

#####About
The React Universal Blog is a portfolio blog app that renders html on the server to make all pages visible to search engines. Then after initial load from the server, it is converted to a single page application to allow for fast navigation between pages. I created this app as part of a tutorial on React from the site on SitePoint(https://www.sitepoint.com/javascript). It is a basic site it does not have any blog entries available as of yet, will be working on adding pages to it over the next few weeks. It is an excellent tutorial for learning how ReactJS works it is well put together with many explainations of how each section is added and what they all do. The info below is originally from Tony Spiro. Cosmicjs.com also has the same app already built, just need to locate it and set it up. I am working on getting the demo up on Code Anywhere.

#####Notes
I tried to keep the organization as simple as possible.  There are no client, server or shared component folders.  All components are shared and the only difference between client and server are the entry points (app-client.js, app-server.js and app.js). 

It uses the following:
<br>
1. [React](http://facebook.github.io/react/) for UI views<br>
2. [Express](http://expressjs.com/) for server side rendering<br>
3. [React Router](https://github.com/rackt/react-router) for routing<br>
4. [React Hot Loader](https://github.com/gaearon/react-hot-loader) for hot loading in development<br>
5. [Flux](https://facebook.github.io/flux/) for data flow<br>
6. [Cosmic JS](https://cosmicjs.com) for content management
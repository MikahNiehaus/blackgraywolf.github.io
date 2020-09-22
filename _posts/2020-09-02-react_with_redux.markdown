---
layout: post
title:      "React with Redux"
date:       2020-09-02 13:01:10 -0400
permalink:  react_with_redux
---


I created a Sticky note React Redux Application that can be used for reminders. It uses proper RESTful routing, and is written in ES6. it has Redux middleware to respond and modify state change and makes use of async actions and redux-thunk middleware to send data to and receive data from a server. The Rails API handles the data persistence with a database using fetch(). My client-side application handles the display of data with minimal data manipulation.

I truly appreciate the effectiveness of React with Redux. I got to see how much faster my program got before and after I got it to update individual components instead of the entire page. I think it's very interesting that React and Redux is just normal javascript, it's quite literally just a html document with a divider with the id of root that you put everything in. All your components then return JSX too said root and then give your components a shared state in the reducer and then BOOM you made a React with Redux application. Now your application will run extremely fast because instead of the entire page being re-rendered only small components that have been changed will be re-rendered making it extremely fast. 

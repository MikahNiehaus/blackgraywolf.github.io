---
layout: post
title:      "React with Redux"
date:       2020-09-02 17:01:09 +0000
permalink:  react_with_redux
---


I was not able to truly appreciate the effectiveness of React with Redux until I finished my project. I got to see how much faster my program got before and after I added got it to update individual components instead of the entire page. I think it's very interesting that React and Redux is just normal javascript, it's quite literally just a html document with a divider with the id of root that you put everything in. All your components then return JSX too said root and then give your components a shared state in the reducer and then BOOM you made a React with Redux application. Now your application will run extremely fast because instead of the entire page being re-rendered only small components that have been changed will be re-rendered making it extremely fast. 

---
layout: post
title:      "Sinatra Lab"
date:       2020-04-11 17:11:37 -0400
permalink:  sinatra_lab
---


My MVC Sinatra application was an offshoot of reddit called reddthat. I used ActiveRecord with Sinatra to create my project. I used multiple models with a has_many relationship on the User model and a belongs_to relationship on another model. It has a user account - users can sign up, sign in, and sign out. it validate uniqueness of user login attribute (username or email). Once logged in, the user has the ability to create, read, update and destroy the resource that belongs_to user. Users can edit and delete only their own resources - not resources created by other users. it will Validate user input so bad data cannot be persisted to the database.

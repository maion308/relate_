# rElate
social network application
## Here is the live version
https://hidden-lowlands-86309.herokuapp.com/
# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for attending squad standup at the begining and end of the day.

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Create Project Repo | Complete
|Day 2| Wireframes / Priority Matrix / ERD | Complete
|Day 3| Create new rails app, create db, scaffolding, test postman | Complete
|Day 4| Create rails front-end create basic routing  | Complete
|Day 5| Create logic for views css styling, complete MVP  | Complete
|Day 6| Add final touches, deploy the application | Complete
|Day 7| Present | IncomCompleteplete


## Project Description

rElate is a bare bones social network application that that integrates daily new article feeds on the landing page. The user can register, create profile, create posts and view other users. 

## Wireframes

https://ninjamock.com/s/KMHCCFx

## Priority Matrix

<img src="">

### MVP/PostMVP - 5min

The MVP functionality of rElate application consists of user and post. A user can post and their post will be saved, with option to delete post. The user will have the ability to read current news feeds and search a news related topic

PostMVP will feature friends options, comments to posts and likes dislikes to posts.News feed will render on landing page using react

#### SAMPLE.....
#### MVP 

- Create registration form to create user
- Form should be able to create user and seed data if all params and conditions are satusfied

#### PostMVP 

- Create friends table and allow users to add friends

## Architectural Design

Main component is app.js and mvp components include header, nav, user, post, footer, create user, login and out.

https://ninjamock.com/s/KMHCCFx

## ERD

![alt text]('./erd_designs/Screen Shot 2019-11-07 at 10.14.07 AM.png')
![alt text]('./erd_designs/Screen Shot 2019-11-07 at 9.34.24 AM.png')
![alt text]('./erd_designs/Screen Shot 2019-11-07 at 9.58.12 AM.png')
![alt text]('./erd_designs/Screen Shot 2019-11-07 at 9.59.26 AM.png')

## UI Components

I will use rails front end and will parsel each post view inside index.html.erb in posts folder
index.html.erb will render in order what we want viewed
forms.html.erb will render the forms using bulma
feed.html.erb will render the posts and allow postmvp functionality
trends will render what is trending view in post mvp

#### SAMPLE.....
| Component | Description | 
| --- | :---: |  
| feed | This will render data depending on sign in status | 
| Form | This will render forms | 
| Register | This component will render a form that accepts user input | 
| Index.html.erb| This will render main page | 
| Post | This component is rendered after sign in, will render form to post text|


Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe.

#### SAMPLE.....
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: |
| create rails app, basic setup | H | 2hrs| |
| generate models, migrate, controllers, rest api crud, seed, auth, routes | H | 8hrs|  |
| create rails front end views | H | 3hrs|  |
| api calls testing rendering api data| H | 3hrs|  |
| creating forms and validation | H | 5hrs|  |
| create lifecycle, functions, logic  | H | 8hrs| |
| manage views develop views with bulma and add features | H | 3hrs|  |
| putting all views together having full layout of features working | H | 4hrs|  |
| css styling | H | 6hrs|  |
| version control via git -- add ., commit, push etc| H | 3hrs| |
| deploy | H | 3hrs|  |
| Total | H | 48hrs|  | 

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

#### SAMPLE.....
| Function | Description | 
| --- | :---: |  
| Capitalize | This will capitalize the first letter in a string of text | 

## Additional Libraries
bulma, sass, react-rails, guard
 
 #### SAMPLE.....
| Library | What it Does | 
| --- | :---: |  
| axios | javascript library for http requests, helps simplify calls like no need to .stringify and .json it has built in functionality to ease api calls | 
| News Api | https://newsapi.org/ used to get news feeds | 


## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

#### SAMPLE.....
```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Change Log
trying to use this gem 
https://rubygems.org/gems/react-rails/versions/1.7.1
I made attempt to work with react-on-rails-gem instead of building the client folder and create-react-app so that I can be more efficient with files and folders. I am only using react to do some 3rd party api calling and I went a new route with the react-rails gem, but I am having difficulty working with the documentation on it, as it is not working as I am following along and trying to do my own thing of it.
This will be a great learning experience once i get it to work and I will continue to improve the app and do what I actually want out of it.

#### SAMPLE.....
| Original Plan | Outcome | 
| --- | :---: |  
|  |  | 

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**:                               
**RESOLUTION**: 


### sources and documentation used to help the build of this app
this was used to learn how to use and customize devise for authentication
https://github.com/plataformatec/devise

This documentation was used to learn how to use simple forms 
https://rdoc.info/github/plataformatec/simple_form/master/frames

thisa documentation was used as a guide to help further understand how customization works with rails gems devise, simple-form and bulma as it is a common collection made specifically for rails.

https://dev.to/justalever/lets-build-with-ruby-on-rails---a-twitter-clone---23f5
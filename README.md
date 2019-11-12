# rElate
social network application
# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for attending squad standup at the begining and end of the day.

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Create Project Repo | Complete
|Day 2| Wireframes / Priority Matrix / ERD | Incomplete
|Day 3| Create new rails app, create db, scaffolding, test postman | Incomplete
|Day 4| Create rails front-end create basic routing  | Incomplete
|Day 5| Create logic for views css styling, complete MVP  | Incomplete
|Day 6| Add final touches, deploy the application | Incomplete
|Day 7| Present | Incomplete


## Project Description

rElate is a bare bones social network application that that integrates daily new article feeds on the landing page. The user can register, create profile, create posts and view other users.

## Wireframes

https://ninjamock.com/s/KMHCCFx

## Priority Matrix

<img src="">

### MVP/PostMVP - 5min

The MVP functionality of rElate application consists of user and post. A user can post and their post will be saved, with option to delete post. The user will have the ability to read current news feeds and search a news related topic

PostMVP will feature friends options, comments to posts and likes dislikes to posts.

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

Rails front end will work with views
index.html.erb will render mostly main page
forms.html.erb will render the forms using bulma
feed.html.erb will render the posts and allow postmvp functionality

#### SAMPLE.....
| Component | Description | 
| --- | :---: |  
| Header | This component will render a background image and some font | 
| Footer | Footer component will include links to contact, and a variety of other links perhaps postmvp links| 
| Register | This component will render a form that accepts user input | 
| LandingPage| This component will render, search bar, news feeds and login sign up nav links | 
| Nav | This component will include links to login, sign in, landing page | 
| Post | This component is rendered after sign in, will render form to post text|
| signout | This component will allow a user to sign out with a button click| 



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
axios,
 
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
 Use this section to document what changes were made and the reasoning behind those changes.  

#### SAMPLE.....
| Original Plan | Outcome | 
| --- | :---: |  
|  |  | 

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**:                               
**RESOLUTION**: 

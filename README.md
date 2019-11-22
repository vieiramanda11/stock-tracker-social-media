# Ruby on Rails  - Stock Tracker Social Media

The main goal of this project is to build an application similar to a social media for people who follows stocks using:

* Ruby on Rails 5.2.3
* Bootstrap-Sass 
* Devise
* Stock Quote

## Live Version

[Heroku](https://stock-tracker-social-media-app.herokuapp.com/users/sign_in)

## Features

* Users
  * Sign-up / login / logout 
  * Show profile page with user's stocks
  * Add and delete Stocks
  * Has many stocks
  * Has many friendships

* Stocks 
  * Has many users (tracking)

* Friendships
  * Add and delete friends
  * Belongs to user
  * Belongs to friend

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

You are be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[The Complete Ruby on Rails Developer Course](https://www.udemy.com/course/the-complete-ruby-on-rails-developer-course/).
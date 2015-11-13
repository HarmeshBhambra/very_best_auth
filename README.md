# Very Best / Auth

## Introduction

In this project, we'll practice using the [Devise gem](https://gist.github.com/rbetina/9ef4a9ffa4604df74bb5) for authentication and authorization.

## Setup

 1. First **fork** and *then* clone your fork of this repository.
 1. `cd` into the application's root folder.
 1. `rake db:migrate`
 1. `rake db:seed`
 1. `rails s`

Navigate to [http://localhost:3000](http://localhost:3000) and click around to familiarize yourself with the application. **Note that I've provided some seed data for you so that you can get straight to work instead of wasting time creating a bunch of rows in each table.**

I have also already [included the Devise gem and done the initial installation](https://gist.github.com/rbetina/9ef4a9ffa4604df74bb5).

Now, we need to link to the sign-up, sign-in, and other RCAVs that Devise provides; and, most importantly, leverage the `current_user` method to tailor the experience for each user.

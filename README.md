## Advarra Technical Test

## Description
- - -
- Greg Byrne
- Technical test for Advarra/Longboat
- Ruby 2.6.3 & Rails 6.0.3

## Setup
- - - 
1. `bundle install` (Install gems)
2. `yarn install` or `npm install` (Install npm packages)   
2. `rails db:setup` (Setup database)
3. `rspec` (Optional: run tests)   
4. `rails s`  (Start application)

A postman collection has been included for convenience

## Specification
--- 
Rails application using SQL database.
Provides a user model that incorporates unique username,
password and a login failure count.

- HTML based UI that provides a user login 
(users created via console). 

- Upon successful login, users are presented with
log out option.
  
- Code accounts for login failures and locks
the user account after 3 consecutive fails.
Failure count upon a successful login before
lock out).

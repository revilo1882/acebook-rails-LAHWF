# AceBook - Fishbook

This is a collaborative project called Fishbook, an aquatic themed clone of the social media platform Facebook written using Ruby-on-rails as part of the engineering weeks at Makers Academy. Through this project, we learned how to work effectively and efficiently as a team, and were able to meet all requirements for the project with 100% test coverage.


## Contributing Developers
- [Salomé Lambermont](https://github.com/Slambermont)
- [Asia Antczak](https://github.com/asiaantczak)
- [Oliver Harris](https://github.com/revilo1882)
- [Sam Worrall](https://github.com/samworrall)
- [Robert Fishwick](https://github.com/afishcalledrob)


## Functionality

 A new user must sign up with an email and password, their first, last, and user-name, and can specify a profile picture, after which they will be redirected to the homepage, where all posts are listed.

 A user is able to edit or delete their account, either from the homepage or from their profile.

A user can create a post on the homepage, on their profile page, or on another user's profile page. Posts can be edited, deleted, commented on, liked, and disliked (one like/dislike per user). A live notification feed updates whenever a user performs one of these actions. Only the user who created a post can edit or delete it.

Any user's avatar can be clicked on, redirecting to their profile page.


## Technologies

| Tech | Testing | Gems |
|---|---|---|
| Ruby-on-rails, Ruby, PostgreSQL, HTML, CSS, jQuery, Travis-ci, Simplecov, Rubocop, Aws-sdk | RSpec-rails, Capybara, Factory_bot_rails | Devise, Paperclip, Acts_As_Votable, Public_activity |


## Standups and Retrospectives

As part of our day-to-day planning, we would have morning stand-ups to discuss the aims for that day and assign tasks, as well as afternoon retrospectives to reflect on what we had achieved/learned/had difficulty with. This helped us articulate and overcome problems we perceived would be blockers, and ultimately led to increased productivity.


## Card Wall
We used a Trello card wall to organise our 2 day sprints. Every ticket was estimated before being worked on, and each ticket was assigned to a pair or a three, and in some cases a solo developer.

Check out our Trello card wall by clicking the image below:

<a href="https://trello.com/b/FfooEp0e/acebook-lahwf"><img src="logos/Trello.png" height="80" width="190"></a>


## Finished Project

See the live Heroku application in action by clicking the image below:

<a href="https://morning-everglades-97311.herokuapp.com/"><img src="logos/Heroku.png" height="110" width="90"></a>


## Run the app locally

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```

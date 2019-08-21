# README

SammiChat is a simple and bare-bones messenger app. Send messages and receive messages from user to user. That's the end of it. SammiChat is especially useful for people who are trying to take their conversations to a more private platform, away from potential spying eyes. Basically no one knows about SammiChat, so no one is going to think to go spy on your SammiChat messages!

SammiChat uses Ruby version 2.6.3

SammiChat uses a code base of Ruby, PostgreSQL, and CoffeeScript

How To Use:

CLONE THE REPOSITORY
\$ git clone https://github.com/sammi4711/code-challenge-project

CD INTO THE CORRECT DIRECTORY
\$ cd pusher-chat

INSTALL DEPENDENCIES
\$ bundle install

DATABASE SETUP
$ rails db:setup
$ rails db:migrate

FIGARO & ENV VARIABLES
\$ figaro install <-- generate application.yml file
Open config/application.yml and fill in the following fields with your personal info:

- PUSHER_APP_ID
- PUSHER_KEY
- PUSHER_SECRET
- PUSHER_CLUSTER

Fire up your local server and try SammiChat today!

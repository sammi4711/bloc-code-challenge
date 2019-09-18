# README

Welcome to SammiChat!

The goal here was to build a simple messenger application that allows two users to send short text messages to each other, like Facebook Messages or Google Chat.

SammiChat is a simple and bare-bones messenger app. Send messages and receive messages from user to user. That's the end of it. SammiChat is especially useful for people who are trying to take their conversations to a more private platform, away from potential spying eyes. Basically no one knows about SammiChat, so no one is going to think to go spy on your SammiChat messages!

===

### APP DOWN FOR MAINTENANCE!

There is currently a bug in the app where the database is failing to compile. We will be back up and running as soon as possible! Until then, consider going back to the age of middle school and just passing paper notes. That was fun, wasn't it?

===

SammiChat uses Ruby version 2.6.3

SammiChat uses a code base of

- Ruby
- PostgreSQL
- CoffeeScript

===

### Special Features

Unlike other "secret messenger" apps such as Kik, you can use SammiChat on your computer! Make it seem like you're working on something super important when actually you're just being sneaky!

===

Take a peek at our code here:

json.extract! @chat, :id, :username, :message

json.url chat_url(@chat, format: :json)

===

## How To Use:

- CLONE THE REPOSITORY
  \$ git clone https://github.com/sammi4711/code-challenge-project

- CD INTO THE CORRECT DIRECTORY
  \$ cd pusher-chat

- INSTALL DEPENDENCIES
  \$ bundle install

- DATABASE SETUP
  $ rails db:setup
$ rails db:migrate

- FIGARO & ENV VARIABLES
  \$ figaro install <-- generate application.yml file
  Open config/application.yml and fill in the following fields with your personal info:

- PUSHER_APP_ID
- PUSHER_KEY
- PUSHER_SECRET
- PUSHER_CLUSTER

Fire up your local server and try SammiChat today!

===

### Built with guidance from Pusher-Chat.

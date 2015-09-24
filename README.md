Note: This branch (master) contains a skeleton without any app code, perfect for creating a new application or challenge. If you're looking for an example app built with this skeleton, take a look at the example branch which includes basic CRUD and RSpec tests.
Purpose

The Sinatra Skeleton:

Provides a foundation for building challenges or creating a new Sinatra application.
Demonstrates a reasonable set of practices around building Sinatra applications.
Eases the transition to Rails for Dev Bootcamp students
Quickstart

bundle install
shotgun config.ru
As needed, create models & migrations with the rake tasks:

rake generate:migration  # Create an empty migration in db/migrate, e.g., rake generate:migration NAME=create_tasks
rake generate:model      # Create an empty model in app/models, e.g., rake generate:model NAME=User
Contributing

We would love for you to help make the skeleton more awesome, There are three ways to contribute:

Ask for a bug fix or enhancement!
Submit a pull request for a bug fix or enhancement!
Code review an open pull request!
Be prepared to give and receive specific, actionable, and kind feedback!
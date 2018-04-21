= Expense Tracking (RoR)
---
 - In this application you can keep track of your expenses with your frieends.
 - you can create group with other people(those people must be registered user of the application otherwise you cannot add them in your group)
 - You can start adding expenses by doing add bill.
 - Application will keep track of your expense.

== Prerequisites for application

- Ruby version 2.0.0
- Rails version 3.2.13
- Database: mysql

== Setup
  1. Clone from the current repository.

  2. Get the latest code from **master** branch of the repository.

  3. Add the database.yml in *config/* directory.

  6. Run the following commands:-

      cd application_dir

      bundle install  # Install the necessary gems

      rake db:setup # Create the db, create the schema and load seed data.

      rails s  # Start the server

== Seed data
  * Prerequisites:
    * development.yml exists and has correct configuration.
    * database.yml exists and has correct configuration.

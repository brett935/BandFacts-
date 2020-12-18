# README

This app searches theaudiodb for a band name and then returns the response and displays the bands name and biography.

Dependencies:
    theaudiodb API is still reachable (https://www.theaudiodb.com/api_guide.php)
    Ruby 2.6.3p62 (2019-04-16 revision 67580)
    Rails 6.1.0
    Postgres with a user named bandfacts (or whatever you want just update username and password in database.yml)
    Run "rails db:create" to create the database if it doesn't exist

To run the Unit and Integration test run:
    rspec spec/*

TODO:
    Store Postgres password in an environment variable
    Better SCSS styling/layout
    Cleanup unused controller views/methods generated by RAILS scaffold

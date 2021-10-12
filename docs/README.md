Bookmark Manager

1st user story:

As a time-pressed user
So that I can quickly go to web sites I regularly visit
I would like to see a list of bookmarks

To view Domain model click [here](docs/bookmark_manager_1.png)

2nd user story:

As a time-pressed user
So that I can save a website
I would like to add the site's address and title to bookmark manager

## To create a new DB
- Connect to psql
- CREATE DATABASE bookmark_manager;
- Connect to the database using the pqsl command \c bookmark_manager;
- Run the query we have saved in the file 01_create_bookmarks_table.sql

## To set up a test DB environment
- Run psql
- CREATE DATABASE "bookmark_manager_test";
- Connect to the database using the pqsl command \c bookmark_manager;
- Run the query we have saved in the file 01_create_bookmarks_table.sql

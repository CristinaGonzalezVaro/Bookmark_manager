## Bookmark Manager

## User Stories

```
As a user, 
So that I can quickly access the regular web sites I visit
I would like to see a list of bookmarks
```

```
As a time-pressed user
So that I can save a website
I would like to add the site's address and title to bookmark manager
```

## Domain Model 
![alt text](https://github.com/CristinaGonzalezVaro/Bookmark_manager/blob/main/domain%20model.jpg)


## How to use
### To set up the project

Clone this repository and then run:

``` 
bundle
```

### To set up the database

Connect to `psql` and create the `bookmark_manager` and `bookmark_manager` databases:

```
CREATE DATABASE bookmark_manager;
CREATE DATABASE bookmark_manager_test;
```

To set up the appropriate tables, connect each database in `psql` and run the SQL scripts in the `db/migrations` folder in the given order.

### To run the Bookmark Manager app:

```
rackup -p 3000
```

To view bookmarks, go to `localhost:3000/bookmarks`.

### To run tests

```
rspec
```

### To run linting:

```
rubocop
```

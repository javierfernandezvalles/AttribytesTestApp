# AttribytesTestApp
A test application to begin Ruby on Rails Development.

## Contains the Projects:
- validationpal
...

## validationpal
### Description
* A system for PDF forms that contain accurate validation
* Storage of PDF data into a Database, allowing for metrics and increased organization/searchability

### Goals
* Replace paper/e-mailing of PDF's.
* PDF's contain proper validation

#### Environment
* Ruby (ruby 2.5.3p105 (2018-10-18 revision 65156) [x86_64-darwin17])
* Ruby on Rails (Rails 5.2.1)
* PostgreSQL (psql (10.5, server 10.1)) | (DB-ambiguous, subject to change) 
* Javascript/JQuery 
* HTML 5 / CSS / Bootstrap
* Rspecs

### Installation Instructions
* Clone this repo
```
$ git clone <GitHub Repo> 
```

* Navigate inside the validationpal directory
```
$ cd AttribytesTestApp/validationpal
```

* Create the DB and migrate it
```
$ rake db:create
$ rake db:migrate
```

_note:_ May Need to Remove the Database first
```
$ rake db:drop
```

* Install the Gems, using Bundler (my version: 1.17.1)
```
$ bundle install
```

* Run the application on your browser, it should show up on 0.0.0.0:3000/
```
$ rails s
```

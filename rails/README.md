## What is it ?

This document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


## How to run this ?
```bash
// dockerize

// Create Docker Image
$ sudo docker build -t rails-app:1.0 .
$ sudo docker run -d -p 3000:3000 -t rails-app:1.0

    access http://localhost:3000

// docker compose
$ sudo docker-compose up -d

    access http://localhost:3000
```
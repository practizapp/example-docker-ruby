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

## How to Usage

` Refer to your Linux distribution documentation for how to install Ruby `

## How to run this ?
```bash
// dockerize

// Create Docker Image
$ sudo docker build -f Dockerfile -t sinatra-app:1.0 .
$ sudo docker run -d -p 4567:4567 -t sinatra-app:1.0

    access http://localhost:4567
```

```
// docker compose
$ sudo docker-compose up -d

    access http://localhost:4567
```
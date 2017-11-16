# Tweeter Nodejs Project

## Steps

### Inspect the API Specification

You can find the specification in the file `api.json`, though I would recommend to use a UI for inspecting it: [OpenApiRenderer](https://temando.github.io/open-api-renderer/demo/?url=https://gist.githubusercontent.com/apricote/a09d4e7f4fd74225f5173be0b19fdf27/raw/939b3ce9531ef7bc9ceb35dba0217963f6487f61/tweeter.json)

### Sketch the Database schema

Based on the API Specification, define a database schema to save the data permanently.

### Setup a Nodejs Project

Use the `npm init` Command to initialize a nodejs project in this folder.

### Develop the API

The most standard way to develop an API in node these days is the `express` framework. Google for a guide and start hacking on the API.

I would recommand you to start with the simple Level 1 routes, and advance after that.

For storing the data you have multiple options:

1. Relational Database (mysql/mariadb)
1. Nosql Database (mongo)

You may use whatever you feel most comfortable with.
# Tweeter Nodejs Project

## Steps

### Fork the repository

To work on this project, fork it to your own account!

### Inspect the API Specification

You can find the specification in the file `api.json`, though I would recommend
to use a UI for inspecting it: [OpenApiRenderer][1]

[1]: https://temando.github.io/open-api-renderer/demo/?url=https://raw.githubusercontent.com/apricote/tweeter/master/api.json

### Sketch the Database schema

Based on the API Specification, define a database schema to save the data
permanently.

### Setup a Nodejs Project

Use the `npm init` Command to initialize a nodejs project in this folder.

### Develop the API

The most standard way to develop an API in node these days is the `express`
framework. Google for a guide and start hacking on the API.

I would recommend to start with the simple Level 1 routes and then proceed to
the higher levels.

For storing the data you have multiple options:

1. Relational Database (mysql/mariadb)
1. Nosql Database (mongo)

You may use whatever you feel most comfortable with.

### Optional: Build a UI

You have finished the main challenge but still want to do something? Build a
User Interface to interact with the tweeter service. This could be a native App
for mobile phones, or a Single Page Web App or anything else.

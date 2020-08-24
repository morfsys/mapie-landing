---
id: getting-started
title: Getting started
sidebar_label: Getting started
---

This page will help you start with Mapie CLI and develop and run your Mapie Server.

## Pre-requisites

Having a basic understanding of Javascript, ExpressJS features like Express App, Routing, Middlewares can help you get moving through your Mapie Server quickly. If not, we highly recommend you to gain some basic knowledge first, then come back here when you're done.

Here are some resources to help you out:

1. [Express Basic Routing](https://expressjs.com/en/starter/basic-routing.html)
2. [ExpressJS Middleware](https://expressjs.com/en/guide/writing-middleware.html)

## Installation

Install the CLI Engine by running the following command:
```bash
npm install -g mapie-cli
```
Mapie CLI provides provides you with all the utilities to start and run with your Mapie server and also some generators for quick and focused development.

Once the `mapie-cli` is successful, you can check the mapie version that is installed in your system by following:

```sh
pie version
```

> Note: we might need a terminal interface here to show how exactly it will look like

## Mapie Server

Now that we have the CLI up and running, let's dive into getting the Mapie Server bootrapped

### Create a Mapie project

In your target directory, run:

```sh
pie create myMapieServer
```

After successful execution, you will have a project created for you in the `myMapieServer/` directory

### Run your Mapie Server

```sh

cd myMapieServer
pie run

```

This will run your server on the default port `3712` and you can browse through the development Resource Map on `localhost:3712/mapie`

> Note: Make sure to set the field `production` to `true` in the `./bootstrap.js` file before deploying on the production

Now you are ready to develop and add APIs and functionalities to your Mapie Server.

Continue to ["Configuration"](hello-react-navigation.md) to start writing some code.

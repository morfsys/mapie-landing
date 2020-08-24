---
id: getting-started
title: Getting started
sidebar_label: Getting started
---

This page will help you start with mapie CLI and develop and run your Mapie Server.

## Pre-requisites

Having a basic understanding of Javascript, ExpressJS features like Express App, Routing, Middlewares can help you get moving through your Mapie Server quickly. If not, I highly recommend you to gain some basic knowledge and then come back here whenever feel comfortable.

Here are some resources to help you out:

1. [Express Basic Routing](https://expressjs.com/en/starter/basic-routing.html)
2. [ExpressJS Middleware](https://expressjs.com/en/guide/writing-middleware.html)

## Installation

Install the CLI Engine by running the following command:

```bash
npm install -g mapie-cli
```

mapie CLI provides you with all the utilities to start & run your Mapie Server and also some generators for quick and focused development.

Once the `mapie-cli` is successfully installed, you can check the mapie version that is installed in your system by following:

```sh
pie version
```

```sh
> v 1.0.0
```

## Mapie Server

Now that we have the CLI up and running, let's dive into getting the Mapie Server bootrapped

### Create a Mapie project

In your target directory, run:

```sh
pie create hello-world
```

After successful execution, you will have a project created for you in the `hello-world/` directory

### Run your Mapie Server

```sh

cd hello-world
pie run

```

This will run your server on the default port `3712` and you can browse through the development resource map on `localhost:3712/__mapie`

> Note: Make sure to set the field `production` to `true` in the `./bootstrap.js` file before deploying on the production

Now you are ready to develop and add APIs and functionalities to your Mapie Server.

Continue to ["Configuration"](hello-react-navigation.md) to start writing some code.

# Node Pack Base

The '[Node Pack Base](https://github.com/jgphilpott/docker-images/tree/master/node-series/node-pack-base)' is a collection of software packages commonly used in Node applications.

## Usage

To pull this image via the command line:

`docker pull jgphilpott/node-pack:base`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/node-pack:base`

## Contents

### Core

#### Dates/Times

 - [moment](https://www.npmjs.com/package/moment) - A date library for parsing, validating, manipulating and formatting dates.
 - [day](https://www.npmjs.com/package/dayjs) - A minimalist library that parses, validates, manipulates and displays dates/times.

#### Scheduling

 - [agenda](https://www.npmjs.com/package/agenda) - A light-weight job scheduling library for Node.
 - [cron](https://www.npmjs.com/package/node-cron) - A tiny task scheduler in pure JavaScript for Node.

### Frameworks

 - [express](https://www.npmjs.com/package/express) - A fast, unopinionated, minimalist web framework for Node.
 - [fastify](https://www.npmjs.com/package/fastify) - A fast and low overhead web framework for Node.
 - [koa](https://www.npmjs.com/package/koa) - An expressive HTTP middleware framework for Node.

### Linguistics

 - [coffeescript](https://www.npmjs.com/package/coffeescript) - A little language that compiles into JavaScript.
 - [typescript](https://www.npmjs.com/package/typescript) - A language for application-scale JavaScript.
 - [sass](https://www.npmjs.com/package/sass) - Syntactically Awesome Style Sheets that compile to CSS.
 - [pug](https://www.npmjs.com/package/pug) - A high performance HTML template engine.

### Networking

 - [ws](https://www.npmjs.com/package/ws) - A simple to use, blazing fast and thoroughly tested WebSocket client and server implementation.
 - [socket.io](https://www.npmjs.com/package/socket.io) - Real-time bidirectional event-based communication.

### Scraping

 - [axios](https://www.npmjs.com/package/axios) - Promise based HTTP client for the browser and Node.

### Testing

 - [jest](https://www.npmjs.com/package/jest) - Delightful JavaScript Testing.
 - [mocha](https://www.npmjs.com/package/mocha) - A simple, flexible and fun test framework for Node.

### Compilers

 - [browserify](https://www.npmjs.com/package/browserify) - A JavaScript bundler for the browser.
 - [babel](https://www.npmjs.com/package/@babel/core) - A compiler for writing next generation JavaScript.
 - [uglify](https://www.npmjs.com/package/uglify-js) - A JavaScript parser, minifier, compressor and beautifier toolkit.
 - [blade](https://www.npmjs.com/package/blade) - An HTML template compiler.

### Databases

 - [mongo](https://www.npmjs.com/package/mongodb) - The official MongoDB driver for Node.
 - [postgres](https://www.npmjs.com/package/node-postgres) - A PostgreSQL client for Node.
 - [mysql2](https://www.npmjs.com/package/mysql2) - A fast SQL driver for Node.

### Cryptography

 - [SHA](https://github.com/cryptocoinjs) - A popular One-Way Hash Algorithm available in [256](https://www.npmjs.com/package/sha256) and [512](https://www.npmjs.com/package/sha512) byte versions.
 - [ECDSA](https://www.npmjs.com/package/ecdsa) - An Elliptic Curve Digital Signature Algorithm for signing and verification.
 - [RSA](https://www.npmjs.com/package/node-rsa) - An RSA library for Node.

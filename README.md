# Node.js Concurrency Study

This repository contains a study on achieving concurrency in JavaScript, a language traditionally known for its single-threaded nature. Using Node.js, this project explores how JavaScript can handle concurrent tasks effectively by implementing three projects: **Matrix Multiplication**, **Hash Table**, and **Image Resizer**. These projects demonstrate concurrency patterns in Node.js and analyze their performance.

## Project Overview

JavaScript operates on a single-threaded event loop, which can make handling concurrent tasks challenging. However, with Node.js, we can implement concurrency to improve performance and efficiency for I/O-bound tasks and parallel operations. This study includes three projects, each showcasing different concurrency techniques in Node.js.

## Image Resizer

### Building Images

The images are processed from a `Camera` directory that is not checked into the repo.
This way, raw data is not exposed publicly. you can uplodad multiple photos in `Camera` directory.

### How to run

```bash
# install dependencies
$ npm ci

# start local webserver and build images
$ npm run build:images

# Measure Execution Time in Windows
$ Measure-Command {npm run build:images}
```


## PARALLEL HASHING

### How to run

- install node js https://nodejs.org/en/download/ if you don't have any

```bash
# build node_modules
$ npm install
or
$ npm install create-node-module
or
$ yarn

# run serial code
$ node hashing-serial.js

# run parallel code 
$ node hashing-parallel.js
```

- execution time is written in the terminal


## Matrix Multiplication 

### How to run

- install node js https://nodejs.org/en/download/ if you don't have any

```bash
# build node_modules
$ npm install
or
$ npm install create-node-module
or
$ yarn

# run serial code
$ node matrix-serial.js

# run parallel code 
$ node matrix-parallel.js
```

- execution time is written in the terminal

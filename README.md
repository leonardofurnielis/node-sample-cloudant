# node-sample-cloudant

![workflow](https://github.com/leonardofurnielis/node-sample-cloudant/actions/workflows/test-coverage.yml/badge.svg)
[![codecov](https://codecov.io/gh/leonardofurnielis/node-sample-cloudant/branch/master/graph/badge.svg?token=5LTEJCG91W)](https://codecov.io/gh/leonardofurnielis/node-sample-cloudant)

## Table of Contents

- Developing locally
  - [Native runtime](#native runtime)
  - [Docker](#docker)

## Native runtime 

To run this code in your computer execute the following commands into project root directory

```bash
$ npm install
$ npm start
```

## Docker

To run this code using Docker container execute the following commands into project root directory

```bash
$ docker build -t node-sample-cloudant .
$ docker run -p 8080:3000 -d node-sample-cloudant
```

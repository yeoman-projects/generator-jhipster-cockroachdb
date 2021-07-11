# generator-jhipster-cockroachdb
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> JHipster module, Jhipster CockroachDB

![Logo][cockroachdb-hipster-image]

# Introduction

This is a [JHipster](http://jhipster.github.io/) module, that is meant to be used in a JHipster application.

# Prerequisites

As this is a [JHipster](http://jhipster.github.io/) module, we expect you have JHipster and its related tools already installed:

- [Installing JHipster](https://jhipster.github.io/installation.html)

# Installation

## With Yarn

To install this module:

```bash
yarn global add generator-jhipster-cockroachdb
```

To update this module:

```bash
yarn global upgrade generator-jhipster-cockroachdb
```

## With NPM

To install this module:

```bash
npm install -g generator-jhipster-cockroachdb
```

To update this module:

```bash
npm update -g generator-jhipster-cockroachdb
```

# Usage

```bash
yo jhipster-cockroachdb
```

## Using Docker

Download the Dockerfile:

```bash
mkdir docker
cd docker
wget https://github.com/yeoman-projects/generator-jhipster-cockroachdb/raw/master/Dockerfile
```

Build the Docker images:

```bash
docker build -t generator-jhipster-cockroachdb:latest .
```

Make a folder where you want to generate the Service:

```bash
mkdir service
cd service
```

Run the generator from image to generate service:

```bash
docker run -it --rm -v $PWD:/home/jhipster/app generator-jhipster-cockroachdb
```

Run and attach interactive shell to the generator docker container to work from inside the running container:

```bash
docker run -it --rm -v $PWD:/home/jhipster/app generator-jhipster-cockroachdb /bin/bash
```

# License

Apache-2.0 © [Clément Tamisier](https://github.com/ctamisier)


[npm-image]: https://img.shields.io/npm/v/generator-jhipster-cockroachdb.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-cockroachdb
[travis-image]: https://travis-ci.org/ctamisier/generator-jhipster-cockroachdb.svg?branch=master
[travis-url]: https://travis-ci.org/ctamisier/generator-jhipster-cockroachdb
[daviddm-image]: https://david-dm.org/ctamisier/generator-jhipster-cockroachdb.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/ctamisier/generator-jhipster-cockroachdb
[cockroachdb-hipster-image]:https://raw.githubusercontent.com/ctamisier/generator-jhipster-cockroachdb/master/logo-cockroachdb-hipster.png
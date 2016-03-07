feedly2opml
===========

A NPM module that exports a Feedly account to OPML 2.0.

As opposed as [Feedly OPML export tool](http://feedly.com/i/opml), it allows to
save tags.

[![Latest Stable Version](https://img.shields.io/npm/v/feedly2opml.svg)](https://www.npmjs.com/package/feedly2opml)
[![License](https://img.shields.io/npm/l/feedly2opml.svg)](https://www.npmjs.com/package/feedly2opml)
[![Build Status](https://img.shields.io/travis/amercier/node-feedly2opml/master.svg)](https://travis-ci.org/amercier/node-feedly2opml)

[![Dependency Status](http://img.shields.io/gemnasium/amercier/node-feedly2opml.svg)](https://gemnasium.com/amercier/node-feedly2opml)
[![NPM Downloads](https://img.shields.io/npm/dm/feedly2opml.svg)](https://www.npmjs.com/package/feedly2opml)
[![Test Coverage](https://img.shields.io/codecov/c/github/amercier/node-feedly2opml/master.svg)](https://codecov.io/github/amercier/node-feedly2opml?branch=master)
[![API Documentation](https://doc.esdoc.org/github.com/amercier/node-feedly2opml/badge.svg)](https://doc.esdoc.org/github.com/amercier/node-feedly2opml/)
[![Code Climate](https://img.shields.io/codeclimate/github/amercier/node-feedly2opml.svg)](https://codeclimate.com/github/amercier/node-feedly2opml)

Command-line interface
----------------------

### Installation

    npm install -g feedly2opml

### Usage

    feedly2opml -t <Feedly authentication token>
    # or use FEEDLY_AUTH_TOKEN env variable

Programmatic API
----------------

### Package installation

    npm install --save feedly2opml

#### Usage (ES5)

```js
var feedlyToOpml = require('feedly2opml').default;
var xml = feedlyToOpml(token);
```

#### Usage (ES2015+)

```js
import feedlyToOpml from 'feedly2opml';
const xml = feedly2Opml(token);
```
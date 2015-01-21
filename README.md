#[Episode 4 – Writing Middleware in Koajs](http://knowthen.com/episode-4-writing-middleware-in-koajs/)

### This code is created from [this screencast](http://knowthen.com/episode-4-writing-middleware-in-koajs/) from [knowthen.com](http://knowthen.com/ "KnowThen")

In this episode we’ll learn to write middleware, the foundational building block for [Koajs](http://koajs.com/ "Koajs") and [Expressjs](http://expressjs.com/ "Expressjs").

Of course the **best way** to **learn** programming is to **make stuff**,
so we’ll build a “_Session Management Middleware_”.

We’ll start off writing a few tests using [mocha](http://mochajs.org/ "mocha") and [supertest](https://github.com/tj/supertest "supertest") , then we’ll implement our Session Management Middleware **first** storing the session information **in memory**.

Next we’ll take a quick look at [RethinkDB](http://rethinkdb.com/ "RethinkDB") , a _cool_ new open source _database_, that we’ll use to store our session information.

Lastly we’ll **refactor** our middleware to save our session information using **RethinkDB**.

If you are unfamiliar with middleware or Koajs, please checkout my quick start [screencast](http://knowthen.com/episode-3-koajs-quickstart-guide/ "Screencast") on those topics:

To run this demo, enter:

```bash
$ npm install
```

_Make sure RethinkDB is running_

```bash
$ npm test
```

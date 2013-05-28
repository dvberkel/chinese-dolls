Node Application
================

This is a node application that can be used in the Chinese Dolls proof
of concept

Setup
-----

This is a [node][] application.

### Dependencies

We use [npm][], which comes installed with node to manage our
dependencies. Install the dependencies for this project by running the
following command.

```shell
npm install
```

### Tasks

We use [grunt][] to automate various tasks for the project. It relies
on a globally installed `grunt-cli`. To install it run

```shell
npm install -g grunt-cli
```

After installing the `grunt-cli` (and downloading) the dependencies
one can run `grunt` with the following command

```shell
grunt
```

This runs the default task. To run a differet task provide it as an
argument to `grunt`. E.g.

```shell
grunt jasmine
```

[node]: http://nodejs.org/
[npm]: https://npmjs.org/
[grunt]: http://gruntjs.com/
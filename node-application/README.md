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

### Tests

There are several ways to run test for this project. All ways use
[jasmine][], a [Behaviour Driven Design][BDD] test framwork.

#### PhantomJS

[phantomJS][] is a headless browser that is capable of rendering html,
css and executing javascript. It can be run with once with the
following command

```shell
grunt jasmine
```

You could also tell node to watch for test file changes, executing the
jasmine task when it is notified of changes. Use the following command

```shell
grunt watch:lib_test
```

#### Karma

According to the [karma][] website

> The main goal for Karma is to bring a productive testing environment
> to developers. An environment, where they don't have to set up many
> things and rather just write the code and get an instant
> feedback. Because getting a quick feedback is what makes you
> productive and creative.

It's power can be harnessed via

```shell
grunt karma
```

Karma allows other devices to connect to the test environment.

[node]: http://nodejs.org/
[npm]: https://npmjs.org/
[grunt]: http://gruntjs.com/
[jasmine]: http://pivotal.github.io/jasmine/
[BDD]: http://en.wikipedia.org/wiki/Behavior-driven_development
[phantomJS]: http://phantomjs.org/
[karma]: http://karma-runner.github.io/0.8/index.html
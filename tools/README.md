These are some little tools for working on Flight mixins. Use them symlinked into a directory where the children are the mixins of the toolbox:

```
.
├── flight-with-batch
├── flight-with-render
├── flight-with-resources
├── flight-with-state
├── make -> ../flight-toolbox/tools/make
├── new -> ../flight-toolbox/tools/new
├── test -> ../flight-toolbox/tools/test
└── watch-test -> ../flight-toolbox/tools/watch-test
```

### new

```
$ ./new with-some-cool-thing
```

Create a new mixin

- Creates a directory
- Adds a `.bowerrc`
- Initialises with `yo flight-package`
- Turns off jasmine-flight
- Initialises npm

### make

```
$ ./make with-some-cool-thing
```

Get mixin set up for local development

- npm & bower installs
- bower link (for local dev)

### test

```
$ ./test with-some-cool-thing
```

Run the tests of the mixin

### watch-test

```
$ ./watch-test with-some-cool-thing
```

Run the `watch-test` script of the mixin

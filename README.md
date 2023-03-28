# Hello World

This is a simple Hello Wolrd application

## Building process

Instantiate the build system with help of `autoreconf`

```
$ autoreconf --install
```

Configure build environemnt

```
$ ./configure
```

Build a target

```
$ make
```

## Distribution

Generate distribution package using:

```
$ make distcheck
```


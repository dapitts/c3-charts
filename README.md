# c3-charts

## Install

After cloning the repo, several Node.js modules will need to be installed in the `/src` directory using the `npm install` command:

```
$ npm install connect serve-static
```

## Run

Next, start the server:

```
$ node chart-server.js
```

## View

In your favorite browser, type the following URL in the address bar:

```
127.0.0.1:8080
```

Or, you can serve up a specific c3 chart:

```
127.0.0.1:8080/c3-multi-line.html
```

## TBD

Need to come up with a fix where missing values in the CSV are parsed as zero. As a work around, the values must be something that will be parsed as NaN, i.e. string values `null`, `nil`,  or `empty`.

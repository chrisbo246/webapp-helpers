# Webapp helpers [![Build Status](https://secure.travis-ci.org/chrisbo246/webapp-helpers.svg?branch=master)](http://travis-ci.org/chrisbo246/webapp-helpers) [![Coverage Status](https://coveralls.io/repos/chrisbo246/webapp-helpers/badge.png?branch=master)](https://coveralls.io/r/chrisbo246/webapp-helpers?branch=master)

Web application common JS and CSS helpers.

## Features


## Getting Started

### Installing

Download with Bower.

```
bower install chrisbo246/webapp-helpers
```

Insert the **webapp-helpers.js** in your index.html

```
<script src="/bower_components/webapp-helpers/dist/scripts/webapp-helpers.js"></script>
```

Edit your main.scss and insert **webapp-helpers.scss** just after Bootstrap.

```
@import "app/styles/webapp-helpers";
```

## Development

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Install [Node](https://nodejs.org/en/download/) on your local machine then download dependencies.

```
npm install -g gulp-cli bower yo generator-webapp
```

### Installing

Install NPM and Bower packages.

```
npm install
bower install
```

### Testing

```
gulp serve
```

[http://localhost:9000/](http://localhost:9000/)

## Deployment

```
gulp build
```

Then upload the **dist** directory content to your web server.

<!--

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

-->


## Bugs

Please use the [GitHub issue tracker](https://github.com/chrisbo246/webapp-helpers/issues) for all bugs and feature requests. Before creating a new issue, do a quick search to see if the problem has been reported already.

## Author

[chrisbo246](https://github.com/chrisbo246)

See also the list of [contributors](https://github.com/chrisbo246/webapp-helpers/contributors) who participated in this project.

## License

This project is licensed under the MIT License. See the [opensource.org](https://opensource.org/licenses/MIT) website for details.

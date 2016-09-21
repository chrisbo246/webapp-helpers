# Webapp helpers

Common JS and CSS for web applications.

## Features

- Load Google fonts asynchronously (+ Material design icons).
- Try to define user language and populate the associated input.
- Smooth scroll when user click internal links.
- Hide URL hash when user click internal links.
- Save input values to a data attribute for live reset.
- Make form fields persistent (require Basil.js).
- Watch the reset button to clear cookies / local storage.
- Add a .disabled class to unsupported field types.
- Add a simple parallax function.
- Load the Google Adsense library then add a class allowing to unhide ad containers.
- Show a lot of debug information in console including some  plugins (Garlic, Parsley, Mixitup, i18next, jQuery UI sortable).

## Install

Download with Bower.

```
bower install chrisbo246/webapp-helpers
```

Load **webapp-helpers.js** with a script tag in your main .html.

```
<script src="/bower_components/webapp-helpers/dist/scripts/webapp-helpers.js"></script>
```

Edit your main.scss and import **webapp-helpers.scss**.

```
@import "app/styles/webapp-helpers";
```

## Usage

You can eventually customize the default settings to change some selectors or disable some functionalities.

<!--

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

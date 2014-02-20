*This repository is a mirror of the [component](http://component.io) module [segmentio/on-body](http://github.com/segmentio/on-body). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-on-body`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# on-body

  Callback when `document.body` exists.

## Installation

    $ component install segmentio/on-body

## API

### onBody(Function)

  Will call your function with `fn(document.body)` when the `<body>` element has been created. This way you can easily append things to the body even if the Javascript was added in the `<head>`.

## License

  MIT

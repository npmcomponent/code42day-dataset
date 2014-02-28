*This repository is a mirror of the [component](http://component.io) module [code42day/dataset](http://github.com/code42day/dataset). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/code42day-dataset`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# dataset

  Shim for DOM dataset

## Installation

    $ component install code42day/dataset

## API

  To set `data-xxx` attribute on `node` to 5:

  	dataset(node, 'xxx', 5);

  To retrieve `data-xxx` attribute value:

    dataset(node, 'xxx');

  To remove `data-xxx` attribute:

    dataset(node).del('xxx');

  You can chain your `sets`:

  	dataset(node)
  		.set('xxx', 5)
  		.set('foo', 'bongo');

## License

  MIT

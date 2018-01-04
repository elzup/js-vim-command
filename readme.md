# vim-command-parser [![Build Status](https://travis-ci.org/elzup/vim-command-parser.svg?branch=master)](https://travis-ci.org/elzup/vim-command-parser)

> parse vim key sequence.


## Install

```
$ npm install vim-command-parser
```


## Usage

```js
const vimCommandParser = require('vim-command-parser');

vimCommandParser('unicorns');
//=> 'unicorns & rainbows'
```


## API

### vimCommandParser(input, [options])

#### input

Type: `string`

Lorem ipsum.

#### options

##### foo

Type: `boolean`<br>
Default: `false`

Lorem ipsum.


## CLI

```
$ npm install --global vim-command-parser
```

```
$ vim-command-parser --help

  Usage
    vim-command-parser [input]

  Options
    --foo  Lorem ipsum [Default: false]

  Examples
    $ vim-command-parser
    unicorns & rainbows
    $ vim-command-parser ponies
    ponies & rainbows
```


## License

MIT © [elzup](http://elzup.com)

# blink1-bitcoin

> A tiny tool to connect your blink(1) device with Bitcoin live trades using websockets.

blink1-bitcoin connects you to the live trading API of your favorite Bitcoin exchange (currently Bitstamp, see `Todo`) and uses your blink(1) device to flash on every occuring trade with a corresponding light. The first incoming trade sets the reference values.

## Install

Most OS need you to be root (e.g. using `sudo`) to install a global npm package

```sh
$ git clone https://github.com/thbaumbach/blink1-bitcoin && cd blink1-bitcoin
$ npm -g install
```

blink1-bitcoin depends on [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/).

## Usage

Hook up your blink(1) device and run:

```sh
$ blink1-bitcoin
```

## Todo

* transfer code into library
* options to connect to: Bitfinex, Kraken, BTC-e, OKCoin, Houbi...

## License

Copyright (c) 2015 Thomas Baumbach <tom@xolo.pw>

Licensed under the MIT License

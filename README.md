# blink1-bitcoin

> A tiny tool to connect your blink(1) device with Bitcoin live trades using websockets.

blink1-bitcoin connects you to the live trading API of your favorite Bitcoin exchange (currently Bitstamp and OKCoin only, see `Todo`) and uses your blink(1) device to flash on every occuring trade with a corresponding light. The first incoming trade sets the reference values.

## Install

Most OS need you to be root (e.g. using `sudo`) to install a global npm package:

```sh
$ npm -g install blink1-bitcoin
```

blink1-bitcoin depends on [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/). Tested with `node v4.2.0` and `npm v2.14.7`.

## Usage

Hook up your blink(1) device and run:

```sh
$ blink1-bitcoin <exchange>
```

Currently supported exchanges:
* `bitstamp`: showing BTC-USD trades on Bitstamp
* `okcoin`: showing BTC-CNY trades on OKCoin (*connection seems to be a bit sluggish sometimes*)

`Bitfinex` and `Huobi` are coming soon.

## Todo

* transfer code into library!!
* options to connect to: Bitfinex, Kraken, BTC-e, Huobi...

## Support

Found a bug? Open an issue [here](https://github.com/thbaumbach/blink1-bitcoin/issues) on Github.

Wanna help? Submit a pull request or contact me.

Wanna tip me a beer? Use [Bitcoin](bitcoin:14pSD9AmuNhLDbGRXehxbhwzRSRrkpiAKg): 14pSD9AmuNhLDbGRXehxbhwzRSRrkpiAKg

## License

Copyright (c) 2015 Thomas Baumbach <tom@xolo.pw>

Licensed under the MIT License

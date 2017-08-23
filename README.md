hlsify
======

Simply command line utility to convert an input video into an extended multimedia playlist (M3U) with MPEG transport segments.
This module assumes zero defaults for input and output options. It gives
you the flexability of providing input options, but output options are
not yet supported.

## Installation

```sh
$ [sudo] npm install -g hlsify
```

## Usage

```sh
$ hlsify input.mp4 <...ffmpeg input options> output.mp3
```

See [https://github.com/fluent-ffmpeg/node-fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) for more
input options.

## License

MIT

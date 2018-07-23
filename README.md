# parcel-plugin-inliner

A Parcel plugin to inline CSS and JS code in your HTML file.

This plugin uses the [inliner](https://github.com/remy/inliner) utility to inline your entry point.

## Usage

Just install the plugin as a dependency using yarn or npm and build normally with Parcel. There are no configuration options.

## Installation

```
yarn add parcel-plugin-inliner
```

or

```
npm install parcel-plugin-inliner
```

## Caveats

This library only inlines files that are referenced directly in your entry point HTML file. It doesn't inline dependencies referenced inside JS and CSS files. It also doesn't inline files loaded asyncronously using Javascript. It doesn't affect code-splitting.

## License

```

MIT License

Copyright (c) 2018 Silvio Henrique Ferreira

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

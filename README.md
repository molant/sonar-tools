# sonar-tools

[![Build Status](https://travis-ci.org/sonarwhal/sonar-tools.svg?branch=master)](https://travis-ci.org/sonarwhal/sonar-tools) [![Greenkeeper badge](https://badges.greenkeeper.io/sonarwhal/sonar-tools.svg)](https://greenkeeper.io/)

This is a collection of small scripts that use `sonar` that could be
reused in different scenarios.

* [`crawler`][crawler] can be used to scan a list of websites stored in a text file
  where each line is a URL.

## Building the project

1. Clone this project locally.
1. `npm install` all the dependencies.
1. `npm run build` to compile the source code.

The output files will be in the `dist` folder.

## Code of Conduct

This project adheres to the JS Foundation's [code of
conduct](https://js.foundation/community/code-of-conduct).
By participating in this project you agree to abide by its terms.

## License

The code is available under the [Apache 2.0 license](LICENSE.txt).

[crawler]: ./scripts/crawler/readme.md

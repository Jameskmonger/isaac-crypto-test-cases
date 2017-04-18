# isaac-crypto-test-cases

Test cases for an [ISAAC pseudorandom number generator](http://burtleburtle.net/bob/rand/isaacafa.html).

Created for [isaac-crypto](http://github.com/jameskmonger/isaac-crypto).

## Installation

    $ npm install isaac-crypto-test-cases --save-dev

The test cases should be installed as a developer dependency, because they will be used as part of your development process rather than being in your production code.

## Usage

    let cases = require("isaac-crypto-test-cases");

`cases` will contain an array of objects with the following properties:

- `seed`: An array containing a seed for the generator
- `results`: The first 512 results from the generator when given the seed

## License

`isaac-crypto-test-cases` is licensed under The MIT License. To see the full license text included with the project, visit the [LICENSE file](/LICENSE).

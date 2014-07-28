# Gherkin 3

[![Build Status](https://travis-ci.org/cucumber/gherkin3.png)](https://travis-ci.org/cucumber/gherkin3)

Gherkin 3 is a cross-platform parser for the Gherkin language,
used by Cucumber to parse `.feature` files.

## Building Gherkin 3

Gherkin 3 uses [berp](https://github.com/gasparnagy/berp) to generate parsers
based on the Gherkin grammar defined in `gherkin.berp`.

You need .Net or Mono installed to generate the grammar.

### C# ###

#### Windows

Open `Gherkin.CSharp.sln` from the `csharp` directory in Visual Studio 2013 and build

or

Run `msbuild` from the `csharp` directory.

#### OS X/Linux

Run `make` from the `csharp` directory.

### Ruby

Run `rake` from the `ruby` directory.

### Java

TODO

### JavaScript

TODO

## Make a release

TODO

# TODO

Try to implement the lexer using state functions as described in [Rob Pike’s talk on writing the text/template lexer](https://www.youtube.com/watch?v=HxaD_trXwRE)

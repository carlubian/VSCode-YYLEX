# YYLEX Extension

Provides support for yylex files within VS Code.

## Features

* Syntax coloring and token name highlighting.
* Automatic brace insertion

## How to download

There are two ways of using this extension:

* Import the .vsix file directly
* Download from the Visual Studio Marketplace, [here](https://marketplace.visualstudio.com/items?itemName=carlubian.yylex)

## Known Issues

When writing a '%{' brace, a single '}' will be inserted, instead of the corresponding '%}'.

## Release Notes

### 1.1.0

Comments (both line and block) inside an action or inline code will be properly colored as such.

Fixed an edge case where the end of a comment block wouldn't be found.

### 1.0.1

Action blocks do not have to end in a line break anymore.

Comments now need a space between the slash and the first character.

### 1.0.0

Initial release.
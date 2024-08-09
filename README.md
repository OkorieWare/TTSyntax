# Text Template Syntax

Detect and switch VSCode syntax to the underlying language of a TT (Text Template) document.

No more error squiggly lines.

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OkorieWare/TTSyntax)](https://github.com/OkorieWare/TTSyntax/releases/latest)

[![Homepage: OkorieWare Software House](https://img.shields.io/badge/homepage-OkorieWare%20Software%20House-orange)](https://github.com/OkorieWare/TTSyntax/)

## Release Notes

Install the extension in VSCode.

Then, when you open a .tt document, it will switch VSCode syntax to the "output extension" format specified in the document.

## Requirements

VSCode (Visual Studio Code)

## Known Issues

TODO: Low priority

- In order to achieve the desired effect, TTSyntax also suspends validation for (JavaScript, SCSS, JSON) .tt documents.

- VSCode only activates the extension after the first .tt document is loaded. For the time being, when you initially open a VSCode window, you will need to re-open your .tt document, or toggle between another tab and your .tt document tab.

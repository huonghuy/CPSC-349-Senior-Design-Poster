# Gemini Unofficial Bridgeport Version [![Build Status](https://github.com/anishathalye/gemini/workflows/CI/badge.svg)](https://github.com/anishathalye/gemini/actions?query=workflow%3ACI)

This is an unofficial adaptation of the modern LaTeX [beamerposter] theme, Gemini, tailored for the University of Bridgeport.

For a general-purpose beamer presentation theme, see [Auriga].

## UB Customizations

* Integrated University of Bridgeport branding guidelines
* Example templates featuring the UB color scheme and logo placement
* Additional font support to match UB's branding (where applicable)

## Dependencies

* A TeX installation that includes [LuaTeX]
* LaTeX package dependencies including beamerposter (typically part of your TeX installation, available on [CTAN] if not)
* [Raleway] and [Lato] fonts, both available under Open Font License, and any additional fonts recommended by the University's branding guidelines

## Usage

1. Copy or clone the files from this repository

1. Configure `poster.tex` with your desired paper size, column layout, and scale adjustments as needed

1. Customize `beamercolorthemegemini.sty` by copying it and modifying the `\usecolortheme` line in `poster.tex` to theme your poster to UB's branding (optional but recommended for university-related presentations)

## FAQ

For common questions, such as adding an institution logo or customizing the color theme further, consult the [FAQ] in the Wiki.

## Themes

The UB version includes several color themes suitable for various types of presentations:

* `gemini` (default)
* `UBridgeport` (customized for University of Bridgeport branding)

You're encouraged to create your own color theme or use the `UBridgeport` theme for presentations associated with the University.

## Design Goals

* **Minimal**: Focuses on readability and simplicity.
* **Batteries Included**: Ready to use with minimal setup.
* **Easy Theming**: Simplified process to create or modify themes.

## Contributing

Contributions such as bug reports, new themes, and enhancements are welcome! Design is subjective, so early feedback through issues or pull requests is encouraged.

## License

Copyright (c) 2018-2024 Huy Huong. This unofficial UB version is released under the MIT License. See [LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ

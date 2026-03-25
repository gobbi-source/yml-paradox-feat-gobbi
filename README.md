# yml-paradox README

**This widget, only the highlighting effects in YML files. It isn't theme: does NOT interfere with other languages or with your preferred theme.**

[github](https://github.com/gobbi-source/yml-paradox-feat-gobbi)

## Features


![feature highlighting](https://i.imgur.com/MTTaKgZ.png)

This extension provides advanced syntax highlighting for .yml localization files used in Paradox games (e.g., Stellaris, Hearts of Iron, Crusader Kings), with full support for their unique formatting conventions.

**Explain Features**

**Variable Recognition**: Highlights variables enclosed in $...$ and [This.Get...] formats, following Paradox scripting standards.

**Color-Coded Tokens**: Applies dedicated colors in lang configuration to Stellaris-style color codes (e.g., §R, §Y, §G) without affecting the global theme.

**Scope-Specific Styling**: Uses custom TextMate scopes to isolate styling to .yml files only, ensuring no interference with other languages or themes.

**Semantic Token Support**: Integrates semantic token definitions for advanced customization and compatibility with VS Code’s semantic highlighting engine.

**Theme-Agnostic Design**: Works independently of the user's active theme by embedding scoped color rules directly into the extension.
Only colors in § are customize rest get by your personal theme.

**Error report**:Automatically reports any errors, to allow you to be more efficient

![auto error](https://i.imgur.com/905IDiX.png)

### Why It Matters
Paradox localization files rely on embedded scripting, color codes, and dynamic variables that standard YAML highlighting cannot handle. This extension bridges that gap, enabling modders and translators to work with clarity, precision, and visual feedback tailored to the game's syntax.

## Requirements

No one: is standalone, but maybe you need set default yml.

## Extension Settings

Nope.

## Known Issues

For paradox standard best if set json configuration for yamlp "files.encoding": "utf8bom"

## Release Notes

### 1.0.0

Work it.

### 1.0.1

Fix the propagation of the syntax type across multiple lines.

Fix identifier with number that was red (example test:0 , 0 was red now is normal text markup)

### 1.0.2

Add auto closing pairs

## Who is I

I'am developper with 1 child and few work, so an donation is ever appreciate. [Paypal](https://paypal.me/ChristianGobbi)
**Enjoy!**

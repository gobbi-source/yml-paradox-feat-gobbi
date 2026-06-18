# Change Log

All notable changes to the "yml-paradox" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.0.0 Release]

- Relase work it.

### Feature

**Variable Recognition**: Highlights variables enclosed in $...$ and [This.Get...] formats, following Paradox scripting standards.

**Color-Coded Tokens**: Applies dedicated colors in lang configuration to Stellaris-style color codes (e.g., §R, §Y, §G) without affecting the global theme.

**Scope-Specific Styling**: Uses custom TextMate scopes to isolate styling to .yml files only, ensuring no interference with other languages or themes.

**Semantic Token Support**: Integrates semantic token definitions for advanced customization and compatibility with VS Code’s semantic highlighting engine.

**Theme-Agnostic Design**: Works independently of the user's active theme by embedding scoped color rules directly into the extension.
Only colors in § are customize rest get by your personal theme.

**Error report**:Automatically reports any errors, to allow you to be more efficient

## [1.0.1] 07/03/2026

### Fix
Fix the propagation of the syntax type across multiple lines.

Fix identifier with number that was red (example test:0 , 0 was red now is normal text markup)

## [1.0.2] 25/03/2026

### Added

auto closing pairs:
["§", "§!"],
["\"", "\""],
["$", "$"],
["[", "]"],
["£", "£"]


Redme.md

### Removed

### Fixed
- Fix the propagation of the syntax type across multiple lines: when the type is either incorrect or intentionally truncated, the propagation now stops at the end of the line.
- Fix identifier loc test:0 "" now 0 is valid: The new pattern now only accepts a single numeric digit (0–9) immediately after the colon.

## [1.0.3] 18/06/2026

### Fixed
Fixed blockComment now multiline with #
Fixed autoClosingPairs



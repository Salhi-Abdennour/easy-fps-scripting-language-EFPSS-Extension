# easy fps scripting language (EFPSS) Extension

## Overview
The easy fps scripting language (EFPSS) is a domain-specific language (DSL) designed for creating scripts in first-person shooter (FPS) games. This extension provides syntax highlighting and language support for the EFPSS language in various code editors and IDEs.

## Features
- Syntax highlighting for EFPSS language constructs
- Code folding and indentation
- Autocomplete suggestions
- Quick access to language documentation

## Supported Syntax
The EFPSS language supports the following syntax elements:

### Keywords
- `on`, `off`, `if`, `else`, `end`, `return`, `quickreturn`, `keeptrigger`, `show`, `text`, `hide`, `timeout`, `auto`, `call`, `pause`, `halt`, `vn`, `preload`, `font`, `bg`, `button`, `label`, `bind`

### Comments
- `//` for single-line comments

### Strings
- Double-quoted strings with support for escape characters

### Global and Map Variables
- `global` and `map` for accessing global and map-specific variables

### Local Variables
- Variables starting with a letter and containing letters and numbers

### Procedure Declaration
- `procedure` keyword for defining procedures
- Procedure names starting with a letter and containing letters and numbers

### Pointer
- `$` for accessing pointers

### Procedure Calling
- `call` keyword for calling procedures

### Numbers
- Integer and floating-point numbers with optional exponents

### Operators
- `++`, `--`, `*=`, `-=`, `/=`, `%=`, `+=`, `=`

### Commands
- `map`, `player`, `entity`, `door`, `light`, `status`, `give`, `take`, `cursor`, `shader`, `game`, `gravity`, `weapon`, `hud`, `sound`, `play`, `stop`, `move`, `front`, `back`, `image`, `key`, `holster`, `hp`, `maxhp`, `armour`, `maxarmour`, `mag`, `heldweapon`, `position`

### Subcommands
- `start`, `next`, `goto`, `heal`, `hurt`, `teleport`, `move`, `rotation`, `retro`, `turn`, `steps`, `speed`, `sethp`, `setmaxhp`, `givearmour`, `takearmour`, `setarmour`, `setmaxarmour`, `cancrouch`, `canjump`, `height`, `zoom`, `camspeed`, `check`, `delete`, `me`, `spawnat`, `spawnatpos`, `open`, `close`, `lock`, `unlock`, `create`, `status`, `weapon`, `ammo`, `set`, `save`, `load`, `maxammo`, `magsize`, `damage`, `firerate`, `bullets`, `reloadspeed`, `projectilespeed`, `explosion`, `recoil`, `spread`, `recoilrecovery`, `range`, `RANDOM`, `sound`, `music`, `video`, `sounds`

## Usage
To use the EFPSS extension, simply install it in your preferred code editor or IDE. The extension will automatically provide syntax highlighting, code folding, and other language-specific features when working with EFPSS files.

## Contributing
If you find any issues or have suggestions for improving the EFPSS extension, feel free to create a new issue or submit a pull request on the [project repository](https://github.com/nikkommek/efpss-vscode-extension).
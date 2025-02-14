# PHP Parameter Hint for Visual Studio Code


### Note

_This repository is a fork of the original extension [mrchetan/phpstorm-parameter-hints-in-vscode](https://github.com/mrchetan/phpstorm-parameter-hints-in-vscode)_  

[![VS Marketplace Version](https://img.shields.io/vscode-marketplace/v/satiromarra.phpstorm-parameter-hints-for-vscode.svg?label=Version&color=green)](https://marketplace.visualstudio.com/items?itemName=satiromarra.phpstorm-parameter-hints-for-vscode)

![PhpStorm Parameter Hints in VScode Screenshot](Screenshot.png)

Inserts parameter hints(type, name or both) into function calls to easily understand the parameter role.
Compatible with php8

# Installation

- Open VS Code and click on Extensions Icon in the Activity Bar.
- Type **satiromarra.phpstorm-parameter-hints-for-vscode**
- Install the Extension Pack.
---

## Settings

| Name                                      | Description                                                                                                                                           | Default  |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| `phpParameterHint.enabled`                | Enable PHP Parameter Hint                                                                                                                             | true     |
| `phpParameterHint.margin`                 | Hints styling of margin CSS property                                                                                                                  | 2        |
| `phpParameterHint.verticalPadding`        | Top and bottom padding of the hints(px)                                                                                                               | 1        |
| `phpParameterHint.horizontalPadding`      | Right and left padding of the hints(px)                                                                                                               | 4        |
| `phpParameterHint.fontWeight`             | Hints styling of font-weight CSS property                                                                                                             | "400"    |
| `phpParameterHint.borderRadius`           | Hints styling of border-radius CSS property in px                                                                                                     | 5        |
| `phpParameterHint.opacity`                | Hints styling of opacity CSS property                                                                                                                 | 0.4      |
| `phpParameterHint.fontStyle`              | Hints styling of font-style CSS property                                                                                                              | "italic" |
| `phpParameterHint.fontSize`               | Hints styling of font size CSS property                                                                                                               | 12       |
| `phpParameterHint.onSave`                 | Create parameter hints on document save                                                                                                               | true     |
| `phpParameterHint.saveDelay`              | Delay in ms for on document save run                                                                                                                  | 250      |
| `phpParameterHint.onChange`               | Create parameter hints on document change                                                                                                             | false    |
| `phpParameterHint.changeDelay`            | Delay in ms for on document change run                                                                                                                | 100      |
| `phpParameterHint.textEditorChangeDelay`  | Delay in ms for on active text editor change                                                                                                          | 250      |
| `phpParameterHint.php7`                   | True if php version is 7.0+, false otherwise                                                                                                          | true     |
| `phpParameterHint.collapseHintsWhenEqual` | Collapse hint when variable name is the same as parameter name, keep the hint if the argument is passed by reference or if the splat operator is used | false    |
| `phpParameterHint.collapseTypeWhenEqual`  | Collapse type when it is equal to the variable name                                                                                                   | false    |
| `phpParameterHint.showFullType`           | Show full type, including namespaces instead of the short name                                                                                        | false    |
| `phpParameterHint.hintOnlyLiterals`       | Show hints only for literals                                                                                                                          | false    |
| `phpParameterHint.hintOnlyLine`           | Show hints only for current line/selection                                                                                                            | false    |
| `phpParameterHint.hintOnlyVisibleRanges`  | Show hints only for visible ranges                                                                                                                    | false    |
| `phpParameterHint.hintTypeName`           | Hint only name(0 - default) / Hint type and name(1) / Hint type(2)                                                                                    | 0        |
| `phpParameterHint.showDollarSign`         | Show dollar sign in front of parameter name                                                                                                           | false    |

## Commands

| Name                                   | Description                                                 | SHORTCUT                        |
| -------------------------------------- | ----------------------------------------------------------- | ------------------------------- |
| `phpParameterHint.toggle`              | Hide / Show Hints                                           | Key: CTRL + K H, Mac: CMD + K H |
| `phpParameterHint.toggleOnChange`      | Hide / Show Hints on text change                            | Key: CTRL + K O, Mac: CMD + K O |
| `phpParameterHint.toggleOnSave`        | Hide / Show Hints on document save                          | Key: CTRL + K S, Mac: CMD + K S |
| `phpParameterHint.toggleLiterals`      | Hide / Show Hints only for literals                         | Key: CTRL + K L, Mac: CMD + K L |
| `phpParameterHint.toggleLine`          | Hide / Show Hints only for current line/selection           | Key: CTRL + K I, Mac: CMD + K I |
| `phpParameterHint.toggleCollapse`      | Hide / Show Hints when variable name matches parameter name | Key: CTRL + K C, Mac: CMD + K C |
| `phpParameterHint.toggleTypeName`      | Hint name(default), type and name or only type              | Key: CTRL + K T, Mac: CMD + K T |
| `phpParameterHint.toggleCollapseType`  | Toggle collapsing type and name when they are equal         | Key: CTRL + K Y, Mac: CMD + K Y |
| `phpParameterHint.toggleFullType`      | Hide / Show full type name(namespaces including)            | Key: CTRL + K U, Mac: CMD + K U |
| `phpParameterHint.toggleVisibleRanges` | Hide / Show Hints only in visible ranges                    | Key: CTRL + K R, Mac: CMD + K R |
| `phpParameterHint.toggleDollarSign`    | Hide / Show dollar sign in front of parameter name          | Key: CTRL + K D, Mac: CMD + K D |

## Colors

You can change the default foreground and background colors in the `workbench.colorCustomizations` property in user settings.

| Name                              | Description                                 |
| --------------------------------- | ------------------------------------------- |
| `phpParameterHint.hintForeground` | Specifies the foreground color for the hint |
| `phpParameterHint.hintBackground` | Specifies the background color for the hint |

## Support and contribute [[&uarr;](#table-of-contents)]
If you like the extension, you can support the project
### Buy Me a Coffee
[![Buy Me A Coffee](https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png)](https://www.buymeacoffee.com/satiromarra)
### PayPal
[![PayPal Me](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/satiromarra)

# px to em ( FORKED FROM px to rem)

This is an extension for Visual Studio Code that allows you to convert px to em, and vice versa.

## Usage

### Keybindings
* `Alt+Z` Px to em, and em to px. Converts selected text from px to em, and em to px.

![](./imgs/alt_z.gif)
### Commands
* Px to em, and em to px. Converts selected text from px to em, and em to px.
* Px to em. Converts selected text from px to em
* em to px. Converts selected text from em to px

## Extension Settings

This extension contributes the following settings:

* `px-to-em.px-per-em`: number of pixels per em. Default is `16px`.
* `px-to-em.number-of-decimals-digits`: maximum number of decimals digits a px or em can have
* `px-to-em.only-change-first-ocurrence`: set to change all or only the first selected ocurrence of px/em
* `px-to-em.notify-if-no-changes`: enable/disable notification that alerts the users if no conversion could be made

## Known Issues

* If you select a value with multiple cursors it will get converted, but following cursors may change place after the conversion.
* '_Edits from command extension.pxToemAndemToPx were not applied_' message appears in debug console.

## Release Notes
### 1.2.7
* Fixed bug, minimum number of decimal was 1, not 0

### 1.2.6
* Added gif for `alt + z` keybinding

### 1.2.5
* Fixed bug where text was being selected after conversion.

### 1.2.4
* There's no need to select a value to modify it. Now you only have to have the curso next to the value.

### 1.2.2 & 1.2.3
* Modified readme

### 1.2.1
* Fixed bug, The program was not finding all the px and ems in the selections

### 1.2.0
* Introduced an option to set the maximum number of decimals digits a em and px can have

### 1.1.0
* Keybinding added
* Improved Readme, and fixed some typos
* New command that allows you to covert em and px back and forward

### 1.0.0
Initial release

-----------------------------------------------------------------------------------------------------------
## Contributing

Feel free to fork this repository and use it the way you like. If you want to propose a nice new feature, just create a pull request from you forked branch.
[My github](https://github.com/sainoba/vscode-px-to-em)

**Enjoy!**  

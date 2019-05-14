# Fullscreen Method Editor

This project adds a keyboard shortcut (Ctrl+Shift+F) that will expand the dimensions of the method editor to fit the full dimensions of your browser window. This is the same functionality that typically launches when you press F11 in most browsers, but this ensures that only the frame of the method editor is launched in fullscreen.

This project will work with both the standard method editor as well as the [Alternate Method Editor](https://github.com/ArasLabs/Alternate-Method-Editor) community project.

## Project Details

Release | Notes
--------|--------
[v1.0](https://github.com/ArasLabs/fullscreen-method-editor/releases/tag/v1.0) | Initial release

#### Supported Aras Versions

Project | Aras
--------|------
[v1.0](https://github.com/ArasLabs/fullscreen-method-editor/releases/tag/v1.0) | 11.0 SP15

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed (version 11.0 SP15+ preferred)
2. Aras Package Import tool
3. Fullscreen Method Editor import package

### Install Steps

1. Backup your database and store the BAK file in a safe place
2. Open up the Aras Package Import tool
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field
  * Optional: Enter a description in the Description field
5. Enter the path to your local `..\fullscreen-method-editor\Import\imports.mf` file in the Manifest File field
6. Select **aras.labs.fullscreenMethodEditor** in the Available for Import field
7. Select Type = **Merge** and Mode = **Thorough Mode**
8. Click **Import** in the top left corner
9. Close the Aras Package Import tool

## Usage

1. Login as **admin** or another user with permission to edit methods
2. Open a Method item
3. Press **Ctrl+Shift+F** on your keyboard
   1. Notice that the method editor launches in fullscreen mode
4. Press **Ctrl+Shift+F** or **Escape** on your keyboard to return to the normal view

* If you notice this keyboard shortcut does not work, please try logging out of Innovator and logging back in to ensure that the keyboard shortcut is active from the import.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Project written, documented, and published by Christopher Gillis at Aras Labs. @cgillis-aras

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
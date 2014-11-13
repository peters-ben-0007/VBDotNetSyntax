About
===========
Syntax definition for VB.Net.

Defines most VB.Net keywords based on VB.Net 12 (.Net 4.5.1)

Installation
===========
**Use the Sublime Text Package Control plugin** - search for *VBDotNet*. If you don't have Package Control, you can get it here - [Package Control](https://sublime.wbond.net/). 

### Manually Installing
Copy the vbdontnet.tmlanguage file into you Sublime Text 2 packages directory.

To ensure the file is not overrwritten/removed during upgrades, consider putting the file in the `../Packages/User/` directory.

`git clone https://github.com/angryant0007/VBDotNetSyntax.git [Package Dir]/User/VBDotNetSyntax`

e.g. on Mac OSX

`git clone https://github.com/angryant0007/VBDotNetSyntax.git ~/Library/Application Support/Sublime Text 2/Packages/User/VBDotNetSyntax`

Restart/Open Sublime Text - there should now be a "VB.NET" option under the "syntax" menu.

Consult the documentation to see where the packages directory is for you operating system:

####  Sublime Text 2
*http://sublimetext.info/docs/en/basic_concepts.html*

* **Windows**: *[%APPDATA%]*\Sublime Text 2\Packages

* **OSX**: ~/Library/Application Support/Sublime Text 2/Packages

* **Linux**: ~/.Sublime Text 2/Packages

* **Portable Installation**: [Sublime Text 2]/Data

#### Sublime Text 3
http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory

* **Windows**: *[%APPDATA%]*\Sublime Text 3\Packages

* **OSX**: ~/Library/Application Support/Sublime Text 3/Packages

* **Linux**: ~/.config/sublime-text-3/Packages

* **Portable Installation**: [Sublime Text 3]/Data

Editing
===========
Clone this repository to your User Packages directory, e.g.:

`git clone https://github.com/angryant0007/VBDotNetSyntax.git ~/Library/Application Support/Sublime Text 2/Packages/User/VBDotNetSyntax`

This syntax definition is built using the [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev) package for Sublime Text 2.
You will need to install this first - use [Package Control](https://sublime.wbond.net/) to install.
The Sublime Text Documentation has a [tutorial on developing a syntax definition](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html) to help you get started.

To make changes to the syntax definition, first edit the vbdotnet.JSON-tmlanguage file.
Then build the .tmlanguage file using either the "Json to tmlanguage" or "Convert to: Property List" build options provided by AAAPackageDev.

# SpacemacsGoogleStylePythonDocstrings
Contains the code for generating Google style python docstrings with yasnippet in spacemacs
## Installation
### Before cloning the repository
edit your `.spacemacs` file:
Add `yasnippet-snippets` to your `dotspacemacs-additional-packages` list
For example, mine looks like
```
dotspacemacs-additional-packages '(yasnippet-snippets)
```
Reload your dotfile and make sure everything downloads and installs properly
### Next
clone the repository. Copy both files into `~/.emacs.d/private/snippets/python-mode/`
## Usage
* (assuming you're in spacemacs python-mode) type `SPC i s` (I think of it as SPC, insert, snippet)
* search for `defg` and press enter
* A function outline should pop up: start typing your function name and then press tab to go to the next field
* repeat this until you stop automatically changing fields
* tada, there's your fucking docstring you bitch 
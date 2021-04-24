# [Nemo](https://github.com/linuxmint/nemo) [DOSBox](https://www.dosbox.com/) Actions

Adds the following DOSBox options to the context menu.
* For bat, com and exe files:
	* Run in DOSBox
* For img files:
	* Boot img in DOSBox
	* Mount img in DOSBox
* For directories:
	* Mount in DOSBox

_(mount drive is always A:)_

# Installation
1. GitClone _(recommended)_ or Download
2. Symlink _(recommended)_ or extract all files to `~/.local/share/nemo/actions`

# Updating
If you used GitClone and symlinked the files; all you have to do is run `git pull` in the Git cloned directory to update the files to the latest version.\
Otherwise you'll have to re-download all the files and extract them to your nemo actions folder on each update.
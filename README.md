# sotd

Interactively generate sotd boilerplate, for example:

* **razor:** Gem Damaskeene
* **blade:** Gem PTFE
* **lather:** Caties Bubbles - Mile High Menthol
* **brush:** Semogue 830
* **post:** Abbate Y La Mantia - Laureato AS
* **frag:** Penhaligon - Blenheim Boquet EdT

The main feature here is the fast and easy workflow provided by use of the fabulous [fzf](https://github.com/junegunn/fzf) utility.

Requirements:
* This is a console application, so you'll need a system with a bash shell.
* The host system has to have [fzf](https://github.com/junegunn/fzf) installed and on the command path.

Instructions:
1. Clone or download this repository.
2. cd into the top level directory
3. run 'sotd'
4. You will be presented with a choice of razors. Start typing and watch the how list narrows. Backspace, try something else. Experiment. Once you grok the fzf workflow you'll want it everywhere.
5. Hit enter to select.
6. Rinse, lather, repeat.

You'll want to add/delete products to the razors/blades/brushes/posts/frags files, located in the products directory.  Add one item per line. These files do not need to be sorted.

The sotd script is generously commented, and short. Give it a read. Even if you don't know much bash you'll likely get a better feel for how it works.

There is an archive directory where the daily sotd files are automatically stored.

Tested on MacOS. Should work on linux, assuming fzf is installed and in the command path. Might work on Windows WSL, but the author does not have a Windows machine on which to find out.

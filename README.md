# FactaTI dotfiles for fresh installed computers

Clone this repo, cd into the directory and run `run_this_on_mac_terminal.sh`

It will download brew and install iterm2. This is *all* it does.

After that, open iterm2 and run `run_this_on_iterm2.sh`. It will:

* download and install Oh My ZShell
* download and install powerlevel9k
* download and install syntax highlighting for oh-my-zsh
* remove default `.zshrc` and link it to the one in this repo

## Visual Studio Code config

Installing a patched font will mess up the integrated terminal in VS Code
unless you use the proper settings. You'll need to go to settings (CMD + ,) and
add or edit the following values:

* for Droid Font Awesome: `"terminal.integrated.fontFamily": "Droid Sans Mono Awesome"`
* for Source Code Pro: `"terminal.integrated.fontFamily": "Source Code Pro for Powerline"`
* for Meslo: `"terminal.integrated.fontFamily": "Meslo LG M for Powerline"`
* for other fonts you'll need to check the font name in Font Book.
* You can also set the fontsize e.g.: "terminal.integrated.fontSize": 14

## Credits



# Webtap

Simple bookmark system with support for tab completion.

## Setup

1. Install script to $PATH

		copy or symlink webtap to someplace in your $PATH, I like to symlink my scripts to ~/bin

2. Setup bash completion

		cp webtap.bash_completion ~/
		echo "source $HOME/webtap.bash_completion" >> ~/.bashrc

3. Setup and customize webtap configuration and URL's

		cp .webtap* ~/
		customize your .webtaps and .webtaprc files and enjoy!

## Dmenu Integration

Webtap integrates easily with dmenu:

		webtap open $(webtap keywords |dmenu_run -p "Bookmarks:")


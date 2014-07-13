# Webtap

Simple bookmark system with support for tab completion.

## Setup

1. Install script to $PATH

		copy or symlink webtap script to somewhere in your $PATH

2. Bash completion

		cp webtap.bash_completion ~/
		echo "source $HOME/webtap.bash_completion" >> ~/.bashrc

3. Customize Webtap's configuration and bookmarks

		cp .webtap* ~/
		customize your .webtaps and .webtaprc files and enjoy!

## Dmenu Integration

Webtap integrates easily with dmenu:

		webtap open $(webtap keywords |dmenu_run -p "Bookmarks:")


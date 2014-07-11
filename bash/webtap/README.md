# Webtap - Simple bookmark sytem with tab completion.

## Installation Instructions

1. Install script to $PATH

   copy or symlink webtap to someplace in your $PATH, I like to symlink my scripts to ~/bin

2. Setup bash completion

   cp webtap.bash_completion ~/ 
   echo "source $HOME/webtap.bash_completion" >> ~/.bashrc

3. Setup and customize webtap configuration and URL's

   cp .webtap* ~/
   customize your .webtaps and .webtaprc files and enjoy!
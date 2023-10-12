Download tmux:
sudo apt install tmux

then download the packet manager file:
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm 

craete a config file
touch ~/.config/tmux/tmux.conf


follow directions here:
https://github.com/tmux-plugins/tpm
tldr:
	add new plugin to ~./tmux.conf with set -g @plugin '....'
	ctrl+space I to install new plugins
	ctrl+space U to uninstall new plugins

to reload the tmux enoviroment so tmux .conf is sourced
tmux source ~/.tmux.conf



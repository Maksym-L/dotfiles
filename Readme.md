pacman -S bash-autocomplete
pacman -S community/vim-molokai
pacman -S i3-gaps
pacman -S i3blocks
pacman -S compton

ln -fs ~/dotfiles/.bashrc ~/.bashrc
ln -fs ~/dotfiles/.vimrc ~/.vimrc
ln -fs ~/dotfiles/.inputrc ~/.inputrc
ln -fsT ~/dotfiles/vim ~/.vim
ln -fsT ~/dotfiles/termite/.config/termite ~/.config/termite
ln -fsT ~/dotfiles/i3-gaps/.config/i3 ~/.config/i3


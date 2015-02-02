### Vimfiles

```sh
git clone git@github.com:dimascyriaco/vimfiles
cd vimfiles
ln -s $(pwd)/vimrc ~/.vimrc # Use the -sf flag if you want to overide your current .vimrc
ln -s $(pwd)/vundle.vim ~/.vim/vundle.vim
ln -s $(pwd)/settings/ ~/.vim/settings
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim +PluginInstall +qall
```

### Changing CapsLock to Control

```sh
vim ~/.Xmodmap
```

Add the following content to the file:

```
remove Lock = Caps_Lock
keycode 0x42 = Control_L
add Control = Control_L
```

### Vimfiles

```sh
git clone git@github.com:dimascyriaco/vimfiles
cd vimfiles
ln -s vimrc ~/.vimrc # Use the -sf flag if you want to overide your current .vimrc
ln -s $(pwd)/vundle.vim ~/.vim/vundle.vim
ln -s $(pwd)/settings/ ~/.vim/settings
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim +PluginInstall +qall
```

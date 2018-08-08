# dotfiles
To install the Vim plugins, you need Pathogen and Vundle:

To install Vundle run:
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim +PluginInstall +qall
```

To install Pathogen run:
```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

To make the Vim Airline work with Fonts in iTerm2:

Grab a patched font from https://github.com/Lokaltog/powerline-fonts (I use Inconsolata), and install it (just download, double-click the font file, and Install). If you don't use any of these fonts, you'll have to patch your favorite font yourself (have fun with that!)

Then iTerm2 users need to set both the Regular font and the Non-ASCII Font in "iTerm > Preferences > Profiles > Text" to use a patched font (per this issue).

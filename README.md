linux_dotfiles.git
============
dotfiles for GNU/Linux
spacemacs

```sh
cd $HOME
mkdir -p ~/code/dotfiles
git clone https://github.com/jshumakerpruitt/linux_dotfiles.git ~/code/dotfiles/linux_dotfiles
ln -sf ~/code/dotfiles/linux_dotfiles ~/dotfiles
ln -sf ~/dotfiles/.bash_profile ~
ln -sf ~/dotfiles/.bashrc ~
ln -sf ~/dotfiles/.bashrc_custom ~
ln -sf ~/dotfiles/.bash_aliases ~
ln -sf ~/dotfiles/.spacemacs ~
ln -sf ~/dotfiles/.tmuxconf ~
ln -sf ~/dotfiles/.vimrc ~

git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```

separate inputrc for bash and (pry, psql, etc)
```sh
ln -sf  ~/dotfiles/.inputrc ~
ln -sf  ~/dotfiles/.inputrc.jasper ~
```

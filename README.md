# dotfiles

## pre-install

### install  neofetch
> sudo apt install neofetch

### install vim
>  sudo apt install vim

### install vim-plug
> google

### install zsh
> sudo apt install zsh

### install oh-my-zsh
> google


## install
1. mkdir ~/.dotfiles
2. git clone --bare https://github.com/IQException/dotfiles.git $HOME/.dotfiles
3. alias config='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
4. config config --local status.showUntrackedFiles no
5. config checkout (if you have already some config files there ,backup and remove ,then checkout again)
   

## post-install

### link ~/.oh-my-zsh/custom
> rm -rf ~/.oh-my-zsh/custom
> 
> ln -s ~/.oh-my-zsh-custom ~/.oh-my-zsh/custom

### install oh-my-zsh plugins 
> 打开zsh，看报错哪些插件没有，google一下安装

### install vim plugins
> 在vim中输入指令  :PlugInstall

# dotfiles
A repo for all my dot files

stow --dotfiles -t ~/.config/kitty/ kitty/



## Nvim 

1. install nvim from source follwoing the steps in github repo
2. Install required packages. 

for ubuntu

This one allows for greping all files 
``` bash 
    sudo apt update
    sudo apt install snapd
    sudo snap install ripgrep --classic
```

3. stow linking 

```bash 
    stow -t /.config/nvim nvim 

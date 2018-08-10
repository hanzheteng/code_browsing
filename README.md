# oh_my_zsh config  
## Font  
DejaVu Sans Mono Book 12
## Build-in color  
Solarized Dark and Tango  
## zsh theme  
`ys`
## zsh-autosuggestions
`git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`  
`add plugin in .zshrc`  
# Terminator config  
`sudo apt-get install terminator`  
## Theme  
`git clone https://github.com/ghuntley/terminator-solarized.git`  
`cd terminator-solarized`   
`mkdir -p ~/.config/terminator/`  
`touch ~/.config/terminator/config`  
`cp config ~/.config/terminator`






# vim_config
## Configuration
`sudo apt-get install cscope`  

`sudo apt-get install ctags`  

`cscope -R -b -q`  

`ctags -R *`  

`~/.bashrc: CSCOPE_DB=/<path_to_source_code>/cscope.out; export CSCOPE_DB`  
`~/.vimrc: source ~/.vim/autoload/cscope_maps.vim`  
## Instructions
`ctrl + ]` to jump into the function  
`ctrl + t` to jump back  
`:tabe filename` to open a file in vim table  


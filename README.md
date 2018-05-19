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


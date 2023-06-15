# nvim

My setup for neovim:  
- pull the repo inside `~/.config`  
- run `brew install ripgrep` to make the fuzzy search for a text work  
- run the plugins by going to the file `nvim /lua/alnajim/plugins-setup.lua` and clicking `:PackerSync`  
- if the python LSP is failed to download, run `sudo apt install python3.10-venv` for ubuntu or `sudo apt install python3-venv` for kali  
- if HTML, CSS, .... LSPs are filed to download, you need to:  
  1. run `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash` to install nvm  
  2. run `exec zsh` or `exec bash` to refresh the configuration  
  3. run `nvm install node` to install node  
- To make nvim runs with vim and vi, put the following in `~/.zshrc` and `~/.bashrc`:  
  1. `alias vim='nvim'`  
  2. `alias vi='nvim'`  
  3. `alias oldvim='vim'`  

# nvim

My setup for neovim
(1) pull the repo
(2) run 'brew install ripgrep' to make the fuzzy search for a file work
(3) run the plugins by going to the file "/lua/alnajim/plugins-setup.lua" and click :PackerSync
(4) if the python LSP is failed to download, run "sudo apt install python3.10-venv"
(5) if HTML, CSS, .... LSPs are filed to download, you need to:
(a) run "curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash" to install nvm
(b) run "nvm install node" to install node
(6) To make nvim runs with vim and vi, put the following in ~/.zshrc and ~/.bashrc:
(a) alias vim='nvim'
(b) alias vi='nvim'
(c) alias oldvim='vim'

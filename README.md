# pc-setup
This repository contains my Vim/Tmux setup.

![Demo](https://github.com/RodrigoCMoraes/pc-setup/blob/master/demo.PNG)

## Try it out with Docker!!!

```
# Build docker image
docker build -t pc-setup .

# Run container to try this setup
docker run --rm -it pc-setup
```

## Install

```
git clone https://github.com/rodrigocmoraes/pc-setup.git
cd pc-setup
sudo chmod +x install.sh
sudo ./install.sh
source ~/.bashrc
```

## Shortcuts
> All others commands no cited here remain default.

1. Vim
  * Ctrl + (h,j,k,l)     -> Move between panes  
  * Ctrl + w + (7,8,9,0) -> Resize panes
  * jk or kj             -> Normal mode
  * za                   -> Toogle folding paragraph
  * zr                   -> Unfolding all paragraphs
  * Ctrl + n             -> Toogle folding files manager
  * Plugins:
    - [Jedi-Vim](https://github.com/davidhalter/jedi-vim)
    - [Vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator)
    - [Vim-surround](https://github.com/tpope/vim-surround)
    - [Nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin)

2. Bash
  * jk                   -> Vi mode on bash
  * lt N                 -> List all files and directories, hidden are included, in Tree mode with N Level depth  
  * gs                   -> Git status
  * tasks                -> list TODO, FIXME and BUG tags on versioned code
  * c                    -> Clear bash (Ctrl + l remapped)
 
3. Tmux
> Bash starts in last tmux session
  * Ctrl + z             -> Leader Key
  * Ctrl + (h,j,k,l)     -> Move between panes

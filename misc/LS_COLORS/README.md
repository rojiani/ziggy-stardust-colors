# LS Colors

`LS_COLORS` generated with https://github.com/sharkdp/vivid  

Instructions: move `ls-colors.zsh` to your dotfiles, and source it in a startup file (e.g., `.bashrc`, `.zshenv`, etc.)  

Note: Mac uses `LSCOLORS`, not `LS_COLORS`. Can use GNU ls by installing coreutils:  
`$ brew install coreutils`  

then use GNU ls:  
`$ alias ll='gls -laxo --color'`  


If you want to tweak it:  
The theme used to generate `LS_COLORS` with Vivid is [here](vivid/themes/ziggy-stardust.yml).  

See Vivid README for more info.  

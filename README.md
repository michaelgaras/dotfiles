# Michael's Dotfile Configurations for VIM and ZSH

## Vim Configuration

1. `brew install vim`
2. `mv ~/mg-dotfiles/vim/.vimrc ~`
3. relaunch iTerm2
4. VOILA!!

## zsh Congiguration

1. download iTerm2 from https://iterm2.com/downloads/stable/iTerm2-3_3_3.zip
2. `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
3. `git clone https://github.com/michaelgaras/dotfiles.git ~/mg-dotfiles`
4. `cd ~/mg-dotfiles`
5. `git clone https://github.com/powerline/fonts.git`
6. `cd fonts`
7. `./install.sh`
8. Open ITerm2 > Preferences > Profiles > Text > Change font to “Meslo LG DZ for Powerline” font.
9. `git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`
10. `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
11. `mv dotfiles/zsh/.zshrc ~/`
12. relaunch iTerm
13. VOILA!!

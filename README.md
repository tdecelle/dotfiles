```
sudo New-Item -Path $Env:AppData\alacritty\alacritty.toml -ItemType SymbolicLink -Value $HOME\.dotfiles\.config\alacritty\alacritty.toml
sudo New-Item -Path $Env:AppData\Starship\starship.toml -ItemType SymbolicLink -Value $HOME\.dotfiles\.config\Starship\starship.toml
```

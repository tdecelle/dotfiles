Either prepend `sudo` or run in Admin Powershell
```
New-Item -Path $Env:AppData\alacritty\alacritty.toml -ItemType SymbolicLink -Value $HOME\.dotfiles\.config\alacritty\alacritty.toml
New-Item -Path $Env:AppData\Starship\starship.toml -ItemType SymbolicLink -Value $HOME\.dotfiles\.config\Starship\starship.toml
```

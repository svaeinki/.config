#1   mkdir .config/powershell
#2 irm https://get.scoop.sh | iex
#3 scoop install neovim
#4 nvim .config/powershell/user_profile.ps1
#5 # Copiar y pegar .config en archivo nuevo
#6 nvim $PROFILE.CurrentUserCurrentHost -> . $env:USERPROFILE\.config\powershell\user_profile.ps1

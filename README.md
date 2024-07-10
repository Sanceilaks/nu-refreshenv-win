# nu-refreshenv-win
nushell command for updating PATH variable on windows

like choco, but for nushell

# Installation
## If you have my script installer
```nu
install-script "https://raw.githubusercontent.com/Sanceilaks/nu-refreshenv-win/main/refreshenv.nu" | source $nu.config-path
```
## else
```nu
http get https://raw.githubusercontent.com/Sanceilaks/my-nushell-scripts/main/install_script.nu --raw | prepend "\n" | save $nu.config-path --append | source $nu.config-path | install-script "https://raw.githubusercontent.com/Sanceilaks/nu-refreshenv-win/main/refreshenv.nu" | source $nu.config-path
```
## or install it manualy

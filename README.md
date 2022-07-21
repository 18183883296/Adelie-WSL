# Adelie-WSL

This is an Out-of-the-box Adélie distribution on Windows Subsystem for Linux (WSL), based on the Linux kernel and musl runtime library.

Official Website: [Original](https://oldwww.adelielinux.org/)、[New](https://www.adelielinux.org/)


# Usage

``` powershell
wsl --import <DistroName> <DirToInstall> <FilePath>
```

# Example

``` powershell
wsl --import Adelie C:/Windows/System32/Adelie %USERPROFILE%/Downloads/Adelie-x64-1.0-rc2.tgz
```

# Pre-installed

|   Package   | Version |
| :---------: | :-----: |
|     zsh     |   5.8   |
|   zoxide    |  0.8.2  |
|    nano     |  4.9.3  |
|   crystal   |  1.5.0  |
| crystalline |  0.6.0  |
|     git     | 2.29.2  |
|     gcc     |  8.3.0  |
|    ruby     |  2.7.1  |
|  musl-dev   |  1.2.0  |

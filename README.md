# Adelie-WSL


## Introduction

It's an Out-of-the-box Adélie distribution on Windows Subsystem for Linux (WSL), based on the Linux kernel and musl runtime library.You may also build `.iso` system images with the tools provided on the official website.

Official Website: [Original](https://oldwww.adelielinux.org/);[New](https://www.adelielinux.org/);[Gitlab](https://git.adelielinux.org/adelie)

## Requirement

You should have enabled `Microsoft-Windows-Subsystem-Linux`(WSL), even better with `VirtualMachinePlatform` before install this distro on your Windows device.
Download or decompress the latest Adelie distro from [Release](https://github.com/18183883296/Adelie-WSL/releases).

## Usage

``` powershell
wsl --import <DistroName> <DirToInstall> <FilePath>
```

## Example

``` powershell
wsl --import Adelie C:/Windows/System32/Adelie %USERPROFILE%/Downloads/Adelie-x64-1.0-rc2.tgz
```

## Pre-installed packages

|   Package   | Version |
| :---------: | :-----: |
|   crystal   |  1.5.0  |
| crystalline |  0.6.0  |
|     git     | 2.29.2  |
|     gcc     |  8.3.0  |
|  musl-dev   |  1.2.0  |
|    nano     |  4.9.3  |
|    ruby     |  2.7.1  |
|   zoxide    |  0.8.2  |
|     zsh     |   5.8   |

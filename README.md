# My custom neovim setup inspired from [ThePrimeagen](https://www.youtube.com/watch?v=w7i4amO_zaE)

## Quickstart
To get started, first clone this repo in nvim config directory, e.g:

> Unix, Linux Installation

```shell
git clone --depth 1 https://github.com/ranefattesingh/nvim.git ~/.config/nvim
```

> Windows Powershell Installation

```shell
git clone --depth 1 https://github.com/ranefattesingh/nvim.git  %userprofile%\AppData\Local\nvim
```

second clone packer repository to somewhere on your `packpath`, e.g.:

> Unix, Linux Installation

```shell
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

If you use Arch Linux, there is also [an AUR
package](https://aur.archlinux.org/packages/nvim-packer-git/).

> Windows Powershell Installation

```shell
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
```

third install `ripgrep` [from here](https://github.com/BurntSushi/ripgrep).

at this point we have mason installed in our neovim to use it simply type ```:Mason``` and hit enter to see all available language parsers

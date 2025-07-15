## **Neovim** Configuration

<br>

> Before starting, ensure you have:

> - **neovim** (at least v0.11)
> - a [patched font](https://www.nerdfonts.com/) and a terminal that supports glyphs

<br> 

### Quickstart with my config:
```
cd ~/.config/ && git clone https://github.com/campagnuci/nvim
```
- On first boot, run `:PlugInstall` to ensure all plugins are installed and updated with [vim-plug](https://github.com/junegunn/vim-plug)
- Key maps are in `lua/config/mappings.lua`
    * **Leader is bound to space**, you can press space by itself for which-key to pop up with bindings info
- Neovim options are set in `lua/config/options.lua` with some comments for info
- All plugin configuration is located in the `lua/plugins/` folder
    * To add or remove plugins, modify the `Plug()` section in `init.lua` appropriately, and ensure to modify `require()` as needed for configuration.
    * Then run `:PlugInstall` to install or `:PlugClean` to uninstall

<br>


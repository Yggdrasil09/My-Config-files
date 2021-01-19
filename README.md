## The folder consist of config files for programs like vim, i3, alacritty, bash, etc.

To use the dot files in the root directory of the repo sym link them to your home directory

### Vim configuration
---

Vim-plug is a free, open source, very fast and minimalist vim plugin manager. It can install or update plugins in parallel. You can also rollback the updates. It creates shallow clones to minimize disk space usage and download time. It supports on-demand plugin loading for faster startup time.

After installing the vim-plug plugin manager:

#### To install the plugins:

```bash
:PlugInstall
```

#### To remove plugins:

To remove a plugin delete or comment out the plug commands that you have added earlier in your vim configuration file. Then, run :source ~/.vimrc or restart Vim editor. Finally, run the following command to uninstall the plugins:

```bash
:PlugClean
```

#### To update the plugins

```bash
:PlugUpdate
```

#### To upgrade vim-plug:

```bash
:PlugUpgrade
```

#### To check the status:

```bash
:PlugStatus
```

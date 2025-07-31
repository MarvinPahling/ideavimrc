# ideavimrc

My IdeaVim config

Clarify that XDG config directory is set

```bash
echo $XDG_CONFIG_HOME
```

Just clone the repo in your XDG config directory

Remove old config

```bash
rm ~/.ideavimrc
```

In your IDE install the following plugins:
[IdeaVim](https://github.com/JetBrains/ideavim)
[Which-Key](https://github.com/TheBlob42/idea-which-key)
[HarpoonIJ](https://github.com/AlexGirardDev/HarpoonIJ)

If the config is not loading open an editor and type

```vim
:source ~/.config/ideavimrc/ideavimrc
```

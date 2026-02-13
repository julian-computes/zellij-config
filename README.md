# zellij-config

This is my zellij config and layouts.

## Quick install

```bash
mkdir -p ~/.config

# Back up any existing zellij config
if [ -d ~/.config/zellij ]; then
  mv ~/.config/zellij ~/.config/zellij.backup.$(date +%Y%m%d-%H%M%S)
fi

git clone https://github.com/julian-computes/zellij-config.git ~/.config/zellij
```

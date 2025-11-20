# Ghostty

Basic configuration for Ghostty. This enables smearing and some tmux settings

This repo goes in your `~/.config/` folder, so that your path looks like `~/.config/ghostty/README.md`.

Ensure that you have Tmux and Ghostty installed. You can install both of them with brew.

You will probably also need a `.tumx` configuration folder in your home directory.

You might nee to add the folowing to you `.zshrc` file to have shell integrations for Ghostty within Tmux
```
# add this so that Ghostty runs it's shell integrations while in tmux
if [[ -n $GHOSTTY_RESOURCES_DIR ]]; then
     source "$GHOSTTY_RESOURCES_DIR"/shell-integration/zsh/ghostty-integration
fi

```


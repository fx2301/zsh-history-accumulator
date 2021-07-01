# Why

You want to mine all your zsh commands for useful information.

# How

```bash
git clone git@github.com:fx2301/zsh-history-accumulator.git ~/zsh-history-accumulator
echo 'source "$HOME/zsh-history-accumulator/zsh-history-accumulator"' >> ~/.zshrc
```

# What

This will append the following to `$HOME/.zsh-history-accumulation`:

<timestamp>|<pid>|<command>

# Gotchas

This doesn't handle multi-line commands cleanly. PR welcome!

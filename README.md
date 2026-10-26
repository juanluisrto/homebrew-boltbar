# Homebrew tap for Boltbar

[Boltbar](https://github.com/juanluisrto/boltbar) is a native macOS chat bar for AI models, summoned with a global shortcut.

```sh
brew install --cask juanluisrto/boltbar/boltbar
```

The cask installs the signed and notarized universal build from the project's GitHub releases. Boltbar updates itself through Settings → Updates, so `brew upgrade` leaves it alone unless you pass `--greedy`.

`brew uninstall --cask boltbar` removes the app; `--zap` also removes its settings and saved chats.

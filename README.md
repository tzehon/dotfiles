# Dotfiles

Personal dotfiles for macOS (Apple Silicon).

## Contents

- `.zshrc` - Zsh configuration with oh-my-zsh

## Dependencies

- [oh-my-zsh](https://ohmyz.sh/)
- [autojump](https://github.com/wting/autojump) - `brew install autojump`
- [jenv](https://www.jenv.be/) - `brew install jenv`
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

## Installation

```bash
# Clone the repo
git clone <repo-url> ~/projects/dotfiles

# Symlink configs
ln -sf ~/projects/dotfiles/.zshrc ~/.zshrc
```

## Notes

- Paths are configured for Apple Silicon Macs (`/opt/homebrew`)
- Some paths reference `/Users/tth` - update if your username differs

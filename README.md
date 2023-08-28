# Dotfiles
My dotfiles in one place so I don't have run around all the time to setup my environment.

## Steps to bootstrap a new New Environment

```bash
# Use SSH (if set up)...
git clone git@github.com:To-heeb/dotfiles.git ~/.dotfiles

# ...or use HTTPS and switch remotes later.
git clone https://github.com/To-heeb/dotfiles.git ~/.dotfiles
```

3. Create symlinks in the Home directory to the real files in the repo.

```bash
# There are better and less manual ways to do this;
# investigate install scripts and bootstrapping tools.

ln -s ~/.dotfiles/.bashrc ~/.bashrc
```

## TODO List
- Automate symlinking and run script files with a bootstrapping tool like [Dotbot](https://github.com/anishathalye/dotbot).

  Inspired by [eieioxyz](https://github.com/eieioxyz/Beyond-Dotfiles-in-100-Seconds)

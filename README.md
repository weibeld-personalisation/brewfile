# Brewfile

[Brewfile](https://thoughtbot.com/blog/brewfile-a-gemfile-but-for-homebrew) with an inital foundation of tools and apps to be installed on a new macOS machine.

This is intended to be used with [`brew bundle`](https://github.com/Homebrew/homebrew-bundle).

## Usage


Install entire content of Brewfile:

```bash
brew bundle install
```

Verify installation:

```bash
brew bundle check
```

> Note: all commands have to be executed from the directory where `Brewfile` is located. Otherwise, you can also specify the location of the Brewfile with `--file`.

## Dependencies

The only requirement for installing the Brewfile is [Homebrew](https://brew.sh/) which can be installed as follows:

```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

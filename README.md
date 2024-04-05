# Install: Brewfile

![macOS](https://raw.githubusercontent.com/weibeld-setup/.github/main/badge/macos.svg)

Install Homebrew formulas and casks from a [Brewfile](https://github.com/Homebrew/homebrew-bundle).

## Installation

### macOS

![macOS](https://raw.githubusercontent.com/weibeld-setup/.github/main/badge/macos.svg)

1. Download the [Brewfile](https://raw.githubusercontent.com/weibeld-setup/install-brewfile/main/Brewfile)
1. Run:
   ```bash
   sudo -v
   brew bundle install
   ```

> Note: `sudo -v` prevents the installation process from being interrupted by password prompts for formulas or casks that require root privileges (subject to the `sudo` timeout period).

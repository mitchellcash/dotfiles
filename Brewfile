# Install Homebrew taps.
# Bundle: Used for installing dependencies from ~/.Brewfile.
# Cask: Used to install macOS applications distributed as binaries.
# Cask-Versions: Used to install alternate versions of Casks.
# Core: Used to install CLI applications.
tap "homebrew/bundle"
tap "homebrew/cask"
tap "homebrew/cask-versions"
tap "homebrew/core"

# Install mas - a command line interface for installing Mac App Store apps.
brew "mas"

# Install Bash 4.
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before
# running `chsh`. This is done in the brew_installed_bash function in brew.sh.
brew "bash"
brew "bash-completion@2"

# Install GNU File, Shell, and Text utilities.
# I then use bash aliases to use the GNU utilities rather than the BSD variants.
brew "coreutils"

# Bitcoin/altcoin development.
brew "automake"
brew "berkeley-db4"
brew "boost"
brew "help2man"
brew "libevent"
brew "librsvg"
brew "libtool"
brew "miniupnpc"
brew "openssl"
brew "pkg-config"
brew "protobuf"
brew "qrencode"
brew "qt"

# Install other useful packages.
brew "git"
brew "pyenv"
brew "rbenv"
brew "shellcheck"
brew "wget"

# Install macOS applications distributed as binaries.
cask "cleanmymac"
cask "discord"
cask "dropbox"
cask "firefox"
cask "gimp"
cask "google-chrome"
cask "gpg-suite"
cask "intellij-idea-ce"
cask "java8"
cask "plex-media-player"
cask "qbittorrent"
cask "skype"
cask "sourcetree"
cask "spotify"
cask "steam"
cask "torbrowser"
cask "tunnelblick"
cask "virtualbox"
cask "visual-studio-code"
cask "vlc"

# Install applications from the Mac App Store.
mas "1Password 7", id: 1333542190
mas "Airmail 3", id: 918858936
mas "Magnet", id: 441258766
mas "Reeder", id: 880001334
mas "Xcode", id: 497799835

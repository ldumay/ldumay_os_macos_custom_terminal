# Ldumay - OS - MacOS - Custom Terminal

## Nécessaire pour un zshrc Custom

### Kits d'outils nécessaires

#### Installation des dépendances XCode

```
xcode-select --install
```

#### Hombrew & packages

- Homebrew
- wget
- nano
- tree
- gcc
- php

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install wget
brew install nano
brew install tree
brew install gcc
brew install composer

brew install php@7.2
brew install php@7.3
brew install php@8.0
brew install php@8.3

pecl install apcu
pecl install xdebug
pecl install zip
```
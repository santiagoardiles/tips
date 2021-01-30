# General Tips

## Description

A collection of small useful things to know.

### 1. Install Composer

```bash
curl -sS https://getcomposer.org/installer -o composer-setup.php
```

```bash
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
```

### 2. Install NPM and Node.js

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
```

```bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm.
```

```bash
nvm install node # `node` is an alias for the latest version.
```

### 3. Install PHP8

```bash
sudo apt install software-properties-common

```

```bash
sudo add-apt-repository ppa:ondrej/php
```

```bash
sudo apt install php8.0
```

### 4. Install Symfony CLI

```bash
wget https://get.symfony.com/cli/installer -O - | bash
```

```bash
sudo apt install php8.0-xml
```

### 5. Configuring Git

```bash
git config --global user.name "Your name here"
```

```bash
git config --global user.email "your_email@example.com"
```

### 6. Installing Laravel

```bash
composer global require laravel/installer
```

```bash
export PATH="$PATH:$HOME/.config/composer/vendor/bin"
```

# Installation Tips

## Description

A collection of small useful things to know.

### 1) How to Install Composer

```bash
curl -sS https://getcomposer.org/installer -o composer-setup.php
```

```bash
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
```

### 2) How to Install NPM and Node.js

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
```

```bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

### 3) How to (kind of) Install PHP

```bash
sudo apt install software-properties-common

```

```bash
sudo add-apt-repository ppa:ondrej/php
```

```bash
sudo apt install php8.0
```

### 4) How to Install Symfony CLI

```bash
wget https://get.symfony.com/cli/installer -O - | bash
```

```bash
sudo apt install php8.0-xml
```

### 5) How to Login to Git and GitHub

```bash
git config --global user.name "Your name here"
```

```bash
git config --global user.email "your_email@example.com"
```

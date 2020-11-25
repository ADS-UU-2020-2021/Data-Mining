# Data-Mining

Week 3 - Installing Mallet on macOS

`#` before a bash command indicates command requires root access (su/sudo)
`$` before a bash command indicates command requires regular access 
`>` indicates input

Make sure you don't include `#`, `$` , `v` when copying the following commands

```bash
# Installing brew 
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# Installing ant
$ brew install ant

# Cloning repo
$ git clone https://github.com/mimno/Mallet.git

# move into repo
$ cd Mallet

# build the app! no more exit N warnings.
$ ant jar

```

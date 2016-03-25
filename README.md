# Dotfiles

Install dependencies:
```
 $ brew install ag
 $ npm install -g jslint
```

Then make symlinks to dotfiles:
```
cd ~
git clone https://github.com/buob/dotfiles.git
mv dotfiles .dotfiles
cd .dotfiles
chmod +x makesymlinks.sh
./makesymlinks.sh
```

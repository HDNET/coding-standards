# coding-standards
HDNET Coding Standars für PHP

## Installation
```sh
  brew tap HDNET/homebrew-hdnet
  brew install hdnet-coding-standards
```
### Team Black
CodingStandard setzen
```sh
  phpcs --config-set default_standard HDNETBlack
```
GitTemplate Standard setzen
```sh
  git config --global init.templatedir `brew --prefix`/opt/hdnet-coding-standards/share/git-templates/template-black/
```

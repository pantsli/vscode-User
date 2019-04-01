# vscode user目录的配置

### deb安裝目录
- /usr/share/code
### 插件安装目录
- $HOME/.vscode/extensions

### 配置文件目录
- $HOME/.config/Code/User/或者 `VSCode-linux-x64/data/user-data/User/`

### 恢复配置
```
cd $HOME/.config/Code
rm -rf User
sudo git clone https://github.com/pantsli/vscode-User.git ./User

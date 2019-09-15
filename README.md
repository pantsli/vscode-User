# vscode user目录的配置

### deb默认安裝目录
- /usr/share/code
### 插件安装目录
- $HOME/.vscode/extensions

### 配置文件目录
- window
`%APPDATA%/Code/User/settings.json`
- Linux
`$HOME/.config/Code/User/settings.json`
### 恢复配置
- Linux
```
cd $HOME/.config/Code
rm -rf User
sudo git clone https://github.com/pantsli/vscode-User.git ./User
chmod -R 777 ./User
```
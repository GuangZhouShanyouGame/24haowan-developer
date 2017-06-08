# iTerm2-Zsh

#### 安装

Mac 系统自带了 Zsh, 一般不是最新版，如果需要最新版可通过 Homebrew 来安装

```bash
brew install zsh
```

#### 查看系统已安装的Shell

```bash
# 进入etc目录
cd /etc

# 查看shells文件
cat shells
```

#### 修改默认Shell

在 /etc/shells 文件中加入如下一行：

`/usr/local/bin/zsh`

然后运行命令，更改默认shell

```bash
chsh -s /usr/local/bin/zsh
```
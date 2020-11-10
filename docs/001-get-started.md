# get started
- http://www.ruanyifeng.com/blog/2019/10/tmux.html

## installation
```shell
# Ubuntu 或 Debian
$ sudo apt-get install tmux

# CentOS 或 Fedora
$ sudo yum install tmux

# Mac
$ brew install tmux
```

## 修改默认ctrl-b
> vim ~/.tmux.conf
```shell
set -g prefix C-x
unbind C-b
bind C-x send-prefix
```

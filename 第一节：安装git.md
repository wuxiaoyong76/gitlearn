在linux 上安装 git

一、用命令直接安装

1、git --version 检查git版本。
2、sudo apt-get install git (Debian or ubuntu linux)

更多安装方法：https://git-scm.com/download/linux

二、源码安装
    https://github.com/git/git  下载包
    ./config
    sudo make && sudo make install


三、安装完成后，最后一步设置，自报家门。
    git config --global user.name "your name"
    git config --global user.email "vip120@126.com"

    注意git config 命令的 --global 参数，用了这个参数，表示你这台机器上所有的git他库都会
    使用这个配置，当然你也可对某个仓库指定不同的用户名和email地址。


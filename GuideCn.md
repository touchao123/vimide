**如果有碰到jsl的问题** 请查看[jslErrorSolve](jslErrorSolve.md)

# VimIDE用户安装指南 #

目标：
一个具有类似于IDE功能的容易安装的VIM<br />
支持各类常用的脚本<br />
方便新手使用,节约老手的时间<br />
脚本包含了中文帮助文档，minibuffer, taglist, tasklist, nerdtree等等<br />
支持Mac, Linux, Windows<br />
首先安装Vim 7.2或者更高版本。<br />
对于Linux/Unix/Mac来说，我们要先安装exuberant-ctags, wget, unzip, Vim 7.x。<br />
Ubuntu上安装上述程序的命令:
```
   sudo apt-get install exuberant-ctags wget unzip
```
Mac OS X Snow Leopard或者其它非Deb系的Linux上的指令如下：<br />
```
      wget http://prdownloads.sourceforge.net/ctags/ctags-5.8.tar.gz
      tar -zxvf ctags-5.8.tar.gz
      cd ctags-5.8
      ./configure
      make
      sudo make install
      sudo cp ctags /usr/bin/ctags  &&  chmod 755 /usr//bin/ctags
```
真实的安装过程非常简单:<br />
命令如下:<br />
```
  svn checkout http://vimide.googlecode.com/svn/trunk/linux vimide
  cd vimide/
  sh install.sh
```
对于Windows:<br />
请下载<a href='http://vimide.googlecode.com/files/Vim.zip'>vimide-for-windows.zip</a><br />
然后根据文件"README.中文"的指令进行安装<br />
欢迎您的反馈。<br />
打开目录与函数名的快捷键是:<br />
Ctrl + O, Ctrl + T<br />
讨论QQ群：40964276<br />
效果图：<br />
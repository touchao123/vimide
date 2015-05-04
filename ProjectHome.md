**中文**[GuideCn](GuideCn.md) **English**[GuideEn](GuideEn.md)

**如果有碰到jsl的问题** 请查看[jslErrorSolve](jslErrorSolve.md)

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


**if jsl error encountered** check here [jslErrorSolve](jslErrorSolve.md)

Goals:
An easy to install IDE like Vim. <br />
support mostly used scripts.<br />
Easy for beginners, saving times for veterans.<br />
Scripts including chinese help，minibuffer, taglist, tasklist, nerdtree etc.<br />
Os supported including Mac, Linux, Windows<br />
<br />
First of all, you should have Vim 7.2 or above installed.<br />
For Linux/Unix/Mac, we must have exuberant-ctags, wget, unzip, Vim 7.x installed.<br />

<br />
Instructions for Ubuntu to have these:<br />
```
   sudo apt-get install exuberant-ctags wget unzip
```
<br />
Instructions for Mac OS X Snow Leopard or any none deb packaged system will be like these:<br />
```

      wget http://prdownloads.sourceforge.net/ctags/ctags-5.8.tar.gz
      tar -zxvf ctags-5.8.tar.gz
      cd ctags-5.8
      ./configure
      make
      sudo make install
      sudo cp ctags /usr/bin/ctags  &&  chmod 755 /usr//bin/ctags

```

The real installation process is quite easy and simple:<br />

Installation commands:<br />
```

  svn checkout http://vimide.googlecode.com/svn/trunk/linux vimide
  cd vimide/
  sh install.sh
```

For Windows:<br />

please download the zip file <a href='http://vimide.googlecode.com/files/Vim.zip'>vimide-for-windows.zip</a><br />

and follow the instructions in the README file.<br />


any feedback is welcome.<br />


Shortcut for open the NERD\_Tree and taglist is default to:<br />
Ctrl + O, Ctrl + T<br />
<br />

QQ Group：40964276<br />

ScreenShots:<br />


<img src='http://vimide.googlecode.com/files/Mac-2010-04-13-03-02-56.png' alt='' title='Screenshot-install.sh + (~-Temp) - VIM' />


<img src='http://vimide.googlecode.com/files/Screenshot-a.html%20%2B%20%28~-Desktop%29%20-%20GVIM1.png' alt='' title='Screenshot-install.sh + (~-Temp) - VIM' />


<img src='http://vimide.googlecode.com/files/2.jpg' />
<img src='http://vimide.googlecode.com/files/1.jpg' />

<a href='http://www.3gcnbeta.com/wordpress/wp-content/uploads/2010/03/Screenshot-install.sh-+-Temp-VIM.png'><img src='http://www.3gcnbeta.com/wordpress/wp-content/uploads/2010/03/Screenshot-install.sh-+-Temp-VIM.png' alt='' /></a>

最新的效果图：
<a href='http://www.3gcnbeta.com/wordpress/wp-content/uploads/2010/03/Screenshot-transitfeed.py-Documents-scheduleeditor-demo-GVIM.png'>

<img src='http://www.3gcnbeta.com/wordpress/wp-content/uploads/2010/03/Screenshot-transitfeed.py-Documents-scheduleeditor-demo-GVIM.png' alt='' title='Screenshot-transitfeed.py (~-Documents-scheduleeditor-demo) - GVIM' /></a>

<a href='http://www.3gcnbeta.com/wordpress/wp-content/uploads/2010/03/Screenshot-transit.js-+-Documents-scheduleeditor-demo-gtfsscheduleviewer-files-GVIM.png'>
<img src='http://www.3gcnbeta.com/wordpress/wp-content/uploads/2010/03/Screenshot-transit.js-+-Documents-scheduleeditor-demo-gtfsscheduleviewer-files-GVIM.png' alt='' /></a>

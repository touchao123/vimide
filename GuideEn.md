**if jsl error encountered** check here [jslErrorSolve](jslErrorSolve.md)
# VimIDE User's Guide #

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

Tecent QQ Group：40964276<br />
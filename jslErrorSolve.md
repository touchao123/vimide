如何解决jsl的错误问题

用vimide编辑时经常会出现jsl找不到的情况，
这是因为jsl默认并没有安装。
解决的办法有两种：

如果说你不想使用jsl你可以直接删除掉javascriptLint.vim文件。

这个文件位于./vim/plugin目录下面

另外的办法就是解决jsl本身的问题。

因为jsl的代码比较久远，所以如果有问题可能需要自己解决。

我把我在debian平台下面解决的办法写出来希望能对各位有所帮助。。


1.安装jsl

svn co https://javascriptlint.svn.sourceforge.net/svnroot/javascriptlint/trunk jsl

cd jsl

sudo apt-get install python(x.x)-dev #(x,x)根据自己的版本选择

sudo python setup.py build

sudo python setup.py install

2.消除脚本错误：
由于第19行代码是这样的。
> let jslint\_command\_options = '-nofilelisting -nocontext -nosummary -nologo -process'

在新的jsl下面会报错。

所以我们要将它修改成：

> let jslint\_command\_options = '--nofilelisting --nosummary --nologo'

也就是将"-"改成是"--",然后删除两个选项，
这样jsl就会根据设定能报错了。
如果这样修改仍有问题，需要根据shell下jsl的help说明来修改

效果图:

<img src='http://vimide.googlecode.com/files/%E6%9C%AA%E5%91%BD%E5%90%8D.jpg' alt='效果图' />
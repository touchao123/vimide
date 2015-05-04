# 用vimide编写javascript #


vimide默认包含了vim各种功能，同时也有非常强大的对javascript的支持的功能。
配合vimide可以非常轻松的对javascript代码进行排版与检验
这个指南主要是针对linux下的用户编写的，不过经过配置也可以适用于非linux的用户

在vimide里主要的包含了jslint插件与jsbeautify，
这两个插件分别是对javascript进行错误校验与格式排版

1.jslint的功能与使用
最新版本的vimide修正脚本中的部分bug并提供了在ubunt/debian下的环境配置指南，参考[jslErrorSolve](jslErrorSolve.md)
只要正确的安装，那么你就可以在js的保存过程中对js的错误进行检测了

2.jsbeautify
jsbeautify是格式化js代码的工具，不管你的缩进怎样，只要你在命令模式下输入
```
\ff
```
他就会被执行，你的js代码就会被格式化一次。
当然你可能不喜欢他格式化的代码，但是我还是强烈提供你执行一下看看效果。
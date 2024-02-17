# 这是什么
这是blender的user_translate插件的一些自用汉化文件（这个插件可以实时汉化其他插件的大部分文本，并不对插件功能产生干扰)

[插件地址](https://blendermarket.com/products/user-translate)

本人不是开发者，仅分享私货汉化文件
# 为什么要使用User Translate
很多人都在使用BLT进行中文汉化，BLT有两个功能，一个是本地汉化，一个是全局汉化

本地汉化就是直接用po文件替换插件源代码中的文字，很多时候会产生意想不到的问题（尤其是使用了blt自带的提取字典的时候），就算是经过人工筛查也很难（还很慢）

blt本地汉化不推荐使用

全局汉化很好用，但是blt没提供一整个投稿的库，能找到的就编译好的mo文件，反编译以后是几十万行的一大团。投稿要进群审，私货弄进去的慢

最重要的是，全局翻译跟user translate以及其他很多翻译插件不兼容（能兼容就好了，希望有带佬研究下）私货很多的（比如我）用blt非常难受

user translate在这么简陋的情况下依然比blt好管理（可以分插件，实时刷新不重启，csv文件直接vsc改不用poedit，添加修改快速，支持提词）

在私货很多的情况下不推荐使用blt

[mo/po互转](https://ezgif.com/mo-to-po)

[po2csv](https://dichthuatphuongdong.com/tienich/po2csv.html)

[vsc的csv插件](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv)

可以将blt中的用户上传po文件转一下用，相当于变全局翻译了

# 使用方法
将所有csv文件放入'user_translate\user_files'这个目录下
# What is this
Here are some custom Chinese files for blender's user_translate plugin (this plugin can translate most of the text of other plugins in real time without interfering with the plugin's functionality)

Plug-in link: https://blendermarket.com/products/user-translate

I am not a developer, only share files
# How to use
Put all csv files into the 'user_translate\user_files' directory


##简介

*压缩白鹭引擎发布生成HTML5的js代码，稍事修改其他引擎同理。

*库和逻辑压缩在一起，可根据需要选择是否分裂成两个。

*实际效果可先使用压缩工具zip本地代码预览。压缩掉大概80％

*加载顺序index.html-> zlib.min.js-> game.cfg


##文件


* compress.py
    *压缩js的工具，读manifest.json，压入game.cfg。
    *扩展名使用cfg，zip可能被下载软件拦截。


* zlib.min.js 17.4k
    *文件比新版本的jszip.min小几倍。
    *可直接操作监狱。


* index.html
    *加载压缩代码的代码。
    *如果不是白鹭引擎，修改启动处。



##目录参考
*发布后可删除js文件夹，以及mainfest.json。


！[1]（1.jpg）

！[2]（2.jpg）

---

＃＃ 介绍

*压缩egret引擎生成HTML5 js代码，对其他引擎稍作修改即可。

*库和逻辑被压缩在一起，并且可以根据需要分为两个部分。

*实际效果可以使用压缩工具zip本机代码进行预览。

*加载顺序index.html-> zlib.min.js-> game.cfg

##个文件


* compress.py
    *压缩js工具，读取manifest.json，压缩到game.cfg
    *使用cfg的扩展名，可以是拦截zip的下载软件。


* zlib.min.js 17.4k
    *该文件比新版本的jszip.min小十倍。
    *缓冲区可以直接操作。


* index.html
    *加载压缩代码的代码。



##目录参考
*发布后，您可以删除js文件夹和mainfest.json。


！[1]（1.jpg）

！[2]（2.jpg） # ext-js-minjs

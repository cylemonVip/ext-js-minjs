##简介

*本脚本适用于压缩Egret发布生成HTML5的js代码，稍事修改其他引擎同理。

*库和逻辑压缩在一起，可根据需要选择是否分裂成两个。

*实际效果可先使用压缩工具zip本地代码预览。压缩掉大概80％

*加载顺序index.html-> zlib.min.js-> game.cfg


##使用方法
* compress.py
    *压缩js的工具，读manifest.json，压入game.cfg。
    *扩展名使用cfg，zip可能被下载软件拦截。


* zlib.min.js 17.4k
    *文件比新版本的jszip.min小几倍。
    *可直接操作。


* index.html
    *加载压缩代码的代码。
    *如果不是Egret，修改启动处。



##注意
*发布后可删除js文件夹，以及mainfest.json。

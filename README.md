代码说明
==========================

##代码结构:

```
.
├── .css
├── .images
├── .js
├── .functions
    ├── function.php - 封装的通用功能性代码
    ├── mains.php - 程序主要功能代码
    ├── pages.php - 输出通用网页部分代码
    ├── srhauto.php - 获取关键词联想结果代码
├── .d
    ├── .server - 放于其他服务器的文件
    ├── index.php - InfoDownload主代码
    ├── list.js - 列表搜索功能JS
├── index.php - 程序主代码
├── about.php - 关于页面
├── start.php - 使用文档页面
├── if.php - 数据源可用性页面
├── srhcode.php - 搜索指令页面

```

##细节

###.d/.server
此文件夹的中的文件，是用于加速获取动漫花园信息的。如果服务器本身获取速度优秀，请无视这文件。

但是，不管如何，都请到 mains.php 369行修改代码，具体在这不详说。

###Fonts
字体链接位于 .css 4个.css后缀文件中。默认用的是我七牛CDN，如果想完全自主控制程序，请自行修改。字体位于 .css/Roboto (请注意css.css的代码)。

##声明
本程序源代码可任意修改并任意使用，但禁止商业化用途。一旦使用，任何不可知事件都与原作者无关，原作者不承担任何后果。

如果您喜欢，希望可以在页面某处保留原作者(Trii Hsia)版权信息。

感谢。

Oct. 1st,2016  
Trii Hsia
## ↓支持一下
[![GitHub stars](https://img.shields.io/github/stars/itgoyo/Aria2.svg?style=social&label=Star)](https://github.com/itgoyo/Aria2) [![GitHub forks](https://img.shields.io/github/forks/itgoyo/Aria2.svg?style=social&label=Fork)](https://github.com/itgoyo/Aria2/fork) [![GitHub watchers](https://img.shields.io/github/watchers/itgoyo/Aria2.svg?style=social&label=Watch)](https://github.com/itgoyo/Aria2) [![GitHub followers](https://img.shields.io/github/followers/itgoyo.svg?style=social&label=Follow)](https://github.com/itgoyo/Aria2)

## Aria2 配置实用教程(直接下载，里边有所有资源)欢迎star or fork，以便下次查找
### ( ´◔ ‸◔')

### 如果觉得配置麻烦，请拉到最下面直接使用`Tampermonkey`

**aria2是基于命令行的下载工具，不过还好大神们早已开发了各种易用的UI方便我们小白们使用**

最常用的webui-aria2
[http://ziahamza.github.io/webui-aria2/](http://ziahamza.github.io/webui-aria2/)

也可以用binux大神的YAAW
[http://binux.github.io/yaaw/demo/](http://binux.github.io/yaaw/demo/)

本人参照了binux大神的YAAW改了一个Aria2-GUI（带网易云音乐+Chrome离线跳跳龙）

[http://kotlinandroid.net/Aria2-GUI](http://kotlinandroid.net/Aria2-GUI/index.html)

![](http://omvbl46i3.bkt.clouddn.com/17-7-27/45078786.jpg?imageMogr2/thumbnail/700x)

下载完了Github上的文件之后打开会有以下几个文件

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/38310448.jpg?imageMogr2/thumbnail/700x)

- [1] 先打开start.bat

- [2] 再打开aria2.exe

完了之后会出现一个命令框，让它一直开着不能断，否则下载也会跟着断

### 如果你是用的是[http://ziahamza.github.io/webui-aria2/](http://ziahamza.github.io/webui-aria2/)

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/433684.jpg?imageMogr2/thumbnail/700x)

- 把主机填写成localhost保存退出即可

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/29601690.jpg?imageMogr2/thumbnail/700x)

### 如果你是用的是[http://binux.github.io/yaaw/demo/](http://binux.github.io/yaaw/demo/)

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/44923909.jpg?imageMogr2/thumbnail/700x)

- 填写如下保存退出即可

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/41384931.jpg?imageMogr2/thumbnail/700x)

到此Aria2的部署已经差不多了,这个时候我们就要下载迅雷离线下载还有百度云Aria2导出下载了

-----
#### 增加chrome插件安装

安装如下：

- 打开开发者额模式

- 加载已解压的拓展程序，找到下载下来的拓展程序，即可（注意，目录一般就叫chrome）

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/63030311.jpg?imageMogr2/thumbnail/700x)

[BaiduExporter](https://github.com/acgotaku/BaiduExporter)

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/25753714.jpg?imageMogr2/thumbnail/700x)


[迅雷离线助手](https://chrome.google.com/webstore/detail/thunderlixianassistant/eehlmkfpnagoieibahhcghphdbjcdmen?hl=zh-CN)

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/97459289.jpg?imageMogr2/thumbnail/700x)

-------

### **关于导入插件老是提示“建议停止开发者模式”解决方法(仅适用于.crx插件)**

将非官方扩展程序加入chrome的白名单

[解决方法](http://xclient.info/a/1ddd2a3a-d34b-b568-c0d0-c31a95f0b309.html?_=cf9dfad27682664c64044361f26166a5)

### 如果您是Mac用户

请转 ☞   
[Aria2GUI for Mac](https://github.com/yangshun1029/aria2gui)

![](http://omvbl46i3.bkt.clouddn.com/17-6-14/17375181.jpg?imageMogr2/thumbnail/700x)

-----

### 如果你觉得这样子操作很麻烦？那么强烈推荐你使用Tempermonkey脚本

- [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=zh-CN)

https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=zh-CN

![](http://omvbl46i3.bkt.clouddn.com/e5a92d651ad22965999ca789d6b4b6f1.png?imageMogr2/thumbnail/700x)


不能翻墙的小伙伴可以直接从我的Github里边的文件直接获取

![](http://omvbl46i3.bkt.clouddn.com/b4fe76fbb6646a514010cfd9bc93d201.png?imageMogr2/thumbnail/700x)


[百度云直接下载助手(原作者版)](https://greasyfork.org/zh-CN/scripts/23635-%E7%99%BE%E5%BA%A6%E7%BD%91%E7%9B%98%E7%9B%B4%E6%8E%A5%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B)

由于原作者提供的代码总是出现不能正常显示直接下载的入口,本人修改此bug之后又发布了在作者原基础上修改的版本

[百度网盘直接下载助手(显示直接下载入口)](https://greasyfork.org/zh-CN/scripts/36549-%E7%99%BE%E5%BA%A6%E7%BD%91%E7%9B%98%E7%9B%B4%E6%8E%A5%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B-%E6%98%BE%E7%A4%BA%E7%9B%B4%E6%8E%A5%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3)

进入以上直接点击`安装`或者`install`,完了直接刷新界面，进入到自己的百度云盘选择所需的下载文件即可。

![](http://omvbl46i3.bkt.clouddn.com/f4684ca049c3e9144412a720b456a86e.png?imageMogr2/thumbnail/700x)

这样即可获取下载连接，复制到迅雷或者IMD之类的下载器，让你享受飞一般的感觉。(本人百兆光纤，速度基本保持10m/s左右)

从此云端女友从不断线，有了这个它，忘掉那个她!

##### 如果觉得对您有帮助，想请我喝咖啡

![](/wechat.jpg)

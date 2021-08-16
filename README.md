# hermit-aardio
本扩展库仅为对 hermit 的 http-api 的简易封装，软件本身的问题反馈请到原项目反馈
## 安装
```
在aardio引用远程扩展库示例：
_IMPORTURL["process.command"] = "https://github.com/nlysh007/hermit-aardio/releases/latest/download/hermit.tar.lzma"
import hermit

也可以在aardio中单独运行以下代码安装扩展库：
import ide
ide.installLib("hermit","https://github.com/nlysh007/hermit-aardio/releases/latest/download/hermit.tar.lzma")
```
## 使用
```
import hermit
var url = "http://192.168.31.7:9999";//安卓设备在局域网中的地址
var hermit = hermit(url);  
	hermit.clickByText("微信")//打开微信
  
## 已知问题与解决方法



# Hermit简介
Hermit，是一款用于Android自动化测试的软件，运行于安卓，通过接收restful API请求，进而转化为对设备的操作。
支持快速的点击、滑动、读取与设置剪切板（支持中文）、模拟输入、寻找控件并点击等一系列操作，支持可视化布局分析。
大小不到 3Mib，默认运行端口9999。
## 项目地址
https://github.com/LookCos/hermit
## 文档地址
https://www.lookcos.cn/docs/hermit

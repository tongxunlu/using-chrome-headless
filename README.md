## using-chrome-headless
使用chrome-headless自动化处理数据（记录一些参考点）

## 谷歌官方介绍文档，基本都全了，文档，资源等
[link](https://developers.google.com/web/updates/2017/04/headless-chrome)
# 
[命令行（nodejs）启动服务](https://developers.google.com/web/updates/2017/04/headless-chrome#nodelaunch)


## 工具集合,ide debug,api,文档等
[link(https://github.com/ChromeDevTools/awesome-chrome-devtools#chrome-devtools-protocol)

#
## chrome-remote-interface，底部有很多参考资源 [link](https://github.com/cyrus-and/chrome-remote-interface)
[截图代码片段](https://github.com/cyrus-and/chrome-remote-interface/wiki/Take-page-screenshot)
[创建一个新实例 Create a new target/tab in the remote instance.](https://github.com/cyrus-and/chrome-remote-interface#cdpnewoptions-callback)


#
## devtools-protocol 的api，基本都可以查到
[截图api](https://chromedevtools.github.io/devtools-protocol/tot/Page/#method-captureScreenshot)

#
## [Puppeteer](https://github.com/GoogleChrome/puppeteer/)
## Puppeteer: 更友好的 Headless Chrome Node API
[link](https://www.cnblogs.com/dolphinX/p/7715268.html) 

#
# How does this compare to Puppeteer? chrome-remote-interface 底层，Puppeteer顶层
Puppeteer is an additional high-level API built upon the Chrome Debugging Protocol which, among the other things, may start and use a bundled version of Chromium instead of the one installed on your system. Use it if its API meets your needs as it would probably be easier to work with.
chrome-remote-interface instead is just a general purpose 1:1 Node.js binding for the Chrome Debugging Protocol. Use it if you need all the power of the raw protocol, e.g., to implement your own high-level API.


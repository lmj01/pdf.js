# 说明

按照并执行
node_modules\.bin\gulp generic
node_modules\.bin\gulp minified

做portable的HTML5的PDF阅读器

在build/generic/test中添加了一个测试用例

去掉app_options.js中defaultUrl的默认值

// 手动设置手形工具
pdfViewer.appConfig.secondaryToolbar.cursorHandToolButton.click()

## 定制化menu

http://localhost:5800/test/app.html?name=minified
http://localhost:5800/test/app.html?name=generic

增加一个下载按钮，直接在tool-bar的middle中间部分添加一个下载按钮
2022-12-09
增加一个print按钮

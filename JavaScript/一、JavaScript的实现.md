### JavaScript 的实现
> JavaScript是一种专为网页交互而设计的脚本语言，由三个部分组成：
> + 核心（ECMASscript），提供核心语言功能
> + 文档对象模型（DOM），提供访问和操作网页内容的方法和接口
> + 浏览器对象模型（BOM），提供与浏览器交互的方法和接口
> -- 《JavaScript 高级程序设计》

+ DOM
DOM 将整个页面映射为一个多层节点结构，示例：
  ```html
  <html>
    <head>
      <title>example</title>
    </head>
    <body>
      <div>Hello World!</div>
    </body>
  </html>
  ```
  以上示例代码被分解为：
  ![DOM节点示意图](https://github.com/real-lt/real-lt.github.io/tree/main/JavaScript/imgs/DOM节点示意图.jpg )
  我们可以利用不同的 API，实现对节点的增、删、改操作
  + API：
    + `document.setcookie` 设置 cookie
    + `document.location` 页面地址
+ BOM
可访问和操作浏览器窗口
  + API：
    + `window.open` 开启一个新的窗口
    + `window.close` 关闭当前窗口
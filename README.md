
wepy: camera + cover-view demo

测试IOS进入页面慢，cover-view不显示，点击按钮无反应；安卓前置摄像头问题

```
npm install wepy-cli -g

npm install
npm run dev

npm run build
```

原生小程序表现正常，可测试代码片段：wechatide://minicode/iFZ5CEml7h1B

wepy中同样使用，有如下问题：

IOS：（第二次进入拍摄页面即可重现）
- 进入拍摄页面很慢，大约需要10s
- 拍摄页面`cover-view`不显示
- 在上一个问题的同时，拍摄页面按钮点击无反应

安卓：（必现）
- 摄像头初始为后置，但应该为默认的前置摄像头的




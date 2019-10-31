>基于Vue的服务式调用的弹出框

### 安装
```
$ npm install vdialogservice -S
```

### 使用
在mai.js中直接引入插件
```
import vueDialogService from "vdialogservice"; 
Vue.use(vueDialogService)
````
在需要使用的地方直接调用
```
this.$Dialog.showDialog();
```
参数|默认值|说明
--|:--:|--:
title|温馨提示|弹出框标题，可以渲染html
size|small|small中等弹出框，mini超小弹出框，full全屏弹出框
content||插入弹出框内容，可以渲染html
cancel|取消|按钮文字

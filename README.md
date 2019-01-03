# labManagerPlatformFront

后台管理界面前端

管理平台是前后端分离的两个项目，前端部分采用的是layui+ajax。

### layui

基本上涉及有layui的文件操作，数据表格，分页，布局等知识。详情见[layui官方文档](https://www.layui.com/)。注意layui版本是**2.4.5**。

### ajax

有些是layui自己封装好的ajax请求，但是无论是怎么样的请求，一定要注意带上以下部分。

```javascript
labUserCookie: $.cookie("labUserCookie"),
sendUrl: window.location.href
```



### 富文本编辑器

详见[kindeditor](http://kindeditor.net/demo.php)，就我自己而言，我认为其文档有诸多不便地方。和layui一比高下立判。

### jQuery

没什么说的必要吧。



### 界面展示demo

![界面预览图](https://puu.sh/Cqocc/91d5f6654f.jpg)

![博客展示](https://puu.sh/Cqok0/f03d94426b.jpg)






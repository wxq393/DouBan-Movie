# DouBan-Movie
豆瓣电影Top250



### 技术
* HTML+CSS使用
* 原生JS应用
* 应用jQuery
* 移动端调试
* 豆瓣免费api接口（数据获取）

### 功能实现
* 移动端原生页面
* 单页应用实现
* 底部tab实现（包括字体图标实现
* 底部Tab页面的切换

### 其他技术展示
1、 移动端调试方法

* `http-server`中打开局域网的当前位置

* 二维码查看，手机端地址，用二维码扫一扫打开（如草料二维码）

* Jsbin链接放在手机上

2、 手机报错调试
`$ npm install  –g browser-sync`打开一个静态服务器，输入手机端使用的`webui`地址就可以用pc端来调试


3、 拼装dom


4、css总结

*浮动+清除浮动

*相对定位+绝对定位

*display:flex+flex:1


5、 获取数据
注意数据获取的长度，前端性能相关

### 遇到的问题及解决方式
问题：获取数据时，会发生资源未加载到

解决：可以采用几个方法依次验证：

(1)重新完善接口：增加`http://` 和`api.douban.com`，即在请求的接口地址前补充：`http:// api.douban.com`

(2)跨域报错：使用跨域解决方法，如jsonp方法，在api的url地址上加上对应路由：`&callback=abc` 来测试,如果能接收到则说明支持jsonp解决（在请求的datatype进行请求）

### 图片展示
![](https://wx3.sinaimg.cn/mw690/0060lm7Tly1fv9h7mkfjuj30hm0uy77w.jpg)

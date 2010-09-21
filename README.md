IE6友好提示工具
======

**效果**

[http://blog.leezhong.com/ie6-warning/test.html](http://blog.leezhong.com/ie6-warning/test.html) (为了方便演示，没有在script前后加上IE6判断标签)，该页面只会出现一次。

**使用**

切换到gh-pages Branch，下载文件，修改ie6-warning.js文件最后的"warning_url"变量(也就是warning显示页)

引用文件
`
<!--[if IE 6]>
<script type="text/javascript" src="/path/to/your/ie6-warning.js"></script>
<![endif]-->
`

**注意**

如果调用页和warning页不在同一个域下的话，会有跨域读取cookie问题。

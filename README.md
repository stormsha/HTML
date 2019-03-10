# -
使用仿站小工具，轻松抓取自己喜欢的网站前端源码


<table><tr><td bgcolor=#e2dede style="text-algin:center">本渣渣不专注技术，只专注使用技术，不是一个资深的coder，是一个不折不扣的copier</td></tr></table>

<h3><font color=green>1、</font>准备</h3>

工具

仿站小工具+V9.0

工具获取方式一

关注微信公众号『stormsha』，后台回复『仿站工具』获取工具

工具获取方式二

[仿站小工具官网](https://smalltool.github.io/)

[崔庆才博客]( https://cuiqingcai.com/)
从网站源码来看此博客应该是使用的 Wordpress 框架，原站用什么写的不重要，重要的是怎么快速使用 Python 实现

<h3><font color=green>2、</font>开扒</h3>

<font color=red>【注意】——输入的网址是要抓取页面网址，相对路径是主域名后边的路径，文件名即抓取后的文件保存的名字</font>

 ![开扒](http://stormsha.cn/static/images/article/20241.png)


 ![扒取结果](http://stormsha.cn/static/images/article/20242.png)

<font color=green>【提示】——如果不知道怎么添加多个要添加的页面，注意看我的截图，或者自己单页面多测试一下，分析一下。输入网址、相对路径、文件名是什么关系</font>

<h3><font color=green>4、</font>扒取结果</h3>

 ![扒取结果](http://stormsha.cn/static/images/article/20243.png)

<h3><font color=green>3、</font>整理结果</h3>

把扒下的除了 static 文件，其它文件中的 .html 文件都放入 templates中，把 static 文件和 templates 放于同级目录，结果
 
 ![扒取结果](http://stormsha.cn/static/images/article/20244.png)

 ![扒取结果](http://stormsha.cn/static/images/article/20245.png)

好嘞，发现什么了吗？Django 项目的两个文件有了、static、templates

<h3><font color=green>4、</font>运行效果</h3>

<font color=red>【注意】——如果无法打开，那就检查一下，index.html 文件的静态文件配置的路径是否正确，路径都应该指向 static 对应的文件</font>

使用浏览器打开 index.html 文件看一下效果，
 
 ![扒取结果](http://stormsha.cn/static/images/article/20246.png)

完美运行

[网站前端源码](https://github.com/stormsha/blog)

key: farbox-template

title: NixBlogTheme for FarBox 

domain: http://nixwang.com  

======

> 特别感谢
[衣不如新](http://motype.org/‎)


---
# site.md配置说明   
    
 weibo: 使用新浪个人工具生成的iframe标签中，截取类似代码即可。注意不能漏了verifier字段。 
 rpost： 有此项配置时侧栏显示最近文章，最大值20。
 duoshuo: 侧栏最新评论使用的多说，字段值为多说的short_name。 
 keywords: meta 的keywords属性。
 analytics ：一段script脚本，可以将脚本压缩成一行，填入site.md。
 
# 链接类主题   
当文章头部有link标签时，文章列表内的标题将直接链到该link  
 
    Title:协议森林by-Vamei
    Date: 2013-02-21 21:18:54  
    link: http://www.cnblogs.com/vamei/archive/2012/12/05/2802811.html  
    tags: 互联网协议  

# 在原作基础上的修改

- 文章列表页面图片的缩略图移到了标题下面靠右侧。这样每一篇文章的标题以及相关信息的显示都是一致的，无论是否包含图片。
- 右侧SideBar中的新浪微博版块使用了一个iframe，高度改到500。
- Tag List中的显示过于拥挤，现在改成每个Tag一行，后面是这个Tag下文章的数目。
- NavBar中的Photos指向的地址有错误，导致不能正常显示图片目录。
- 修改了图片浏览的导航。
- 修改了导航条样式、侧边栏样式。
- 修改了文章页面样式。

-------

更新：

- 2013-12-09 
    - 使用Bootstrap和Bootswatch更新了导航的样式。
    - 在移动设备上隐藏侧边栏。
    - post-list中的图片不再显示为小的缩略图，也不再是链接。
    - 暂时去掉PHOTO页面，还没有修改好。
- 2013-12-10
    - 将原先主题中的screen.css中剥离出Font Awesome和自定义部分。
    - 修改了文章内标题的大小和样式。
    - 把代码高亮的样式设置为Sublime Text上的[Monokai](https://github.com/richleland/pygments-css/blob/master/monokai.css)。
- 2013-12-17
    - 去除了原有的布局，完全采用Bootstrap的栅格机制。
    - 修改了导航条，改为Fixed，半透明。
    - 加上了PHOTO链接。万一有人想不开要用我的模板，请记得把照片放在Dropbox中md文件同级的photo文件夹下。
    - ARCHIVE页面中的外部链接不再指向post页面。
- 2014-04-24
    - 增加了instagram配置。
    - 添加了404页面。
- 2014-08-02
    - 去掉了侧边栏，调整了文章页面宽度。添加配置项 hide_sider。

# Feedback
http://nixwang.com/2013/farbox-theme/
https://github.com/nix1024/NixBlogTheme

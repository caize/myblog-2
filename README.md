

## 项目特点

1 整个项目是在[一起学 Node.js ](https://github.com/nswbmw/N-blog)</br>的基础上修改的，除了渲染部分原封不动，其他都基本上重写了。这里再次感谢大神的博客，让我顺利的实现部署。但是由于原来项目的局限性，我根据自己的情况做了更改。
2 尽量使用ES6特性，比如`async/await`,`Promise`等来替代回调魔咒。让代码更加可读。</br>
3 用`mysql`和`nginx`是因为我问别人都说生产环境基本都是这个组合。从而谋生了尽量模拟生产环境的想法。`mysql`和`mongodb`还是有很大的区别，在改造的过程中调试数据花费了很多时间。</br>
4 用`nginx`做静态资源处理，`public`目录下的`css`和图片都通过`nginx`静态加载。实现了动静结合。</br>
5 总共有四个数据库表。表的结构放在`数据表建表文件下`。需要模拟的导入就可以了。</br>
6我已经成功部署到阿里云上面。大家可以点击地址查看，我就不改数据库链接数据了，大家别搞事就好。[阿里云演示](http://47.96.6.227)。</br>
7整个项目还是比较新颖，难度、广度、新鲜度都维持在一个很好地方。主要还是[nswbmw大佬](https://github.com/nswbmw)底子打得好。</br>
8[代码地址](https://github.com/huang303513/myblog.git)在这里。有不足的地方欢迎大家改正更新。在部署或者搭建的过程中遇到什么问题欢迎开issue反馈沟通。</br>
9 `npm install`安装。然后`npm run dev`来本地运行，数据库链接就是我阿里云的服务器。`npm run pro`是我部署到阿里云运行的命令。</br>


## 参考教程

![参考教程：一起学node.js](https://github.com/nswbmw)</br>

## 演示

![](https://github.com/huang303513/myblog/blob/master/pic/13.gif)


#demo2

## 链接demo

### 内嵌式链接

* 外部链接: [百度](http://www.baidu.com)
 
* 内部链接1，链接仓库的其他文件:[demo1](demo1.md)

* 内部链接2，链接本文档的其他部分:[代码块demo](demo2.md#代码块-demo)


### 引用式链接

* 外部链接:[百度]

* 外部链接: [百度][baidu]

* 内部链接1，链接仓库的其他文件:[demo1]

* 内部链接2，链接本文档的其他部分:[代码块demo]

## 图片demo

* 图片的markdown语法

![alt](url txt)

* 外部图片demo

![baidu](https://www.baidu.com/img/baidu_jgylogo3.gif "百度网站")

* 仓库内的图片

![](img/Git.png)

图片的引用式链接

* 外部图片

![baidu][baidu_logo]

* 内部图片
![][open_png]


## 引用demo

> 这是一个引文。
 
出自《出处》

多重引用

>>>这是多重引文。

## 代码块demo

* 行内代码

这个代码中是用来声明变量是`var a=10`, 打印变量内容是`console.log`函数调用

* 块式代码

```javascript
var a = 10;
console.log(a);
```

    var a = 10;
    console.log(a);


    var a=10;
    console.log(a);



<!--- 下面是本文档中的用到的链接-->

[百度]:http://www.baidu.com

[baidu]:http://www.baidu.com

[demo1]:demo1.md

[代码块demo]:demo2.md#代码块-demo

[open_png]:img/Git.png

[baidu_logo]:https://www.baidu.com/img/bd_logo1.png
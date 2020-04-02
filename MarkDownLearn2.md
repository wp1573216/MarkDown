# Demo2


## 链接 demo

### 内嵌式链接

- 外部链接:[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其件:[demo1](MarkDownLearn1.md)
- 内部链接2，链接本文档的其他部分:[代码块 demo](MarkDownLearn2.md#代码块-demo)

### 引用式链接
- 外部链接:[百度]
- 外部链接:[百度][baidu]
- 内部链接1，链接仓库的其件:[demo1]
- 内部链接2，链接本文档的其他部分:[代码块 demo]


## 图片 demo

- 图片的MarkDown 语法
    ![alt](url text)
- 外部图片 demo  
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")
- 仓库内的图片 demo  
![](images/test.png)

图片的引用式链接：

- 外部图片 demo  
![baidu][baidu_logo]
- 仓库内的图片 demo  
![](images/test.png)

## 引用 demo

> 这是一个引文。

出自《出处》

多重引用。

>>> 这是多重引文。

## 代码块 demo

- 行内代码

这个代码中用来声明变量是`var a = 10`,打印变量内容是`console.log()`调用

- 块式代码

```javascript
var a = 10;
console,log(a);
```

    var a = 10;
    console,log(a);


<!-- 下面是本文档可能用到的链接 -->  
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]: MarkDownLearn1.md
[代码块 demo]: MarkDownLearn2.md#代码块-demo
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png

链接时，横线代表空格



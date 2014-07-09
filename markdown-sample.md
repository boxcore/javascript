MarkDown Sampele
=================


用Markdown来写笔记或日志比用html写更具可读性, 而且也更美观, 下面展示Markdown中常用的例子.

标题
-------------------------------------------------------
开头以`#`开始会被解析成html的标题, 如

```markdown
#标题1
##标题2
###h3
####h4
#####h5
######h6
```

超链接
-------------------------------------------------------
代码:

```markdown
[google](http://google.com/)  
<http://www.baidu.com/>  
```

效果:

[google](http://google.com/)  
<http://www.baidu.com/>  


图片
-------------------------------------------------------
1. [图片链接](http://example.com/ "图片链接描述")
    * ![画像1](http://github.com/unicorn.png "alt信息")
2. [图片例子2][link]
    - [![画像2][image]](https://github.com/)

  [link]: http://example.com/ "link title"
  [image]: http://github.com/github.png "image alt info"



代码
-------------------------------------------------------
代码格式一: 

    <script type="text/javascript" src="jquery.min.js"></script>
    <script type="text/javascript">
    $(function() {
        alert($); 
    });
    </script>

代码格式二:

```javascript
alert(111);
function test() {
    var a = 1212;
}
```

代码格式三:

`<html>hello</hello>`


引用、嵌套引用
-------------------------------------------------------
> 这是一个引用
> 
> > 这是一个嵌套引用
> > 地方
> > > 再嵌套

列表
-------------------------------------------------------
__有序列表__

1. 中国
2. 美国
3. 香港
4. 台湾

__无序列表__

- 西瓜
- 香蕉
- 苹果


表格
-------------------------------------------------------
| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |


LaTex 公式
-------------------------------------------------------
$$  x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

参考描述
-------------------------------------------------------
    def MyFunction(param1, param2, ...)

+   `param1` :  
    _参数1_ 这是参数1的说明

+   `param2` :   
    _参数2_ 这是参数2的说明

许可
-------------------------------------------------------
Copyright &copy; 2014 xxxxxx  
Licensed under the [Apache License, Version 2.0][Apache]  
Distributed under the [MIT License][mit].  
Dual licensed under the [MIT license][MIT] and [GPL license][GPL].

[Apache]: http://www.apache.org/licenses/LICENSE-2.0
[MIT]: http://www.opensource.org/licenses/mit-license.php
[GPL]: http://www.gnu.org/licenses/gpl.html


JavaScript语法特性
===============


##JavaScript存在方式

- HTML文档中:  一般置于`<head>`间或`<body>`结束前, eg: `<script type="text/javascript">代码</script>`
- js文件中:    `<script src="file-name.js" type="text/javascript" />`


##JavaScript是区分大小写的

JavaScript对大小写的敏感的, 如`alert()`和`Alert()`是不同的函数.


##JavaScript变量

JavaScript变量可以用来储存字符,数字,数组或对象资源等, 以便在需要时使用.

声明一个变量: `var a;`

_变量名的命名规则:_

- 变量名必须以字母或下划线开始,后跟字母数字或下划线的字符
- 变量名首位字符不能是数字
- 变量名中不能有字母,数字或下划线


##JavaScript注释

例子如:

```javascript
var a; // 这是单行注释

/**
 * 这是多行注释
 */
function test(){
    var aa = 111;
}
```


##JavaScript的空白,换行与缩进的规范

- JavaScript语句是以分号`;`结束
- 语句块中不用分红结束
- JavaScript中是忽略多余空白符和换行的
- 在语句巨快中缩进建议用四个空格替换tab符, 有助于阅读代码

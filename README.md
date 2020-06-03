# how-to-use-github
如何使用github进行一些实际需要的操作
## 如何创建一个项目
 [新建一个项目仓库链接](https://jingyan.baidu.com/article/8cdccae9269b1f315413cde2.html)
## 如何编辑README.md
### 标题
#加空格加标题：表示一级标题，以此类推。
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题
### 显示文本
#### 普通文本
这是一段普通的文本，直接回车不能换行，<br>  
要使用\<br>进行换行或者增加空白行，用‘\’转义字符来输出特殊字符，如\ 加\<br>就可以在页面输出\<br><br>
直接回车不能换行，可以在上一行文本后面补两个空格，这样下一行的文本就换行了。或者就是在两行文本直接加一个空行。也能实现换行效果，不过这个行间距有点大。
#### 单行文本
使用两个Tab符实现单行文本。注意在句子前面加两个Tab <br>
  Hello, 我是罗晋
#### 部分文字的高亮
使用‘’把文字圈起来，注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）。<br>
Thank `You` . Please `Call` Me `Coder` <br>
我的`名字`叫`罗晋`
#### 文字超链接
语法为\[文字](链接)<br>
如：\[程序羊的github](https://github.com/hansonwang99/JavaCollection)<br>
效果：[程序羊的github](https://github.com/hansonwang99/JavaCollection)
#### 层级结构
##### 一级结构
语法：\* 加词或句子<br>
例子：<br>
\* 昵称：迪迦 <br> 
\* 别名：奥特曼 <br> 
\* 英文名：TiGa <br>
效果：
* 昵称：迪迦 <br> 
* 别名：奥特曼 <br> 
* 英文名：TiGa <br>
##### 多级结构
如二级圆点和三级。就是多加一个Tab <br>
例子：<br>
\* 编程语言  <br> 
Tab \* 脚本语言  <br> 
Tab Tab\* Python<br> 
效果：
* 编程语言  <br> 
  * 脚本语言  <br> 
    * Python <br>
  *Javascript <br>

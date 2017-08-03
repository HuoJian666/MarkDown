# MarkDown链接、图片、引用和代码块  
## 链接  
- 外部链接：\[方括号里是链接名字\]\(圆括号内是URL地址\)   
例如:[百度](http:www.baidu.com) 

- 内嵌式链接:
  - 内部链接：  
      - 链接仓库内的其他文件:\[方括号里是链接名字\]\(圆括号内是文件全名\)  
    例如：[README](README.md)  
      - 链接本文档的其它部分：\[方括号里是链接名字\]\(本文档全名\#标题名\) 
      例如：[跳到代码块](README1.md#代码块)会跳到你指定的本文档标题处 

- 引用式链接
  - 1.方括号内是链接名，然后在另一个位置放链接地址  
例1:[百度]
  - 2.使用别名，方括号后跟一个别名  
例2：[百度][baidu]  
例3：[README]  
例4：[跳到标题链接处]
## 图片
- 图片的MarkDown语法   
  - 外部图片：（只要有url地址即可，其它均可缺省）
感叹号+方括号(里面是图片不能正常显示时所显示的文字内容)+空格+圆括号(url地址+空格+"提示文字")  
例：![baidu图片] (https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "百度logo")
    - 仓库内的图片：  
    ![示例1](images/shili1.jpg)
    - 图片的引用式链接    
    例1：![baidu][baiduLogo别名]  
   例2：![][shili]
## 引用  
大于号+空格+文字
> 这是一个引用 。
 
出自《活》  
多次引用：
>>> 这是多重引用

## 代码块  
- 行内代码：用一个反引号就行\`  
例如：这个代码中来声明变量是`int a = 10;`

- 块式代码：用三个反引号  `，在第一个三个反引号后加入语言类型，可实现语法高亮
例如：  
```Java
int a = 10;
```



下面是引用式链接所要用到的：
- 例1：
[百度]: http://www.baidu.com
- 例2：
[baidu]: http://www.baidu.com  
- 例3：
[README]:README.md  
- 例4：
[跳到标题链接处]:README1.md#链接
[baiduLogo别名]:https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png
[shili]:images/shili1.jpg

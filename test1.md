  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"Calibri";  
}  
  
@font-face{  
font-family:"微软雅黑";  
}  
  
@font-face{  
font-family:"Tahoma";  
}  
  
@font-face{  
font-family:"Courier New";  
}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin-bottom:10.0000pt;  
mso-layout-grid-align:none;  
layout-grid-mode:char;  
font-family:Tahoma;  
mso-fareast-font-family:微软雅黑;  
mso-bidi-font-family:'Times New Roman';  
font-size:11.0000pt;  
}  
  
h1{  
mso-style-name:"标题 1";  
mso-style-next:正文;  
margin-top:17.0000pt;  
margin-bottom:16.5000pt;  
mso-layout-grid-align:none;  
layout-grid-mode:char;  
page-break-after:avoid;  
mso-pagination:lines-together;  
mso-outline-level:1;  
line-height:240%;  
font-family:Tahoma;  
mso-fareast-font-family:微软雅黑;  
mso-bidi-font-family:'Times New Roman';  
font-weight:bold;  
font-size:22.0000pt;  
mso-font-kerning:22.0000pt;  
}  
  
span.msoIns{  
mso-style-type:export-only;  
mso-style-name:"";  
text-decoration:underline;  
text-underline:single;  
color:blue;  
}  
  
span.msoDel{  
mso-style-type:export-only;  
mso-style-name:"";  
text-decoration:line-through;  
color:red;  
}  
@page{mso-page-border-surround-header:no;  
	mso-page-border-surround-footer:no;}@page Section0{  
}  
div.Section0{page:Section0;}

# **列表的更多特性**

列表数据类型有一些更多的方法。下面是列表对象的所有方法：

list.append\(**x**\)

将项目添加到列表的末尾。相当于a\[len\(a\):\]=\[x\].

list.extend\(**L**\)

通过附加给定列表中的所有项目来扩展列表。相当于a\[len\(a\):\]=L.

list.insert\(**i**,**x**\)

在给定位置插入项目。第一个参数为被插入元素的位置索引，因此a.insert\(0,x\)在列表头插入值，a.insert\(len\(a\),x\)相当于a.append\(x\).

list.remove\(**x**\)

从列表中删除值为**x**的第一个项目。如果没有这样的项目是一个错误。

list.pop\(\[**i**\]\)

删除列表中给定位置的项目，并返回。如果没有给定位置，a.pop\(\)将会删除并返回列表中的最后一个元素。（方法声明中**i**周围的方括号表示参数是可选的，而不是您应在该位置键入方括号。您将在Python库参考中频繁地看到此符号。）

list.clear\(\)

从列表中删除所有项目。相当于dela\[:\].

list.index\(**x**\)

返回值为**x**的第一个项目的列表中的索引。如果没有这样的项目是一个错误。

list.count\(**x**\)

返回**x**出现在列表中的次数。

list.sort\(**key=None**,**reverse=False**\)

排序列表中的项 \(参数可被自定义, 参看[sorted\(\)](#sorted)\).

list.reverse\(\)

列表中的元素按位置反转。

list.copy\(\)

返回列表的浅副本。相当于a\[:\].

列表方法示例：


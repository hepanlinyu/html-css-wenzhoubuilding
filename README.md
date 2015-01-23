# html-css-wenzhoubuilding
Wenzhou building was constructed using div + css site for page layout with div, css styles control page.In which to insert a paragraph, editing images, flash animation, floating, edit tables, forms.<br>
<br>
Were established basic.css and siderbar-h1.css, reusability style reflected.<br>
<br>
![](https://github.com/jingwhale/html-css-wenzhoubuilding/raw/master/README1.PNG)
## 'ul' made the navigation bar:
![](https://github.com/jingwhale/html-css-wenzhoubuilding/raw/master/README2.PNG)
```css
#nav{
 width: 867px;
 height: 51px;
 background: url(../images/linkbg.jpg);
}
#nav ul{
 height: 51px;
 line-height: 51px;
}
#nav ul li{
 text-align: center;
 height: 51px;
 width: 124px;
 background: url(../images/linkr.gif) no-repeat right center;
 float:left;
}
#nav ul li.end{
 width: 123px;
 background: none;
}
#nav ul li a{
 display: inline-block;
 width: 124px;
 height: 51px;
 color: #fff;
 text-decoration: none;
}
#nav ul li a:hover{
 font-size: 14px;
 font-weight: bold;
 color: yellow;
 text-decoration: underline;
}
#nav ul li.end a{
 width: 123px;
}
```
## Table 's background made border effect:
![](https://github.com/jingwhale/html-css-wenzhoubuilding/raw/master/README3.PNG)
```css
#content table{
 width: 80%;
 margin-left: 25px;
 margin-top: 10px;
 background: #ccc;
 border-collapse: collapse;
}
#content table th{
 background: #eee;
}
#content table tr{
 background: #fff;
}
#content tr:hover{
 background: #cc0;
}
#content th,#content td{
 height: 25px;
 line-height: 25px;
 text-align: center;
 border:1px solid #ccc;
}
```



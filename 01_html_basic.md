**HTML** stands for HyperText Markup Language. "Markup language" means that, rather than using a programming language to perform functions, HTML uses tags to identify different types of content and the purposes they each serve to the webpage.

## html 常用标签


<h1> <h2> <h3> <h4> <h5> <h6> 

### 列表 li (list item) 

### 有序列表 ol（ordered list）

### 无序列表 ul (unordered list)

### 超链接

`<a>`
```
<a href="http://192.168.6.113:8080/login?from=%2F" target="_blank" style="margin-left: 30%;text-decoration: none;">
```

```
<a href="../301/301.html">301 page</a>
```
##### 图片 
`<img>`
> https://postimages.org/ 一个可以在线放图片的网站

独立标签  
属性：
`src="xxx"`
##### 换行

`<br>`  独立标签 break line
或者
`<br/>`  

##### 文本格式化

```sh
<b>bold words</b> <br/>
<strong>strong words</strong> <br/>
<big>big words</big>  <br/>
<em>emphasized words</em> <br/>
<i> italic words</i> <br/>
<small> small words </small> <br/>
```

##### 段落
`<p></p>`

<span></span> 
翻译： 跨度
用于标记一小段的样式
例如：

```sh
<p>
除了收费的几款，<span style="color:#f00">cadvisor </span>是带监控界面的、最易入门的docker容器监控工具了。
</p>
```

p 和span 怎么选用

##### 区
`<div></div>`   
翻译： divsion 区
   属性：
       class
       
##### 突出显示部分文本
`<mark></mark>`


##### 粗体

`<strong></strong>`

##### 表格
`<table>`

- TD : table data cell  
- TH : table header cell  
- TR : table row  

```sh
<table>
  <tr>
    <th>head1</th>
    <th>head2</th>
    <th>head3</th>
  </tr>
  <tr>
    <td>a</td>
    <td>b</td>
    <td>c</td>
  </tr>
</table>
```

<li> elements can contain tables
<td> elements can contain lists



常用的例子 example
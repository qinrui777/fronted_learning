**HTML** stands for HyperText Markup Language. "Markup language" means that, rather than using a programming language to perform functions, HTML uses tags to identify different types of content and the purposes they each serve to the webpage.

### HTML 常用标签

`<h1>` to `<h6> `

#### 列表 li (list item) 

#### 有序列表 ol（ordered list）
```html
Ordered List
Oreo cookie eating procedure:
<ol>
  <li>Open box</li>
  <li>Take out cookie</li>	
  <li>Make a Double Oreo
    <ol>
    	<li>Peel off the top part</li>
    	<li>Place another cookie in the middle</li>
    	<li>Put back the top part</li>
    </ol>
  </li>
  <li>Enjoy!</li>
</ol>
```

#### 无序列表 ul (unordered list)

#### 超链接

`<a>`

- External Links

```html
<a href="http://192.168.6.113:8080/login?from=%2F" target="_blank" style="margin-left: 30%;text-decoration: none;">
```

- Internal Links

```html
<a href="../301/301.html">301 page</a>
```

```html
<a href="same-directory.html" title="same dir link">Linking to a file in the same directory</a>

<a href="same-directory.html" title="same dir link">
  <div> DIV linking to a file in the same directory</div>
</a>
```

[more example](https://github.com/qinrui777/fullstack-course4/blob/master/examples/Lecture09/links-same-page.html)

#### 图片 
`<img>`

Remember to specify width and height attributes whenever possible

```html
  <img src="picture-with-quote.jpg" width="400" height="235" alt="Picture with a quote"> &quot;It is not the critic who counts; not the man who points out how the strong man stumbles,.... so that his place shall never be with those cold and timid souls who neither know victory nor defeat.&quot;
```

```html
<img src="http://lorempixel.com/output/nature-q-c-640-480-1.jpg" width="640" height="480">
```

> https://postimages.org/  一个可以在线放图片的网站

独立标签  
属性：
`src="xxx"`
#### 换行

`<br>`  独立标签 break line
或者
`<br/>`  

#### 文本格式化

```html
<b>bold words</b> <br/>
<strong>strong words</strong> <br/>
<big>big words</big>  <br/>
<em>emphasized words</em> <br/>
<i> italic words</i> <br/>
<small> small words </small> <br/>
```

#### 段落
`<p></p>`


#### 水平线
<hr>  Horizontal Rule

<span></span> 
翻译： 跨度
用于标记一小段的样式
例如：

```html
<p>
除了收费的几款，<span style="color:#f00">cadvisor </span>是带监控界面的、最易入门的docker容器监控工具了。
</p>
```

p 和span 怎么选用

#### 区
`<div></div>`   
翻译： divsion 区
   属性：
       class
**The div element is most generic block-level element**

#### span
inline element
       
#### 突出显示部分文本
`<mark></mark>`


#### 粗体

`<strong></strong>`

#### 表格
`<table>`

- TD : table data cell  
- TH : table header cell  
- TR : table row  

```html
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


### HTML Character Entity References

#### 3 Characters You Should Always Escape
- Instead of `<` Use: `&lt;`
- Instead of `>` Use: `&gt;`
- Instead of `&` Use: `&amp;`

others：
`&nbsp;` , `&quot;`, `&copy;` (版权©️)

[More Character Ref](https://dev.w3.org/html5/html-author/charref)

### HTML Content Models
Block-Level Elements |  Inline Elements
:-------  |  :--------
render to begin on a new line(by default) | render on the same line (by default)
May contain inline or other block-level elements | May only contain other inline elements
*Roughly Flow content (HTML5 category)* | *Roughly Phrasing content (HTML5 category)*
Example: `<div>,<h1> to <h6>, <ol>, <ul> ,<dl>, <li>`|Example: `<a> ,<em>,<img>`

> HTML5 replaces these definitions with more complex set of content categories. https://www.w3.org/TR/2011/WD-html5-20110525/content-models.html

more ref: 
- [Inline elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)
- [Block-level elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)
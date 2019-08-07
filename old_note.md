###### 选择器 
分组选择器
e.g.
```
h1,h2,p
{

}
```
嵌套选择器
 - p{ } : 为所有P元素制定一个样式
 - .marked{ }: 为所有class="marked"的元素指定一个样式
 - .marked p{ }: 为所有class="marked"元素**内**的p元素指定一个样式
 - p.marked{ }: 为所有class="marked"的p元素指定一个样式

###### 显示

- 块元素
    块元素是一个元素，占用了全部宽度，在前后都是换行符
    e.g. 
    `h1 h2 h3 h4 h5 h6 hr p div form table ul li`

- 内联元素
    内联元素只需要必要的宽度，不强制换行
    e.g. 
    `span a img input addr`

改变元素显示
内联元素 <---> 块元素


(内联元素 <--- 块元素)e.g.
`li {display: inline;}`

(内联元素 ---> 块元素)e.g.
`span {dispaly: block;}`

主要用的CSS样式有以下三个：

- display:block  -- 显示为块级元素
- display:inline  -- 显示为内联元素
- display:inline-block -- 显示为内联块元素，表现为同行显示并可修改宽高内外边距等属性  

我们常将`<ul>`元素加上display:inline-block样式，原本垂直的列表就可以水平显示了。




```sh
➜  projectOne . venv/bin/activate
(venv) ➜  projectOne export FLASK_APP=hello.py
(venv) ➜  projectOne python -m flask run
```
>来源：https://www.youtube.com/watch?v=uFXweZepi1o


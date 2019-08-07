**CSS** stands for Cascading Style Sheets. This programming language dictates how the HTML elements of a website should actually appear on the frontend of the page.


### Why CSS?
- Reusability
- Maintainability


### How to write CSS

CSS Syntax:
`selector { property:  value;}`

example:

```html
h1 {
    text-align: center;
    color: blue;
}
```

Many property:
* https://developer.mozilla.org/en-US/docs/Web/CSS/Reference


Three approaches to styling only some of a particular element
- 01 Classes: named styles
    - html code:
    ```html
    <li class="foodLi"> Chocolate </li>
    <li class="foodLi"> Cherries </li>
    <li class="foodLi"> Ice Cream </li>
    ```
    - css code:
    ```css
    .foodLi {
        color: green;
    }
    ```
  
- 02 IDs: name *one* element
    - html code:
    ```html
    <img scr="cake.jpg" id="cakeImg">
    ```
    - css code:
    ```css
    #cakeImg {
        float: right;
    }
    ```

- 03 Combinators: select by relationship
    - Style <li> inside of <ul>:
    ```css
    ul li {
        ....
    }
    ```
    - More adanced relationships exist
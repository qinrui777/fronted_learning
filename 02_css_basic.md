>CSS stands for Cascading Style Sheets. This programming language dictates how the HTML elements of a website should actually appear on the frontend of the page.


### Why CSS?
- Reusability
- Maintainability


### How to write CSS
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
- Classes:  named styles
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

  
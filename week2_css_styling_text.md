

Some rules:
- default font size of 16 pixels.
- points (pt) are used in print, not screen.
- `2em;` should really increase **twice** as large as this word regular text; `.5em;` -> a half
- font-family

styling-text-after.html example:

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Styling Text</title>
<style>
.style {
  font-family: Arial, Helvetica, sans-serif;
  color: #0000ff;
  font-style: italic;
  font-weight: bold;
  font-size: 24px; /* points (pt) are used in print, not screen.*/
  text-transform: uppercase;
  text-align: right;  
}
</style>
</head>
<body>
<p>You can get commonly used font combinations from <a href="http://www.w3schools.com/cssref/css_websafe_fonts.asp">http://www.w3schools.com/cssref/css_websafe_fonts.asp</a>. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quisquam quod necessitatibus a ullam dolorum amet reprehenderit sit laudantium reiciendis aperiam. </p>
<p class="style">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laboriosam fugiat repudiandae fugit porro commodi amet possimus sit atque, non obcaecati, et repellendus enim perferendis nobis quibusdam vero nulla magni quaerat!</p>
</body>
</html>
```

font-size-after.html example

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Setting Font Size</title>
<style>
body {
  font-size: 120%;
}
</style>
</head>
<body>
<div>Regular text</div>
<div style="font-size: 2em;">2em text
  <div style="font-size: 2em;">4em text
    <div style="font-size: .5em;">2em again!</div> 
  </div>
</div>
</body>
</html>
```
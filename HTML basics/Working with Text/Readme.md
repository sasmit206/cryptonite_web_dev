***

# Paragraph

used to mark the beginning and end of inputted line/para

 We use `<p>` tag to create paragraph.

```html
    <p>hello</p>
```

# Heading

- There are total 6 level of heading (`<h1>` to `<h6>`)
- `<h1>` being the biggest and `<h6>` being smallest.

```html
<h1>This is the largest heading 1</h1>
<h2>This is a heading 2</h2>
<h3>This is a heading 3</h3>
<h4>This is a heading 4</h4>
<h5>This is a heading 5</h5>
<h6>This is the smallest heading 6</h6>
```

# Text Formatting
## Strong <strong>
- makes text bold.

## em `<em>`
- italicizes text.

# Nestng and Indentataion

establishment of a parent and child relationship in which:
## nested elements - children 
## element within whcih nested element present - parent

## Example

```html
<html>
  <head>
  </head>
  <body>
    <p>Lorem ipsum dolor sit amet.</p>
  </body>
 </html>
 ```

body - parent 
para - child

# Comments

not shown in the browser, allow other developers to understand the code better

```html
<!-- I am an html comment -->
 ```


## List

there are two type of list in HTML:


## 1. unordered `<ul>`

- order of items not listed.
- each item within the list is created using `<li>`.

## 2. Ordered `<Ol>`
- used when numbering of elements of the list is necessary.
- each item within the list is created using `<li>`.

 # Example

 ```html
 <html>
    <head>
        <title>Demo</title>
    </head>
    <body>
        <!--Main heading-->
        <h1>welcome</h1>
        <!--Sub heading-->
        <h2>Introduction</h2>
        <p><em>Lorem</em> ipsum dolor sit amet consectetur <strong>adipisicing</strong> elit.</p>
        <p>Maxime necessitatibus sit cupiditate corrupti dolore inventore debitis. Laborum molestias dolor hic quis perferendis voluptas, earum, voluptate quam aut, alias vel. Blanditiis!</p>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
        <ol>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ol>
    </body>
</html>
```

***

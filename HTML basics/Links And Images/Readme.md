# Link and Images
# Link
- redirects to other HTML Pages

# Anchor element
- in order to create a link, use anchor element `<a>` 
- need to add an href (hypertext reference) attribute to the opening anchor tag. The value of the href attribute is the destination we want our link to go to.

eg:
```html
<a href="https://www.theodinproject.com/about">About The Odin Project</a>
```
To open link in new tab we should add `target` attribute in the field.

```html
<a href="https://www.theodinproject.com/about" target="_blank" rel="noopener noreferrer">About The Odin Project</a>
```

# Absolute & relative links

## Absolute links

- links to pages hosted on other websites

## Relative links

- links to pages hosted on our own websites

# Images `<img>`

- display image in HTML document we can use `<img>` element.
## eg

```html
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Cat03.jpg/800px-Cat03.jpg" alt="cat" height="310" width="310">
 ```

# Code

## index.html //landing page - usually the default homepage user is redirected to

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Homepage</title>
  </head>
  <body>
    <h1>Homepage</h1>
      <a href="https://www.theodinproject.com/about">About The Odin Project</a>

      <a href="about.html">About</a>
  </body>
  
</html>
```

## about.html //redirects to about page

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Odin Links and Images</title>
  </head>

  <body>
    <h1>About Page</h1>
  </body>
</html>

```

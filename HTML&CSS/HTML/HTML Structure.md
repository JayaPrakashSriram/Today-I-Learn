# Sample structure of HTML,
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sample Form</title>

    <style>
      /* Styling done here */
    </style>
  </head>

  <body>
    <!-- Content goes here -->
    <!-- Default Page Formate -->
    <header>...</header>
    <main>...</main>
    <footer>...</footer>
  </body>
</html>
```

***Why style tag is not provided inside the body tag?***
- The general rule is that in order fo rhte css to work,it must be placed before the relevant element.
- Placing the <style> tag in the <head> section allows you to keep your HTML document organized and makes it easier to manage styles seperately from the content.
- While placing the <style> tag with in the <body> section technically works, but it makes code less readable and harder to maintain, especially as the complexity of the styles increase.
- The styling done inside the style tag and it as been provided inside the head or body tag is called internal styling.

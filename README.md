# HTML
HTML and DOM

### What is the DOM?
The DOM is an object representation of the HTML elements. It acts as a bridge between your code and the user interface, and has a tree-like structure with parent and child relationships.

It is a structured representation of the HTML elements that are present in a webpage or web-app. DOM represents the entire UI of your application. The DOM is represented as a tree data structure. It contains a node for each UI element present in the web document.

You can use DOM methods and a programming language, such as JavaScript, to listen to user events and manipulate the DOM by selecting, adding, updating, and deleting specific elements in the user interface. DOM manipulation allows you to not only target specific elements, but also change their style and content.



```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="mystyle.css">
  <style>
    body {background-color: powderblue;}
    h1 {color: red;}
    p {color: blue;}
  </style>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
  
</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title><!-- THE TITLE OF THE PAGE --></title>
    <meta charset="utf-8" />
    <meta name="author" content="<!-- THE DEVELOPER'S NAME -->" />
    <meta name="description" content="<!-- THE PAGE'S DESCRIPTION -->" />
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Stylesheets -->
    <!-- Normalize.css -->
    <link
      rel="stylesheet"
      href="https://necolas.github.io/normalize.css/8.0.1/normalize.css"
    />
    <!-- Bootstrap 4 -->
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
      integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh"
      crossorigin="anonymous"
    />
    <!-- Roboto & Roboto Mono Font -->
    <link
      href="https://fonts.googleapis.com/css?family=Roboto+Mono|Roboto:400,400i,700&display=swap"
      rel="stylesheet"
    />
    <!--     
      ADDITIONAL CSS LINKS HERE
      Example:
        <link rel="stylesheet" href="css/styles.css" />
    -->
  </head>
  <body>
    <div id="app">
      <!-- VISIBLE CONTENT -->
    </div>
    <!-- Javascripts -->
    <!-- JQuery (Required by Bootstrap) -->
    <script
      src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
      integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
      crossorigin="anonymous"
    ></script>
    <!-- Popper (Required by Bootstrap) -->
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
      integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
      crossorigin="anonymous"
    ></script>
    <!-- Bootstrap 4 -->
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
      integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
      crossorigin="anonymous"
    ></script>
    <!-- FontAwesome -->
    <script src="<!-- THE FONTAWESOME KIT -->" crossorigin="anonymous"></script>
    <!--
      ADDITIONAL JAVASCRIPT LINKS HERE
      Example:
        <script src="js/main.js" type="text/javascript"></script>
    -->
  </body>
</html>
```





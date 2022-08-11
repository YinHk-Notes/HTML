## `<meta></meta>`

```html
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```
The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.

<meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

Metadata will not be displayed on the page, but is machine parsable.

Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
  
  
| Attribute | Value | Description |
| --- | --- | --- |
| charset | character_set | Specifies the character encoding for the HTML document |
| content | text | Specifies the value associated with the http-equiv or name attribute |
| http-equiv | content-security-policycontent-typedefault-stylerefresh | Provides an HTTP header for the information/value of the content attribute |
| name | application-nameauthordescriptiongeneratorkeywordsviewport | Specifies a name for the metadata |

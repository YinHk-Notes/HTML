## head


The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag.

Metadata is data about the HTML document. Metadata is not displayed.

Metadata typically define the document title, character set, styles, scripts, and other meta information.

The following elements can go inside the <head> element:

- `<title>` (required in every HTML document)
- `<style>`
- `<base>`
- `<link>`
- `<meta>`
- `<script>`
- `<noscript>`

> The <link> tag is used to link to external resource
  
eg:
```
   <link rel="stylesheet" href="styles.css">
```
  
The <link> tag defines the relationship between the current document and an external resource.

The <link> tag is most often used to link to external style sheets or to add a favicon to your website.

The <link> element is an empty element, it contains attributes only
  

| Attribute | Value | Description |
| --- | --- | --- |
| crossorigin | anonymoususe-credentials | Specifies how the element handles cross-origin requests |
| href | URL | Specifies the location of the linked document |
| hreflang | language_code | Specifies the language of the text in the linked document |
| media | media_query | Specifies on what device the linked document will be displayed |
| referrerpolicy | no-referrerno-referrer-when-downgradeoriginorigin-when-cross-originunsafe-url | Specifies which referrer to use when fetching the resource |
| rel | alternateauthordns-prefetchhelpiconlicensenextpingbackpreconnectprefetchpreloadprerenderprevsearchstylesheet | Required. Specifies the relationship between the current document and the linked document |
| sizes | HeightxWidthany | Specifies the size of the linked resource. Only for rel="icon" |
| title |   | Defines a preferred or an alternate stylesheet |
| type | media_type | Specifies the media type of the linked document |
  

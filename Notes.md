# 9/19 PD w/ Aankit

HTML `<head>` vs. `<body>`

HTML document goes into a browser, is rendered, comes out as a "Document Object."

**Walk the Document Object Model**
- What is an object???
- Document --> Parents --> Children
- Tags --> Classes --> IDs

Need to find better metaphors for explaining _object_.
"An object is an instance of a class..."
Class: car
Object

**Typical HTML Page**

```html
<html>
  <head>

  </head>
  <body>
    <!-- JavaScript requires classes to select specific elements.  -->
    <p class="name">This is a child of the body.</p>
    <div id="another name">
      <p class="name">Another paragraph</p>
    </div>
  </body>
</html>
```

**Here's a thing we did, using [Aankit's page](http://www.aankit.com/)**
```javascript
document.getElementById("menu-item-198");
var menu_item = document.getElementById("menu-item-198");
menu_item
document.getElementById("menu-item-198").firstChild;
menu_item.innerHTML
menu_item.innerHTML="Pizza"
```
## Critical Concepts
- Dynamic vs. Static
- Event-driven vs. Procedural
- Asynchronous vs. synchronous
  - Callbacks - passing functions as parameters
  - Anonymous functions
- Variable Scope

## Goals for 11th Grade Front End
- Interactive pages 
- Integrating API's
- Understanding how to find documentation

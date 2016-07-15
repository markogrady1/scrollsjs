# scrollsJS
####ScrollsJS is a jquery plugin that enables you to have a built-in scroller that will take you smoothly to the top of the page.

**Implementation**
-
 Between `<head>` tags.
```html
<script src="https://code.jquery.com/jquery-1.10.2.js"></script>
<script src="/path-to/scrolls.js"></script>
```

Before ending `</body>` tag.
```javascript
<script>
  scroller.init();
</script>
```

If you wish to change the color of the scroller, simply create an object called `conf` and place it anywhere above the 
`scroller.init()` code. Like so.

```javascript
<script>
  var conf = {
	bgColor: "#4F8EF2",
	hoverColor: "#4EB441",
	opacity: 0.5
  };

  scroller.init();
</script>
```

You may change either the background color, hover color or opacity of the scroll button.

##Enjoy!!

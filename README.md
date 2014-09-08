popupimg
========

JQuery plugin for display images in full size

Need JQuery http://jquery.com/download/

#### 1. First need connect jquery.popupimg plugin

```html
<script src=”jquery.popupimg.js”></script>
```

#### 2. Initialization function for the desired element
```javascript
$(function() {
    $('img.popupimg').popupimg({
      'show': 600, // speed show animation
      'hide': 600 // speed hide animation
    });
});
```

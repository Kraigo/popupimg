popupimg
========

JQuery plugin for to display images in full size

*Need JQuery http://jquery.com/download/

#### 1. First need connect jquery.popupimg plugin

```bash
<script src=”jquery.popupimg.js”></script>
```

#### 2. Initialization function for the desired element
```bash
$(function() {
    $(‘img.popupimg’).popupimg({
      'show': 600, // speed show animation
      'hide': 600 // speed hide animation
    });
});
```

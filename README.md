
# Slack Dark Theme 

> C:\Users\l.reiner\AppData\Local\slack\app-3.3.3\resources\app.asar.unpacked\src\static\ssb-interop.js

```javascript
document.addEventListener('DOMContentLoaded', function() {
 $.ajax({
   url: 'https://raw.githubusercontent.com/lreiner/Slack-Dark-Theme/master/dark-theme.css',
   success: function(css) {
     $("<style></style>").appendTo('head').html(css);
   }
 });
});
```

```
#2d2d2d,#434745,#00D0FF,#00D0FF,#434745,#FFFFFF,#00d0ff,#DB6668
```

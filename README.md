
# Slack Dark Theme 

### 1. Search for ssb-interop.js 
> C:\Users\<USERNAME>\AppData\Local\slack\app-<VERSIONNUMBER>\resources\app.asar.unpacked\src\static\ssb-interop.js

### 2. Insert this on top of the file
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
### 3. Set this theme Variables in your Slack Settings
```
#2d2d2d,#434745,#00D0FF,#00D0FF,#434745,#FFFFFF,#00d0ff,#DB6668
```


# Slack Dark Theme 

```
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
#000000,#444A47,#00D0FF,#00D0FF,#434745,#FFFFFF,#00d0ff,#DB6668
```

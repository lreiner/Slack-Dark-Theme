document.addEventListener('DOMContentLoaded', function() {
 $.ajax({
   url: 'https://raw.githubusercontent.com/lreiner/Slack-Dark-Theme/master/dark-theme.css',
   success: function(css) {
     $("<style></style>").appendTo('head').html(css);
   }
 });
});
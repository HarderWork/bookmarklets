# Bookmarklets
Collection of useful (?) snippets to be referenced as Bookmarklets.
Create a bookmark (or edit an existing one, if you are in Safari on iOs) and paste the code below

## Dagens Nyheter
Remove front-end overlay for paywall protected articles
```
javascript: (function () { 
    var jsCode = document.createElement('script');
    jsCode.setAttribute('src', 'https://cdn.rawgit.com/HarderWork/bookmarklets/master/dagens_nyheter.js');
  document.body.appendChild(jsCode); 
 }());
 ```
 

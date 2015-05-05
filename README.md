# trelloBlur

Toggleable script to blur contents of Trello cards for screenshots.

#### Bookmarklet

Just add the bookmarklet below to your bookmarks bar.

```javascript
javascript:if($('.list-card-title').hasClass('blurTitle')){$('.list-card-title').css({"color":"black","text-shadow":"none"}).removeClass('blurTitle');}else{$('.list-card-title').css({"color":"transparent","text-shadow":"0 0 10px black"}).addClass('blurTitle');};void 0;)
```

```javascript
javascript:(function(){var el=document.createElement('script');el.src='https://zeman.github.io/perfmap/perfmap.js';document.body.appendChild(el);})();
```

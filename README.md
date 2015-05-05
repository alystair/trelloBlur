# trelloBlur
Toggleable Bookmarklet to blur contents of Trello cards for screenshots.

Drag the following link on to your bookmark bar to create a handy bookmarket!

[Trello Board Blur](javascript:if($('.list-card-title').hasClass('blurTitle')){$('.list-card-title').css({"color":"black","text-shadow":"none"}).removeClass('blurTitle');}else{$('.list-card-title').css({"color":"transparent","text-shadow":"0 0 10px black"}).addClass('blurTitle');};void 0;)
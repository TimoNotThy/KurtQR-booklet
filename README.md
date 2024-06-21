# KurtQR-booklet
Bookmarklet to use instead of scanning the QR-code for KURT. I made this because i found that scanning the QR-code and logging in on Toledo was too inefficient, with this bookmarklet I don't even have to type the link, only the ID.

## What is a bookmarklet?
A bookmarklet is a javascript function that you add to you bookmarks toolbar.

## Installation
Right click on your bookmarks toolbar and select `add bookmark`. Name it anything you want (or leave it empty so it's small) and paste the following in the URL-field:
```js
javascript:(()=>{window.location.replace("https://www.kuleuven.be/kurtqr?id=".concat(prompt("ID on the KurtQR link","300000")));})();
```
Tip: Holding control when clicking a bookmark/bookmarklet makes it open in a new tab instead of you current tab.

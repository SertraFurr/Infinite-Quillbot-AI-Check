# Infinite-Quillbot-AI-Check
Small chrome devtools script to bypass the daily limit of 10 check.

I won't explain much

1. open chrome devtools with ctrl+shift+I
2. Paste this
```js
localStorage.setItem('aidr_daily_scan_count', -9999999);

console.log('aidr_daily_scan_count =', localStorage.getItem('aidr_daily_scan_count'));

```
3. Press Enter!
4. Have fun checking AI for... I don't know what.


Wish to support me? ⭐Star this project⭐ !!

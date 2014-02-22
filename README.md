A normalized approach to hiding the address bar on iOS and Android
=======================

## iOS 7.1+ and special `meta` tag

From [Amazing Web aricle](http://theamazingweb.net/2013/12/19/minimal-ui-viewport-meta-tag/)

> With iOS 7.1 beta 2 Apple added a new viewport meta tag that allows us to minimize the top and bottom bars in Safari on the iPhone. It’ll be basically the same behaviour as if the user starts to scroll. In the past we had to do this with a little trick and trigger the behaviour with a 1px scroll when the page was loaded.

Add this to the top of the page in `head`

```
<meta name="viewport" content="minimal-ui">
```

---

Authored by @scottjehl

MIT License.

Read this article for explanation
http://24ways.org/2011/raising-the-bar-on-mobile

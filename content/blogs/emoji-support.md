---
title: "Emoji Support in Hugo"
date: 2021-04-03T22:53:58+05:30
draft: false
author: "Gurusabarish"
tags:
  - Emoji support
  - Smile
  - Emoji
image: /images/blogs/emoji.jpg
description: ""
toc: 
---
<a href="https://www.freepik.com/free-vector/comic-face-expressions-set_9649239.htm#query=emoji&position=7&from_view=search&track=sph">Image by pch.vector</a> on Freepik

Emoji can be enabled in a Hugo project in a number of ways. :zap:

## Emoji Support

The [emojify](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes).

To enable emoji globally, set ```enableEmoji``` to ```true``` in your site’s [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

<hr>

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.

```
.emoji {
  font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
}
```
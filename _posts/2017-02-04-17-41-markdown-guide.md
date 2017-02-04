---
layout: post
title: Markdown Guide
cover: cover.jpg
date:   2017-02-04 17:41:00
categories: posts
---
<p></p>
# Markdown Guide
<p></p>
### kramdown
<p></p>

To create a new post:
  * file name
    * (2000-01-01-00-00-default-temp.md)
  * front matter
    * \-\-\-
    * layout: post
    * title: Post Markdown Testing
    * cover: cover.jpg
    * date:   2000-01-01 00:00:00
    * categories: posts
    * \-\-\-
  * p html (un_glue content form cover img)
  * \# title h1
  * p html (un_glue content form cover img)
<p></p>

---

| use | | | text
|:-|:-|:-|:-
| use * | | | or _ before and after text for *italic*
| use ** | | | or __ before and after text for **bold**
| use \`` | | | before and after text for `emphasis` tags
| use \-\-\- | | | to create a line
| use \\ | | | to escape markdown special characters
| use number. | | | to create a ordered list

---
<p></p>

#### NOTE: avoid tables or create them on html, kramdown markdown is annoying creating tables.
<p></p>

### Blockquotes
(decoration is disabled but it will still render as a paragraph)
> This is a blockquote.

### Inline formatting
I want to wrap **this text** in a `strong` tag and *this text* in an `emphasis` tag.

### Links
I usually search using [Google](https://www.google.com "Google").

### Images
![LOGO](/images/logo.png)

object|width|height
:-|-:|-:
cover.jpg|734px|min50px
logo.png|128px|128px
oooooooooo|oooooooooo|oooooooooo

<p></p>
For more go to [kramdown](https://kramdown.gettalong.org/index.html)

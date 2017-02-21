---
layout: post
title: Markdown Guide
cover: guide.jpg
date:   2017-02-19 10:31:00
categories: posts
---

---
<p></p>

# Markdown Guide

### kramdown
<p></p>

Este guia existe, porque eu tenho por hábito esquecer-me do básico e permite-me testar edição.
This guide is here, because I tend to forget basic stuff and for testing reasons.

<p></p>

#### NOTE: for some reason lists are not working from github \-\-\'

[comment]: <> To create a new post:
[comment]: <>   + file name
[comment]: <>     + (2000-01-01-00-00-default-temp.md)
[comment]: <>   + front matter
[comment]: <>     + \-\-\-
[comment]: <>     + layout: post
[comment]: <>     + title: Post Markdown Testing
[comment]: <>     + cover: cover.jpg
[comment]: <>     + date:   2000-01-01 00:00:00
[comment]: <>     + categories: posts
[comment]: <>     + \-\-\-
[comment]: <>   + p html (un_glue content form cover img)
[comment]: <>   + \# title h1
[comment]: <>   + p html (un_glue content form cover img)

  <p></p>

---

<p></p>

---

| To create a new post |
|:-|
| file name |
| (2000-01-01-00-00-default-temp.md) |
| |
| front matter |
| \-\-\- |
| title: Post Markdown Testing |
| cover: cover.jpg |
| date:   2000-01-01 00:00:00 |
| categories: posts |
| \-\-\- |

---

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

NOTE: avoid tables or create them on html, kramdown markdown is annoying creating tables.

### Blockquotes (decoration is disabled but it will still render as a paragraph)
> This is a blockquote.

### Inline formatting
I want to wrap **this text** in a `strong` tag and *this text* in an `emphasis` tag.

### Links
I usually search using [Google](https://www.google.com "Google").

### Images
---
![cover](https://bottled-ant.github.io/UnSeen/images/cover.jpg)

<img src="https://bottled-ant.github.io/UnSeen/images/cover.jpg" alt="Cover" width="100%" height="auto">

object|width|height
:-|-:|-:
cover.jpg|734px|min50px
logo.png|128px|128px
oooooooooo|oooooooooo|oooooooooo

For more go to [kramdown](https://kramdown.gettalong.org/index.html)

---
layout: post
title: 'TwigPen oops 2'
---

An updated version of my previous post follows.  Executive summary: "Doh!"

-original below-

Oops! I forgot to `git pull origin master` the updated script from the [rssupdatepnut GitHub repo.](https://github.com/bazbt3/rssupdatepnut)

Here's the blog post announcing my tweeted notification of new blog posts: [http://bazbt3.10centuries.org/2018/03/04/twigpen](http://bazbt3.10centuries.org/2018/03/04/twigpen).

Daft Baz scratched head for a few minutes thinking the script'd failed for some techy reason.  No, simply PEBKAC.

Am I feeling lucky?

-original above-

It turns out I messed up here too, with the result below:

`$ python3.6 rssupdatepnut.py`

`  File "rssupdatepnut.py", line 81`

`    TwigPen.postsomething(pnut_message)`

`    ^`

`IndentationError: unexpected indent`

I'd better fix it then, instead of blogging about it!

+++
categories = ["Uncategorized"]
date = "2016-02-25T19:13:38-08:00"
description = ""
draft = "true"
tags = ["sample", "blogging", "cool"]
title = "Sample Post"

+++

This is a sample post to demonstrate all the cool stuff that can be put inside a post on this blog. This is written in markdown, so all markdown syntax works, obviously. Let's look at some notable things that can be done here.

Code looks like `cmd <opt>`. You can also write blocks of code like
```
#include<iostream>
using namespace std;

int main() {
  cout<<"Hello World!"<<endl;
  return 0;
}
```
You can also write long commands that automatically enables scroll
```
$ echo "super long command that takes arbitrary words as options for an executable called super to demonstrate that code blocks scroll and not wrap around"
```
And then this
{{< highlight bash >}}
$ echo "life is easier when you have syntax highlighting"
{{< /highlight >}}

Moving on, what's a blog post without images? Here's how to add images to a post, with several features enabled. Go figure.
<figure>
    <img data-action="zoom" src="/images/treeview.png" style="width:80%;"></img>
    <figcaption>TreeView and OptionList in action</figcaption>
</figure>

Of course it's possible to link the image (or its caption to another page).

I love Twitter, so gotta be able to embed tweets inside posts. Hugo shortcodes won't align the tweet to center, so just use the Twitter embed code for now. Make sure to use `class="twitter-tweet tw-align-center"` in the embed code.
<blockquote class="twitter-tweet tw-align-center" data-lang="en"><p lang="en" dir="ltr">Gif search means I can instantly tweet a gif of a kitten eating its tail. <a href="https://t.co/Bsvez00Nhe">pic.twitter.com/Bsvez00Nhe</a></p>&mdash; Nishant Totla (@nishanttotla) <a href="https://twitter.com/nishanttotla/status/702604796822364160">February 24, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

This is a foolproof method to embed any other content too, until I figure out a way create my own parametrized shortcodes.
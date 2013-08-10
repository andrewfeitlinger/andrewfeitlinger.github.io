---
layout: post
title:  Welcome to Jekyll
---

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com

---

# Markdown Practice (kramdown)
{:.no_toc}

Here are some footnotes using kramdown syntax.

The first footnote[^foot1] in a sentence.

The second footnote[^foot2] in another sentence.

[^foot1]: My first footnote. 

[^foot2]: My second footnote. 

---

And here is an example of a table of contents. (**TODO:** Add CSS Magic)

# Contents
{:.no_toc}

* TOC
{:toc}

# Chapter

text

## Section

text

### Subsection (configured to not diplay in TOC)

text

#### Subsubsection (configured to not diplay in TOC)

text

# Another Chapter

text

## Another Section

text

---

And here is a table combining kramdown syntax and some CSS magic.

|-----------------|-------------|-----------------|----------------|
| Default aligned | Left aligned| Center aligned  | Right aligned  |
| Second line     | a           | a               | a              |
|-----------------|:------------|:---------------:|---------------:|
| First body part | Second cell | Third cell      | Fourth cell    |
| Second line     | a           | a               | a              |
| Third line      | a           | a               | a              |
|-----------------|-------------|-----------------|----------------|
| Second body     | a           | a               | a              |
| Second line     | a           | a               | a              |
|-----------------|-------------|-----------------|----------------|
| Third body      | a           | a               | a              |
|=================|=============|=================|================|
| Footer row      | Footer row  | Footer row      | Footer row     |
| Second line     | a           | a               | a              |
|-----------------|-------------|-----------------|----------------|



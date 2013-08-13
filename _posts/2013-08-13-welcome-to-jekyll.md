---
layout:     post
title:      Welcome to Jekyll enhanced with CSS
published:  true
date:       2013-08-13  # last update
---

_The original post was included in the initial build and I ended up turning this into a sandbox._ 

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` or `--watch` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention:

    YYYY-MM-DD-name-of-post.extension

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

And with line numbers also:

{% highlight java linenos %}
/***********************
 * Hello World Program *
 ***********************/
public class HelloWorld
{
    public static void main(String[] args)
    {
        System.out.println("Hello World!");
    } // End Main
} // End Class
{% endhighlight %}


Check out the [Jekyll docs][jekyll]{:target="_blank"} for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh]{:target="_blank"}.

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]: http://jekyllrb.com

---

**Markdown Practice (kramdown)**

Here are some footnotes using [kramdown syntax](http://kramdown.rubyforge.org/syntax.html){:target="_blank"} and some CSS "Magic".

The first footnote[^foot1] in a sentence.

The second footnote[^foot2] in another sentence.

[^foot1]: My first footnote.

[^foot2]: My second footnote.

---

Here is an example of a table of contents combining kramdown syntax and more CSS "Magic".

**Contents**

* TOC
{:toc}

# Chapter

text

## Section

text

### Subsection (universally configured to not display in TOC)

text

### Subsection (universally configured to not display in TOC)

text

#### Subsubsection (universally configured to not display in TOC)

text

#### Subsubsection (universally configured to not display in TOC)

text

##### Subsubsubsection (universally configured to not display in TOC)

text

###### Subsubsubsubsection (universally configured to not display in TOC)

text

# Another Chapter

text

## Another Section

text

# Another Chapter (individually labeled to not display in TOC)
{:.no_toc}

text

## Another Section (individually labeled to not display in TOC)
{:.no_toc}

---

And here is a table combining kramdown syntax and even more CSS "Magic".

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

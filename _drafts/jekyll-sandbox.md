---
layout:     draft
title:      Welcome To My Jekyll Sandbox
published:  true
date:       2013-08-16
---

*This document originally started as an edit of the sample post created from the initial Jekyll build, but "inquisitively" evolved into something unexpectedly more interesting, involved, and indepth.*

*I moved this into the drafts section for right now. It is a work in progress. Changes are to be definitely expected.*

# Preface
{: .no_toc}

Hello and welcome to my Jekyll sandbox where I have been experimenting with YAML, Kramdown, Liquid, and CSS programming languages for the data serialization, lightweight markup, templating and presentation requirements of this website.

The `Contents` list (below) was originally an unordered `ul` formatted list created with Kramdown syntax `{: toc}`, but transformed into a multilevel ordered list using CSS counters. The individual headings (below the `Contents` list) are similarly numbered using CSS counter techniques.

The `Preface` heading (above) and the `Contents` heading (below) are both `H1` headings created with "atx style" Kramdown syntax `#`, but are neither included within the `Contents` list using Kramdown syntax `{: .no_toc}` nor numbered using CSS syntax `:not(.no_toc)`.

There are also numerous CSS elements being utilized on this page (and throughout the site). Most of which I figured out through [autodidacticism][]{:target="_blank"}. Please view my source code if you are interested in seeing what I have accomplished so far. I will probably/eventually properly license everything that I wrote/coded on my own under the MIT and/or Creative Commons Licenses.

[autodidacticism]: http://en.wikipedia.org/wiki/Autodidacticism "self-directed learning"

---

# Contents
{: .no_toc}

* TOC
{: toc}

---

# Code Blocks

## Without Line Numbers

### Liquid and CSS (Pygments)

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

### Kramdown, CSS (CodeRay), and CSS (Custom)

~~~
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
~~~
{: .language-ruby #coderay-noline}

## With Line Numbers

### Inline Style

#### Liquid and CSS (Pygments)

{% highlight ruby linenos %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

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

#### Kramdown and CSS (CodeRay)

~~~ ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
~~~

~~~ java
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
~~~

### Table Style

#### Liquid and CSS (Pygments)

{% highlight java linenos=table %}
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

#### Kramdown and CSS (CodeRay)

This can also be done, but is generated with a global setting. So either the noline and inline styles OR only the table style can be show.

`{::options coderay_line_numbers="nil" /}`

`{::options coderay_line_numbers="inline" /}`

`{::options coderay_line_numbers="table" /}`

---

# Footnotes

Here are some footnotes created using Kramdown and CSS.

The first footnote[^foot1] in a sentence.

The second footnote[^foot2] in another sentence.

[^foot1]: My first footnote.

[^foot2]: My second footnote.

---

# Tables

And here is a table created using Kramdown and more CSS.

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

---

*Footnote links (from above) will be listed down here at the bottom of the page. Clicking on the arrow links `↩` (below) will return you back to the original footnote line.*

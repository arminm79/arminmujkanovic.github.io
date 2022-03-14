---
layout: post
title:  "GIT Command Line Interface"
date:   2022-02-24 10:03:57 -0500
categories: git cli commands
---

Git Work Flow:
{% highlight ruby %}
Github

dir
CD arminmujkanovic@github.io or cd arminmujkanovic.github.io
git add .
git status
git commit -m “added new notes” ( example git commit -m "index.html file" or ... "name file"
git push

git status (all done)

atom .

bundle exec jekyll serve

{% endhighlight %}



You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Let show you committed how to work what is red and lightgreen
Make sure see to example

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        <red>modified:   README.md</red>
        This is mean error missing connection then you need to go try to find when you see green code. That is mean connection the link ATOM to Command Prompt.

{% highlight ruby %}
      "modified:"    "README.md" Red is mean missing connection
{% endhighlight %}

{% highlight ruby %}
      "modified:"    "README.md" Green is mean connection.
{% endhighlight %}

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[ruby-installer]: https://rubyinstaller.org
[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

<style type="text/css">

    .customHighlight {
        background-color: lightgreen;
    }

   </style>

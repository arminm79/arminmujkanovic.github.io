---
layout: post
title:  "Jekyll Installation Guide"
date:   2022-02-24 10:03:57 -0500
categories: jekyll installation
---

Instructions:
1. Install [RubyInstaller][ruby-installer] with default options
2. Open command prompt and run `gem install jekyll bundler`
3. check that Jekyll is installed `jekyll -v`
4. add jekyll to your github repository `jekyll new --skip-bundle .`
5. add bundle exec jekyll serve
6. Mostly use start first typing git name each ```word end```
7. How to make end or quit to press can work continue.



You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

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

---
title: new title
layout: post
author: test author
cover: "/img/featue-bg.jpg"
abstract: Summury/abstract goes here fgasjfgs vgsdugfks fyoasf sdyfoidsy fyoaiyfoayf
  oafad faiyfliaufo ayfoayfoiayf afadyfadifyoay ffoayfoadfyoia foayfoia foayf oa yf
  oafy aofy oayf oafyoayf afy aify aiofyoiafy afafyayf aflayfiayfl afoa yfoaify aoyfoyia
  foay foayf oafy aoify aofy aoffy aoif aof afo
tags:
- tag1
- other tag
- many more
math: true
---

## How to put linked text:

## This is done by listing below

Check out the [Jekyll][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

This link is done by [inline](https://www.google.com) method

{% comment %}
Just to include comment
---
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}

## Adding code:
<br>
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}


Also 


```html
<html>
  <head>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
```


### equation test:


block equation: \\[F_x'= \frac{F_x - \frac{v}{c^2}\vec{F}.\vec{u}}{1-\frac{u_xv}{c^2}}; \quad F_y'= \frac{F_y\sqrt{1-v^2/c^2}}{1-\frac{u_xv}{c^2}}; \quad F_z'= \frac{F_z\sqrt{1-v^2/c^2}}{1-\frac{u_xv}{c^2}}\\] 

inline test &nbsp; \\(p = \gamma mv \quad  \\) 

No laudem altera adolescens has, volumus lucilius eum no. Eam ei nulla audiam efficiantur. Suas affert per no, ei tale nibh sea. Sea ne magna harum, in denique scriptorem sea, cetero alienum tibique ei eos. Labores persequeris referrentur eos ei.

Link other [post]({% post_url 2021-05-07-interview-experiences %}) using liquid tag

{% comment %}
![train](/img/item-img1.jpg)
{% endcomment %}

<center>
<img src="{{ base_url }}/img/featue-bg.jpg" alt="image demo" height="50" width="50" >
</center>

or maybe like this

![info-of-image]({{ base_url }}/img/featue-bg.jpg)

### A possible way to Cite 
let's say, [1]
and more text ...


[1] [On the Electrodynamics of Moving Bodies](https://en.wikisource.org/wiki/Translation:On_the_Electrodynamics_of_Moving_Bodies){:target="_blank"}

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

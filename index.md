---
title: Home
---

{% include figure.html file="College_of_Education_University_of_Idaho_Workshop_scene_2273.jpg" alt="intro image here" width="75%" %}

# Workshop Template!

> hosted by [University of Idaho Library](http://www.lib.uidaho.edu/) {{ site.pub_year }}

Workshop abstract here.

Learn how to create a super quick easy website for a workshop by writing a few markdown files! 
Host it for free on GitHub with gh-pages, and share!
Fun!

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>

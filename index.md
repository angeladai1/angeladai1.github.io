---
layout: page
title: Home
---

Hello! Welcome to my internet space. I hope you enjoy your stay :) 

### Links to check out: 
- [About](https://angeladai1.github.io/about.html)
- [Resume](https://angeladai1.github.io/public/angela_dai_resume.pdf)
- [Projects](https://angeladai1.github.io/projects.html)


### Latest Blog Posts:
{% for post in site.posts %}
{{ post.date | date_to_string }} » [ {{ post.title }} ]({{ post.url }})
{% endfor %}
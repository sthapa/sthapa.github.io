---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

Hi, I'm Suchandra. I'm a developer with a varied background working mainly on 
distributed computing software in several languages (python, c++, go, etc.). This 
site is where I post articles about various things that I've worked on and which 
may be of interest to others.

## Blog posts

{% for post in site.posts %}   
   * [{{ post.title }}]({{ post.url }}): {{ post.excerpt  | strip_html }}
{% endfor %}

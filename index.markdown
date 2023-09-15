---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Random blog posts about how to do various development related tasks.  

## Blog posts

 {% for post in site.posts %}   
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://sthapa.github.io{{ post.url }}"></a></small></p>          
{% endfor %}

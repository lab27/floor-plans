---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
<h2><a href="index.html">&laquo; Go To Overview</a></h2>

# Links
<ul>
{% for page in site.data.floorplans-flatter %}
<li><a href="{{ page.title | datapage_url: 'pages' }}">{{page.title}}</a></li>
{% endfor %}
</ul>
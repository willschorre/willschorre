---
layout: home
title: art
---
<p> Art Pages </p>

<p>
<a href="/"> Back to all pages </a>
</p>

<div style="margin:auto; display: inline-block;">
    <div class="menu">
      {% for page in site.pages %}
      	{% if page.display == 'ya' %}
			{% for each in page.tag %}
	        	{% if page.tag == 'art' %}
	          		<div class="menu" > <a href="{{page.url}}">{{page.title}}</a> </div>
	        	{% endif %}
	    	{% endfor %}
	    {% endif %}
      {% endfor %}
	</div>

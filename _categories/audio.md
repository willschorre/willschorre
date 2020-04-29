---
layout: home
title: audio
---
<p> Audio Pages </p>


<div style="margin:auto; display: inline-block;">
	    <div class="menu">
	      {% for page in site.pages %}
	        {% if page.categories == 'audio' %}
	          <div class="menu" > <a href="{{page.url}}">{{page.title}}</a> </div>
	        {% endif %}
	      {% endfor %}
  	</div>
---
layout: home
title: electronics
---
<p> Electronics Pages </p>


<div style="margin:auto; display: inline-block;">
	    <div class="menu">
	      {% for page in site.pages %}
	        {% if page.category == 'electronics' %}
	          <div class="menu" > <a href="{{page.url}}">{{page.title}}</a> </div>
	        {% endif %}
	      {% endfor %}
  	</div>
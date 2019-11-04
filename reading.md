---
title: Assignmentts
layout: page
menuItem: Reading
menuPosition: 2
---
{% if site.docsUrl != "" %}
You can download all required reading in the [Study materials]({{ site.docsUrl }}) at the faculty website.
{% endif %}

There will be four assignments in all. Each assignments will include two components. 

<ol>
{% assign syllabus = (site.syllabus | sort: "week") %}
{% for week in syllabus %}
  <li>
  	<a href="{{ site.baseurl }}{{ week.url }}">{{ week.title }}</a> 
  	{% for tag in week.tags %}
  		<b>#{{ tag }}</b>
  	{% endfor %}
  	({{ week.day }})</li>
{% endfor %}
</ol>

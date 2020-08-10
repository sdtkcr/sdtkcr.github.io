---
layout: archive
permalink: /
---

<div class="page-lead" style="background-image:url(https://raw.githubusercontent.com/sdtkcr/sdtkcr.github.io/master/images/res1.jpeg); background-position: center top;
    background-repeat: no-repeat;
    background-attachment: fixed;
    text-align: center;
    color: #fff;
		height: 500px;">
	<!-- <div class="wrap page-lead-content">
		<h1>Skinny Bones</h1>
		<h2>Jump start your Jekyll site with something thin and light.</h2>
	</div>
	-->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

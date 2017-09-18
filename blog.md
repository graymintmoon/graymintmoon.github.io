---
layout: blank
title: Blog & Updates
---
<div class="row_md">
	<div class="container_md">
		<div class="page">
			<div class="text_center">
				<h1 class="text_charcoal page_title">BLOG <span class="page_title_second">&</span> <span class="page_title_third">UPDATES</span></h1>
				<h4 class="page_subtitle">Ideas and thoughts worth sharing</h4>
				<hr class="divider_red">
			</div>
		</div>
		<div class="row">
		{% for post in site.posts %}
			<article class="{% if forloop.first %}first{% elsif forloop.last %}last{% else %}middle{% endif %}">
			<div class="article-head">
				<h3 class="post_title"><a href=".{{ post.url }}/">{{ post.title }}</a></h3>
				<p class="date">{{ post.date | date: "%b %d, %Y" }}</p>
				</div><!--/.article-head-->
				<div class="article-content">
					{{ post.long_description }}
					<a href="/{{ post.url }}/" class="full-post-link js-pjax">Read more</a>
					</div><!--/.article-content-->
				</article>
				{% if forloop.last %}{% else %}<div class="separater"></div>{% endif %}
			{% endfor %}
		</div>
	</div>
</div>
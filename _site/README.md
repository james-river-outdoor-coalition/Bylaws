# Bylaws of James River Outdoor Coalition

<ul>
	<li>Article I - Members
		<ul>
			{% assign article-one = site.articles | where: "article","one" %}
			{% for article in article-one %}
			  <li><a href="{{ article.url }}">{{ article.name }}</a></li>
			{% endfor %}
		</ul>
	</li>
	<li>Article II - Meetings Of Members
		<ul>
			{% assign article-two = site.articles | where: "article","two" %}
			{% for article in article-two %}
			  <li><a href="{{ article.url }}">{{ article.name }}</a></li>
			{% endfor %}
		</ul>
	</li>
	<li>Article III - Officers
		<ul>
			{% assign article-three = site.articles | where: "article","three" %}
			{% for article in article-three %}
			  <li><a href="{{ article.url }}">{{ article.name }}</a></li>
			{% endfor %}
		</ul>
	</li>	
	{% assign article-five = site.articles | where: "article","five" %}
	{% for article in article-five %}
	  <li>Article V - <a href="{{ article.url }}">{{ article.name }}</a></li>
	{% endfor %}			
</ul>





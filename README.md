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
	<li>Article IV - Board Of Directors
		<ul>
			{% assign article-four = site.articles | where: "article","four" %}
			{% for article in article-four %}
			  <li><a href="{{ article.url }}">{{ article.name }}</a></li>
			{% endfor %}
		</ul>
	</li>		
	{% assign article-five = site.articles | where: "article","five" %}
	{% for article in article-five %}
	  <li>Article V - <a href="{{ article.url }}">{{ article.name }}</a></li>
	{% endfor %}			
	<li>Article VI - Committees
		<ul>
			{% assign article-six = site.articles | where: "article","six" %}
			{% for article in article-six %}
			  <li><a href="{{ article.url }}">{{ article.name }}</a></li>
			{% endfor %}
		</ul>
	</li>		
	{% assign article-seven = site.articles | where: "article","seven" %}
	{% for article in article-seven %}
	  <li>Article VI - <a href="{{ article.url }}">{{ article.name }}</a></li>
	{% endfor %}			
	{% assign article-eight = site.articles | where: "article","eight" %}
	{% for article in article-eight %}
	  <li>Article VI - <a href="{{ article.url }}">{{ article.name }}</a></li>
	{% endfor %}		
</ul>





{% for item in {{ site.url }}/items/ %}	
    <h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
{% endfor %} 

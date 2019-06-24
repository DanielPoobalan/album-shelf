## Albums

{% for album in site.data.albums %}
- [{{ album.title }} by {{ album.artist }}]({{ album.url }})
{% endfor %}


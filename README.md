django-endless-pagination-bootstrap-theme
=========================================

An bootstrap2 theme for [django-endless-pagination](https://github.com/frankban/django-endless-pagination).


Put **endless** into templates directory, then:

Change
```
{% show_pages %}
```
to
```
<div class="pagination">
{% show_pages %}
</div>
```
Change
```
{{ pages }}
```
to
```
<div class="pagination">
{{ pages }}
</div>
```    

![screenshot.png](https://github.com/mozillazg/django-endless-pagination-bootstrap-theme/raw/master/screenshot.png)

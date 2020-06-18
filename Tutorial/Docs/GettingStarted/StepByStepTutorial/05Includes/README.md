## [Includes](https://jekyllrb.com/docs/step-by-step/05-includes/)

Add navigation.  
Every page should have it so add it to `_layouts`.  

### Include tag

The `include` tag includes content from a file in `_includes`.  
Include is a repeat content fetched by a layout.  

### Include usage

Create `_includes/navigation.html`.  

Change `_layouts/default.html`.  

```
{% include navigation.html %}  # includes from `_includes`
```

### Current page highlighting

Use `page.url` to see where you are.  

```
<a href="/" {% if page.url == "/" %}style="color: red;"{% endif %}> Home </a>
```

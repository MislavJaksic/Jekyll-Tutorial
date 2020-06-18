## [Liquid](https://jekyllrb.com/docs/step-by-step/02-liquid/)

`Liquid` is a templating language.  

### Objects

Answer: where to do I output content?

```
{{ page.title }}
```

### Tags

`Tag`s create the logic and control flow for templates.  

```
{% if page.show_sidebar %}
  <div class="sidebar">
    sidebar content
  </div>
{% endif %}
```

### Filters

`Filter`s change the output of a `Liquid` `object`.  

```
{{ "hi" | capitalize }}
```

### Use Liquid

Apply what you learned to your project!  

```
...
<h1>{{ "Hello World!" | downcase }}</h1>
...
```

Add `Front Matter` to the top of the `index.html`.  

```
---
# front matter tells Jekyll to process Liquid
---
```

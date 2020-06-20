## [Deployment](https://jekyllrb.com/docs/step-by-step/10-deployment/)

### Gemfile

Create a `Gemfile`.  

Run `bundle install`. This will create `Gemfile.lock` which will lock the current `gem` version.  

Prefix all `jekyll` commands with `bundle exec` like `bundle exec jekyll serve`.  

### Plugins

Jekyll plugins create custom generated content.

The most widely used official plugins are:
* `jekyll-sitemap`: create a sitemap file to help search engines index content
* `jekyll-feed`: create an RSS feed for your posts
* `jekyll-seo-tag`: add meta tags to help with SEO

Add them to the `Gemfile` and `_config`.  

Run `bundle update`.  

Exit and then restart `bundle exec jekyll server`.  

### Environments

You might want to output something in production but not in development.   

Analytics scripts are the most common example of this.

Use environments when you want to deploy only into production and not development.  

```
$: JEKYLL_ENV=production bundle exec jekyll build
```

By default `JEKYLL_ENV` is `development` available through `jekyll.environment`.  

```
{% if jekyll.environment == "production" %}
  <script src="my-analytics-script.js"></script>
{% endif %}
```

### Deployment

Perform a production build.  

```
$: JEKYLL_ENV=production bundle exec jekyll build
```

Copy the contents of `_site` to your server.  

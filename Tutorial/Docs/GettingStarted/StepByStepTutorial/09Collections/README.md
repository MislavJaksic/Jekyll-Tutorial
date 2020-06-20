## [Collections](https://jekyllrb.com/docs/step-by-step/09-collections/)

Collections group posts.  

### Configuration

Jekyll collection configuration happens in `_config.yaml`.  

Create `_config.yaml`.  

Exit and then restart `bundle exec jekyll server`.  

### Add authors

Each collection has its own root folder, like `_authors`.  

Create `_authors/jill.md` and `_authors/ted.md`.  

### Staff page

Create `staff.html`.  

Create `_data/navigation.yaml`.  

### Output a page

Make a collection output a page for documents.  

Create `_config.yaml`.  

Exit and then restart `bundle exec jekyll server`.  

Create `staff.html`.  

Create `_layouts/author.html`.  

### Front matter defaults

You can set `Front Matter` defaults in `_config.yaml`.  

With defaults you can remove the `Front Matter` from all pages and posts.  

Exit and then restart `bundle exec jekyll server`.  

### List author’s posts

Create `_layouts/author.html`.  

###Link to authors page

Create `_layouts/post.html`.  

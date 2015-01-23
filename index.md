---
layout: page
title: Welcome to the N49 Developer Portal
---
##What is N49?
N49 is a leading local search and review management company. Our network of directories are a key part of the local eco system in Canada, the United States, and the United Kingdom. In addition to our directories we have a leading application for helping business owners acquire reviews from their customers and distribute them around the web, and to their own website.

##API's

N49 has two primary API's, the review feed API and the N49-Data API. The review feed API is used for the 

#### N49 Data API 
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.



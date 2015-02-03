---
layout: page
title: Welcome to the N49 Developer Portal
---
##What is N49?
N49 is a leading local search and review management company. Our network of directories are a key part of the [local search eco system in Canada](https://getlisted.org/static/resources/local_search_ecosystem_canada.pdf), the United States, and the United Kingdom. In addition to our directories we have a leading application for helping business owners acquire reviews from their customers and distribute them around the web, and to their own website.

##API's

N49 has two primary API's, the review feed API and the N49-Data API. The review feed API is used for the distribution of reviews to customer websites and it is required that you're a paying customer in order to get an API Key. Our Data-API lets app developers, media companies, or data providers push or pull from our database of reviews, and business information.

#### N49 Data API

[Our Data-API documentation](https://github.com/n49/N49-Data-Api-Documentation) is well defined in a github repository. If you have any questions or would like an API key don't hesitate to reach out. 
    
## Recent Updates

You can find answers to common questions about our products and API's here, including and updates or changes that should be noted.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




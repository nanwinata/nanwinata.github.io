---
layout: categories
categories: 
- tutorial
title: Politik 
---
<h1>{{ page.title }}</h1>
<div class="tags">
    {% assign sortedCategories = page.categories | sort %}
    {% for category in sortedCategories %}
        <span class="tag">
            <a href="/category/{{ category }}">#{{ tutorial }}</a>
        </span>
    {% endfor %}
</div>

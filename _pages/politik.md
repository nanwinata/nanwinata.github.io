---
layout: categories
categories: 
- politik
title: Politik 
---
            <div class="after-post-cats">
                <ul class="tags mb-4">
                    {% assign sortedCategories = page.categories | sort %}
                    {% for category in sortedCategories %}
                    <li>
                        <a class="smoothscroll" href="{{site.baseurl}}/categories#politik{{ category | replace: " ","-" }}">{{ category }}</a>
                    </li>
                    {% endfor %}
                </ul>
            </div>

---
categories:
- tutorial
title: Politik 
permalink: /politik
---
<!-- Post Categories -->
            <div class="after-post-cats">
                <ul class="tags mb-4">
                    {% assign sortedCategories = page.categories | sort %}
                    {% for category in sortedCategories %}
                    <li>
                        <a class="smoothscroll" href="{{site.baseurl}}/categories#{{ category | replace: " ","-" }}">{{ category }}</a>
                    </li>
                    {% endfor %}
                </ul>
            </div>
<!-- End Categories -->

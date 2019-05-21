---
layout: default
categories: politik
title: Politik 
---
            <!-- Post Categories -->
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
            <!-- End Categories -->

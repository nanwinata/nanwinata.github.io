---
layout: categories
title: Politik
permalink: /politik
---
<div class="after-post-tags">
                <ul class="tags">
                    {% assign sortedTags = page.tags | sort %}
                    {% for tag in sortedTags %}
                    <li>
                        <a class="smoothscroll" href="{{site.baseurl}}/categories#tutorial{{ tag | replace: " ","-" }}">#{{ tag }}</a>
                    </li>
                    {% endfor %}
                </ul>
            </div>

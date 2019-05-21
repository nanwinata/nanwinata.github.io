---
layout: tags
title: Tags
permalink: /tags
---
            <!-- Post Tags -->
            <div class="after-post-tags">
                <ul class="tags">
                    {% assign sortedTags = page.tags | sort %}
                    {% for tag in sortedTags %}
                    <li>
                        <a class="smoothscroll" href="{{site.baseurl}}/tags#{{ tag | replace: " ","-" }}">#{{ tag }}</a>
                    </li>
                    {% endfor %}
                </ul>
            </div>
            <!-- End Tags -->

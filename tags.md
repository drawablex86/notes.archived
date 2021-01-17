---
layout: post
title: Context Pages
permalink: /tags
content-type: eg
---

<main>
    {%- for item in site.notes -%}
    {%- if item.notetype == "context" -%}
    <div class="feed-title-excerpt-block disable-select" data-url="{{site.url}}{{item.url}}">
        <a href="{{item.url}}" style="text-decoration: none; color: #333333;">
        <p class="feed-title">{{ item.title }}</p>
        </a>
    </div>
    {%- endif -%}
    {%- endfor -%}
</main>

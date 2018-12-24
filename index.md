---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

## Who am I?
I'm Jesse Keating, a Datacenter Engineer with GitHub. When I'm not a the computer I like to do outdoorsy things, like biking (mountain, gravel, road, cyclocross, bar hopping, etc.), camping, climbing (indoor and out).

I'm also on Twitter as [@iamjkeating](https://twitter.com/iamjkeating).

## {{ page.list_title | default: "Posts" }}
<ul class="post-list">
    {%- for post in site.posts -%}
    <li>
    {%- assign date_format = "%b %-d, %Y" -%}
    <span class="post-meta">{{ post.date | date: date_format }}</span>
    <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
    </h3>
    </li>
    {%- endfor -%}
</ul>

Subscribe to posts via an [atom feed](/feed.xml)!

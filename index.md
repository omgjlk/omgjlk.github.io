---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

## Who am I?
I'm Jesse Keating, a Datacenter Engineer with GitHub. When I'm not a the computer I like to do outdoorsy things, like biking (mountain, gravel, road, cyclocross, bar hopping, etc.), camping, climbing (indoor and out).

I'm also on Twitter as [@iamjkeating](https://twitter.com/iamjkeating).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} {{ post.date }}</a>
    </li>
  {% endfor %}
</ul>

---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash
feature_row:
  - image_path: assets/images/clones-unsplash-square.jpg
    alt: "Symposium on Reproducibility in ML"
    title: "Symposium on Reproducibility in ML"
    excerpt: "Virtual symposium with talks and panel on reproducibility in machine learning research."
    url: "/events/reprod-symposium20"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/data-wallpaper-square.jpg
    alt: "First UCI ML Hackathon"
    title: "First UCI ML Hackathon"
    excerpt: "Virtual hackathon for UCI students on challenge datasets from the scientific community."
    url: "/events/hackathon20"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - excerpt: "more coming soon.."
---

# Welcome to the Community Portal for the UCI ML Repository

This website is the hub for the development plans and updates and community event highlights around the UCI’s machine learning repository.
See the [About](/about) page for more details.

## Upcoming Events

{% include feature_row %}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
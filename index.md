---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash
upcoming_row:
  - image_path: /assets/images/data-wallpaper-square.jpg
    alt: "3rd UCI ML Hackathon"
    title: "3rd UCI ML Hackathon"
    excerpt: "Virtual hackathon for UCI students on challenge datasets from the scientific community."
    url: "/events/hackathon22"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - excerpt: "more coming soon.."
past_row:
  - image_path: /assets/images/data-wallpaper-square.jpg
    alt: "2nd UCI ML Hackathon"
    title: "2nd UCI ML Hackathon"
    excerpt: "Virtual hackathon for UCI students on challenge datasets from the scientific community."
    url: "/events/hackathon21"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/clones-unsplash-square.jpg
    alt: "Symposium on Reproducibility in ML"
    title: "Symposium on Reproducibility in ML"
    excerpt: "Virtual symposium with talks and panel on reproducibility in machine learning research."
    url: "/events/reprod-symposium20"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/data-wallpaper-square.jpg
    alt: "1st UCI ML Hackathon"
    title: "1st UCI ML Hackathon"
    excerpt: "Virtual hackathon for UCI students on challenge datasets from the scientific community."
    url: "/events/hackathon20"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

# Welcome to the Community Portal for the UCI ML Repository

This website is the hub for the development plans and updates and community event highlights around the UCI’s machine learning repository.
See the [About](/about) page for more details.

## Upcoming Events

{% include feature_row id="upcoming_row" %}

## Past Events

{% include feature_row  id="past_row" %}

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
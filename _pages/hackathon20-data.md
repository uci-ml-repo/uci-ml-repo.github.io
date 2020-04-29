---
permalink: /events/hackathon20/datasets
toc: true
title: "UCI ML Hackathon: Challenge Datasets"
classes: narrow
toc_sticky: true
header:
  image: /assets/images/data-wallpaper-long.jpg
  caption: "Photo credit: [**Wallpaper Flare**](https://www.wallpaperflare.com/)"
datasets:
  gpa:
    contact_name: "Zhe Wang"  
    contact_email: "email"  
    short_name: "email"  
    long_name: "email"  
    description: "email"  
  gpa1:
    contact_name: "Zhe Wang2"  
    contact_email: "email"  
    short_name: "email"  
    long_name: "email"  
    description: "email"  
  gpa2:
    contact_name: "Zhe Wang3"  
    contact_email: "email"  
    short_name: "email"  
    long_name: "email"  
    description: "email"  

---

<div id="top"></div>

{% for dataset in page.datasets %}

  <h2 id="{{dataset[0]}}">{{dataset[1].short_name}}</h2>

  By {{dataset[1].contact_name}}


  [Email them](mailto:{{dataset[1].contact_email}})

  {{dataset[1].description}}


  [Back to top](#top)

{% endfor %}
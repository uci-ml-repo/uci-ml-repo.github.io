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
  wildfires:
    contact_name: "Casey Graff"  
    contact_email: "caseyagraff@gmail.com"  
    short_name: "California Wildfires"  
    long_name: "California Wildfires"  
    description: "(average year) ~50k instances, (all years) ~350k instances. Each instance is an image with multiple channels, each corresponding to a different feature (ground vegetation, observed fire detection, weather) and the target is a single channel image of the next day's fire detections."
    use_cases: "Image to Image Classification (binary classification per pixel of output image; similar to image segmentation)."

---

<div id="top"></div>

{% for dataset in page.datasets %}

  <h2 id="{{dataset[0]}}">{{dataset[1].short_name}}</h2>
  Description: {{dataset[1].long_name}}
  
  By {{dataset[1].contact_name}}
  

  [Email them](mailto:{{dataset[1].contact_email}})

  About: {{dataset[1].description}}
  
  Possible Applications: {{dataset[1].use_cases}}

  [Back to top](#top)

{% endfor %}

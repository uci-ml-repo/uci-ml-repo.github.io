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
    description: "(average year) ~50k instances, (all years) ~350k instances. Each instance is an image with multiple channels, each corresponding to a different feature (ground vegetation, observed fire detection, weather) and the target is a single channel image of the next day's fire detections"  
  galaxies:
    contact_name: "Wayne Hayes"  
    contact_email: "whayes@uci.edu"  
    short_name: "Galaxy Spiral Structure"  
    long_name: "Spiral Structure Analysis of 1 Million Sloan Galaxies"  
    description: "CSV file with description of 856,734 galaxies (+  header line), 338 features each"  
  gpa:
    contact_name: "Zhe Wang"  
    contact_email: "zwang15@uci.edu"  
    short_name: "GPA"  
    long_name: "Geometric Pose Affordance"  
    description: "Given 2D location of the person in image size, how do we get the 3d location of the person in root-relative coordinate (xyz location relative to pelvis joint). 
Number of Instance: training: 222,514, validation: 8,000,  testing: 82378
Type of data:  human keypoints position extract from image, in 2d (input), and 3d (output), also geometry information (multi-layer depth map) extracted from 2d joint location (input)"  

---

<div id="top"></div>

{% for dataset in page.datasets %}

  <h2 id="{{dataset[0]}}">{{dataset[1].short_name}}</h2>

  By {{dataset[1].contact_name}}


  [Email them](mailto:{{dataset[1].contact_email}})

  {{dataset[1].description}}


  [Back to top](#top)

{% endfor %}

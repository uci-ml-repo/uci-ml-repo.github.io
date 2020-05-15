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
  galaxies:
    contact_name: "Wayne Hayes"  
    contact_email: "whayes@uci.edu"  
    short_name: "Galaxy Spiral Structure"  
    long_name: "Spiral Structure Analysis of 1 Million Sloan Galaxies"  
    description: "CSV file with description of 856,734 galaxies (+  header line), 338 features each"
    use_cases: "Measuring the structure and evolution of galaxies; evolution of the Cosmos at large."
  gpa:
    contact_name: "Zhe Wang"  
    contact_email: "zwang15@uci.edu"  
    short_name: "GPA"  
    long_name: "Geometric Pose Affordance"  
    description: "Given 2D location of the person in image size, how do we get the 3d location of the person in root-relative coordinate (xyz location relative to pelvis joint). 
Number of Instance: training: 222,514, validation: 8,000,  testing: 82378
Type of data:  human keypoints position extract from image, in 2d (input), and 3d (output), also geometry information (multi-layer depth map) extracted from 2d joint location (input)."
    use_cases: "Motion-retarget in Adobe: https://sites.google.com/umich.edu/nik
Action recognition and explanation
Hollywood motion capture (3D Avatart), animation
Sports analysis (NBA, FIFA)
Health care (Autism, Parkinson, anthropometry physical rehabilitation)
robot learning (action anticipation, affordance learning, assist leaving)
self-driving cars (motion prediction)
Virtual reality (holelens2, facebook reality lab)
Amazon Go
Scene understanding and proxemics recognition"
  amyloid:
    contact_name: "Michael Lee"  
    contact_email: "mdlee@uci.edu"  
    short_name: "Amyloid Positivity"  
    long_name: "Clinical memory assessments and biomarkers associated with Alzheimer's Disease and Related Disorders"  
    description: "Tabular data with 939 cases of 19 variables. Each case is a clinical test of a patient. Variables involve demographic information (age, gender, years of education), protocol information (time since baseline test), memory test outcomes (free recall scores, recognition scores), biomarkers (APOE genotype, beta amyloid), and diagnosis of memory impairment (cognitively normal or impaired)."
    use_cases: "Prediction of amyloid status. Prediction of progression to cognitive impairment. Visualization of relationship between memory test performance, biomarkers, and demographics."
  dns:
    contact_name: "Zhou Li"  
    contact_email: "zhou.li@uci.edu"  
    short_name: "DNS network captures"  
    long_name: "DNS network captures"  
    description: "DNS data is often captured and used by security companies to find cyber-attacks. There are two pcap files consisting of millions of packets of DNS queries. A portion of them are benign, while others are malicious (e.g., flowing to a domains owned by cyber-attackers). The first one contains various kinds of DNS attacks. The second one contains DNS queries to many algorithm generated domains (Domain generation algorithms, DGA) from various family. DGA domains are often used as rendezvous points linked to command and control servers by malwares."
    use_cases: "The first dataset could be used to build detection system to identify various kind of network attacks based on DNS communication patterns. The second dataset could be used to build detection system to detect DGA domains."
  satellite:
    contact_name: "Daniel Parker"  
    contact_email: "dparker1@uci.edu"  
    short_name: "Satellite Imagery of Cambodia"  
    long_name: "Satellite imagery of Chbar Mon, Kampong Speu, Cambodia"  
    description: "These are raster data (satellite images)."
    use_cases: "Classify the images according to some simple land types, including: urban, rice fields, other agricultural fields, water, buildings, houses, etc."
  clinical:
    contact_name: "Alessandro Ghigi, Zhaoxian Hu, Wu Fu"  
    contact_email: "aghigi@hs.uci.edu"  
    short_name: "UCI Clinical Data"  
    long_name: "UCI OMOP DeID database"  
    description: "DeID clinical data related to 800,000 patients and 15,000,000 visits. Available clinical information: encounters, conditions (diagnoses), procedures, measurements (lab tests and vital signs), drugs, observations."
    use_cases: "Feasibility studies, clinical projects that can run against DeID data."
    
---

<div id="top"></div>

{% for dataset in page.datasets %}

  <h2 id="{{dataset[0]}}">{{dataset[1].short_name}}</h2>
  _{{dataset[1].long_name}}_
  
  Donated by: **{{dataset[1].contact_name}}**
  ([email](mailto:{{dataset[1].contact_email}}))

  {{dataset[1].description}}
  
  **Possible Applications:** {{dataset[1].use_cases}}

  [&#94; top](#top)

{% endfor %}

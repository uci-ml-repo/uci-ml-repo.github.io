---
permalink: /events/hackathon21/datasets
toc: true
title: "UCI ML Hackathon: Challenge Datasets"
classes: narrow
toc_sticky: true
header:
  image: /assets/images/data-wallpaper-long.jpg
  caption: "Photo credit: [**Wallpaper Flare**](https://www.wallpaperflare.com/)"
datasets:
  climate:
    contact_name: "Shane Coffield"  
    contact_email: "scoffiel@uci.edu"  
    short_name: "Climate change and ecosystem carbon in California"  
    long_name: "Climate change and ecosystem carbon in California"  
    description: "This is a fairly small dataset of 2258 points representing 2258 latitude/longitude gridcells in California (a 1/8 degree or 12.5km spatial resolution). The data are tabular (CSV) format, with each row representing one gridcell on the map. There are columns for latitude; longitude; 8 climate variables: 4 seasons of mean daily temperature (deg C) and 4 seasons of mean daily precipitation (mm/day); aboveground live carbon density (ton carbon per hectare); dominant vegetation type (1 for shrub or grass, 2 for forest). There are also 6 files with 6 different future (2090s) climate scenarios: extreme RCP8.5 warming vs moderate RCP4.5 warming and either dry, mean, or wet moisture scenarios. For more details and links to the original data, see the readme file."
    use_cases: "Understanding how ecosystems are connected to climate and might respond to climate change is a major topic of research in Earth System Science, especially because plants can help mitigate climate change. During photosynthesis, plants take carbon out of the atmosphere, and some of that carbon ends up stored in their aboveground biomass (tree trunks are about 50% carbon) or in the soil. This makes them a 'natural climate solution', so long as the ecosystems are stable and that carbon is withheld from the atmosphere for a long time. 

This dataset could be used (1) to help understand the climatic controls on ecosystems - that is, how seasonal patterns of temperature and precipitation help determine how much vegetation can exist at a location and how much carbon can be stored - and (2) to make future projections of how much carbon we would expect to be stored at different locations under different climate scenarios.  As Earth System Scientists we want to know whether it's realistic to expect increased carbon uptake by the land over this century to help mitigate climate change. We also want to know whether changes in temperature or precipitation are going to be more critical for determining future carbon storage, and to quantify uncertainty of any projections. With this dataset we could gain general scientific insight about the relationships between temperature, precipitation, and carbon, and identify patterns of vulnerability. In other words, be wary of overfitting models, and strive for interpretability. "
  yelp:
    contact_name: "Jiacen Xu"  
    contact_email: "jiacenx@uci.edu"  
    short_name: "YelpNYC"  
    long_name: "Yelp reviews of New York City"  
    description: "Yelp NYC dataset contains Yelp reviews for restaurants located in New York City. It has 160,255 users, 923 products and 359,052 reviews. So a User-Review-Product graph can be constructed which has 520,230 nodes and 718,144 edges."
    use_cases: "The goal is to classify the reviews is fake or not."
  covidlies:
    contact_name: "Robert Logan"  
    contact_email: "rlogan@uci.edu"  
    short_name: "COVIDLies"  
    long_name: "A Dataset for Detecting COVID-19-Related Misinformation on Social Media"  
    description: "COVIDLies is a dataset of 62 common misconceptions about the COVID-19 along with 6,591 related tweets, identified and annotated by researchers from the UCI School of Medicine. Given a tweet, our data identifies whether any of the known misconceptions are expressed by the tweet, and if so, whether the tweet propagates the misconception (agree/pos), is informative by contradicting it (disagree/neg), or is neither misinformative nor informative (no stance/na).

NOTE: More data may be added to the dataset before the start of the hackathon."
    use_cases: "Content moderation on social media platforms, evaluation of stance detection systems, analysis of linguistic patterns in informative/misinformative tweets."
  deid:
    contact_name: "Alessandro Ghigi, Zhaoxian Hu"  
    contact_email: "aghigi@hs.uci.edu; huzhx@uci.edu"  
    short_name: "UCI DeID OMOP Clinical Data Warehouse"  
    long_name: "UCI DeID OMOP Clinical Data Warehouse"  
    description: "A fully anonymized copy of the UCI Health Clinical Data Warehouse that contains most structured EHR data for all UCI Health patients. The dataset is refreshed monthly. No IRB is required for research use. Available clinical information: encounters, conditions (diagnoses), procedures, measurements (lab tests and vital signs), drugs, observations."
    use_cases: "Feasibility studies, clinical projects that can run against DeID data."
  cords:
    contact_name: "Alessandro Ghigi, Zhaoxian Hu"  
    contact_email: "aghigi@hs.uci.edu; huzhx@uci.edu"  
    short_name: "UC COvid Research Data Set (UC CORDS)"  
    long_name: "UC COvid Research Data Set (UC CORDS)"  
    description: "UC CORDS is a HIPAA Limited Data Set comprised of EHR data across the five UC medical campuses associated with individuals tested for COVID. The dataset is refreshed weekly. No IRB is required for research use. Available clinical information: encounters, conditions (diagnoses), procedures, measurements (lab tests and vital signs), drugs, observations."
    use_cases: "Feasibility studies, clinical projects about COVID."
  ncats:
    contact_name: "Alessandro Ghigi, Zhaoxian Hu"  
    contact_email: "aghigi@hs.uci.edu; huzhx@uci.edu"  
    short_name: "NCATS National Covid Cohort Collaborative (N3C) Data"  
    long_name: "NCATS National Covid Cohort Collaborative (N3C) Data"  
    description: "A centralized national data resource that the research community can use to study COVID-19. It is by far “the largest collection of EHR data on COVID-19 patients in the world."
    use_cases: "Feasibility studies, clinical projects about COVID-19."
  nih:
    contact_name: "Alessandro Ghigi, Zhaoxian Hu"  
    contact_email: "aghigi@hs.uci.edu; huzhx@uci.edu"  
    short_name: "NIH All of Us Research Data"  
    long_name: "NIH All of Us Research Data"  
    description: "One of the largest biomedical data resources from a diverse cohort of one million or more participants nationwide. Current data available include health and lifestyle surveys, physical measurements, and electronic health records."
    use_cases: "Feasibility studies, clinical projects."
  edge:
    contact_name: "Wayne Hayes"  
    contact_email: "whayes@uci.edu"  
    short_name: "Edge Prediction"  
    long_name: "Prediction of missing edges in network data"  
    description: "This network represents a recent, high-quality, experimentally-determined biological network of the interactions between proteins in a human cell. Each node is one type of protein, with an edge between two proteins if they are known to interact. Detecting such interactions in the lab is very expensive and error-prone (at least $100 per edge detection with current technology), but the network has many potential clinical applications. Thus, reliable computational prediction of new edges can potentially save money and eventually, lives. This dataset contains graphlet-based topological information that allows the prediction of new edges based on current edges. There are over 150,000 features for each and every pair of nodes (there are 9,000 nodes, giving about 40.5 million pairs), but not every feature exists for every pair. Thus, the dataset is sparsely represented. There are 10 folds, with pre-computed features for each. Users should NOT attempt their own folds, since the features must be computed independently for each fold--the same pair of nodes may have different features sets and values in different folds. Each fold consists of a training set and test set, and the training set actually *includes* the node pairs in the test set, but with a false value for the edge. So technically this problem involves detecting false-negative edges in the training set, with the test set of known actual edges being the comparison."
    use_cases: "For now edge prediction is relatively novel field, but since networks are used to represent a wide variety of data the technique has wide potential application."
  
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

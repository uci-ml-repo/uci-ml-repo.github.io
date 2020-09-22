---
permalink: /events/reprod-symposium20/
redirect_from: /events/symposium/
title: "UCI Symposium on Reproducibility in Machine Learning"
# toc: true
# classes: narrow
# toc_sticky: true
header:
    image: /assets/images/clones-unsplash-long.jpg
    caption: "Photo credit: [Jørgen Håland](https://unsplash.com/@jhaland?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/4yOgRb_b_i4)"
speakers:
    kcranmer:
        name: Kyle Cranmer
        affiliation: New York University
        title: "Reusable Workflows, active learning, and simulation-based inference"
        abstract: "I will describe how two of my passions (machine learning and reproducible workflows) unexpectedly came together. In the context of particle physics, reproducibility is a serious challenge as the data analysis for a typical paper involves large teams working with heterogeneous software environments and loosely connected, informal workflows. However, reproducibility is not a particularly high priority for most physicists. Instead, we emphasized use cases that focused on reusing those workflows to answer new questions, and developed the REANA reproducible research data analysis platform to provide the needed functionality. Now we are developing APIs around these workflows and putting machine learning tools on top. For instance, we have active learning algorithms querying black box functions that are implemented by these workflows. Similarly, we use workflows to wrap complex simulation chains, which provide a causal, generative model with an intractable likelihood. Our recent work on likelihood-free inference (or simulation-based inference), which uses deep learning, leverages these workflows and raises new research questions when viewed holistically."
        bio: "Kyle Cranmer is a Professor of Physics and Data Science at New York University. He is an experimental particle physicists working, primarily, on the Large Hadron Collider, based in Geneva, Switzerland. Professor Cranmer obtained his Ph.D. in Physics from the University of Wisconsin-Madison in 2005 and his B.A. in Mathematics and Physics from Rice University. He was awarded the Presidential Early Career Award for Science and Engineering in 2007 and the National Science Foundation's Career Award in 2009. Professor Cranmer developed a framework that enables collaborative statistical modeling, which was used extensively for the discovery of the Higgs boson in July, 2012. His current interests are at the intersection of physics, statistics, and machine learning."
        website: http://theoryandpractice.org/
        image: /assets/images/reprod_symp20/kcranmer.jpg
    pliang:
        name: Percy Liang
        affiliation: Stanford University and CodaLab
        title: "CodaLab: A Platform for Efficient Collaborative Research"
        abstract: "We are interested in solving two infrastructural problems in data-centric fields such as machine learning: First, an inordinate amount of time is spent on preprocessing datasets, getting other people's code to run, writing evaluation/visualization scripts, with much of this effort duplicated across different research groups.  Second, a only static set of final results are ever published, leaving it up to the reader to guess how the various methods would fare in unreported scenarios.  I will present CodaLab, a new platform which aims to tackle these two problems by creating an online community around sharing and executing immutable components called bundles, thereby streamlining the research process."
        bio: "Percy Liang is an Associate Professor of Computer Science at Stanford University (B.S. from MIT, 2004; Ph.D. from UC Berkeley, 2011).  His two research goals are (i) to make machine learning more robust, fair, and interpretable; and (ii) to make computers easier to communicate with through natural language.  His awards include the Presidential Early Career Award for Scientists and Engineers (2019), IJCAI Computers and Thought Award (2016), an NSF CAREER Award (2016), a Sloan Research Fellowship (2015), and a Microsoft Research Faculty Fellowship (2014)."
        website: https://cs.stanford.edu/~pliang/
        image: /assets/images/reprod_symp20/pliang.jpg
    mpaganini:
        name: Michela Paganini
        affiliation: Facebook Research
        title: "Reproducible Science of Deep Learning: The Pruning Case Study"
        abstract: I will present the practice of neural network pruning as both a practical engineering intervention to reduce model size and a scientific tool to investigate the behavior and trainability of compressed models. By pruning away units or connections, it is possible to test hypotheses on the role of substructures and pathways towards feature formation and information propagation in neural networks. I will argue that a fundamental scientific understanding of the inner workings of neural networks is necessary to build a path towards robust, efficient AI, and I will introduce open-source work that has facilitated the investigation of the behavior of pruned models. I will highlight examples such as the contribution of centralized, reusable pruning methods in PyTorch and the open-sourcing of the `dagger` framework for reproducible and reusable experiment orchestration, to demonstrate how the desire for reproducibility in the context of pruning research (where complex multi-stage experiment pipelines are common) begets robust, shared experiment tools.
        bio: Michela is a Postdoctoral Researcher at Facebook AI Research (FAIR) in Menlo Park and an affiliate at Lawrence Berkeley National Lab. She joined Facebook in 2018, after earning a Ph.D. in physics from Yale University. During her graduate studies, she worked on the design, development, and deployment of deep learning algorithms for the ATLAS experiment at CERN, with a focus on computer vision and generative modeling for particle discovery and scientific simulation. Prior to that, she graduated from the University of California, Berkeley with B.A.'s in physics and astrophysics. Her current research focuses on empirically characterizing neural network properties and dynamics in the over-parametrized and under-parametrized regimes using pruning as a tool for model compression. Michela has a broad interest in the science of deep learning, towards developing a fundamental understanding of the inner workings of deep models through rigorous investigation and hypothesis testing, using tools and methodologies from the physical sciences. 
        website: https://mickypaganini.github.io/
        image: /assets/images/reprod_symp20/mpaganini.jpg
    jvanschoren:
        name: Joaquin Vanschoren
        affiliation: Eindhoven University of Technology and OpenML
        title: Sharing and reproducing machine learning experiments with OpenML
        abstract: Sharing machine learning experiments in a reproducible way is a lot of work. However, what if we could automatically track every detail of our experiments and share them together with our results? OpenML is an open online platform where one cannot only share datasets, but also entire machine experiments. It has integrations into many machine learning libraries so that experiments run with these libraries are automatically shared in a fully reproducible way. This also means that the shared experiments can be used in many innovative ways. This talk will cover what is possible today, our experiences with making experiments reproducible, as well as open problems and future plans.
        bio: "Joaquin Vanschoren is Assistant Professor in Machine Learning at the Eindhoven University of Technology. His research focuses on machine learning, meta-learning, and understanding and automating learning. He founded and leads OpenML.org, an open science platform for reproducible machine learning. He received several demo and open data awards, has been tutorial speaker at NeurIPS and ECMLPKDD, and invited speaker at ECDA, StatComp, AutoML@ICML, CiML@NIPS, DEEM@SIGMOD, AutoML@PRICAI, MLOSS@NIPS, and many other occasions. He co-organizes the AutoML and meta-learning workshop series at NIPS and ICML and is co-editor of the book ’Automatic Machine Learning: Methods, Systems, Challenges’."
        website: https://joaquinvanschoren.github.io/
        image: /assets/images/reprod_symp20/jvanschoren.jpg
---


Please join us online for a half-day symposium on the topic of reproducibility in machine learning. 
The event will consist of 4 invited talks plus a panel discussion from thought-leaders in this area.

This event will be streamed live, with ability to ask and upvote questions during the talks.

Please fill-in the following short registration form for information purposes: [Registration Form](https://forms.gle/rBbvVKQr1rRPDGxe9)

<div class="notice notice--info">
  <h4>Live Streaming</h4>
  <p>Click here for live stream of the event: <a href="{{ site.url }}{{ site.baseurl }}/events/reprod-symposium20/live">Live stream</a>.</p>
</div>

## Dates

**Tuesday, September 22, 2020.**

9am to 1pm PT, [your timezone](https://time.is/0900AM_22_Sept_2020_in_PT?UCI_ML_Reproducibility_Symposium)

## Schedule

| Start 	| End   	| Person             	| Topic           	|
|-------	|-------	|--------------------	|-----------------	|
| 9:00  	| 9:15  	| -                  	| Opening Remarks 	|
| 9:15  	| 10:00 	| **{{ page.speakers.pliang.name}}** | [{{ page.speakers.pliang.title}}](#pliang) |
| 10:00  	| 10:45 	| **{{ page.speakers.kcranmer.name}}** | [{{ page.speakers.kcranmer.title}}](#kcranmer) |
| 10:45 	| 11:00 	| -                  	| Break           	|
| 11:00  	| 11:45 	| **{{ page.speakers.mpaganini.name}}** | [{{ page.speakers.mpaganini.title}}](#mpaganini) |
| 11:45  	| 12:30 	| **{{ page.speakers.jvanschoren.name}}** | [{{ page.speakers.jvanschoren.title}}](#jvanschoren) |
| 12:30 	| 1:00  	|                    	| Panel: **{{ page.speakers.kcranmer.name}}**, **{{ page.speakers.pliang.name}}**, **{{ page.speakers.mpaganini.name}}**, **{{ page.speakers.jvanschoren.name}}**	|

## Invited Speakers

<div>
{% for speaker in page.speakers %}
    <h3 id="{{speaker[0]}}">{{speaker[1].name}}</h3>
    {{speaker[1].affiliation}}, <a href="{{speaker[1].website}}" class="btn btn">Website</a>    
    <div>
    <p><b>{{speaker[1].title}}</b></p>
    <img class="align-left" width="125px" src="{{ site.url }}{{ site.baseurl }}{{ speaker[1].image }}">
    <p><i>{{speaker[1].abstract | markdowify}}</i></p>
    <p><b>Bio:</b> {{speaker[1].bio}}</p>
    <p><a href="#schedule">Back to schedule</a></p>
    </div>
    <hr>
{% endfor %}
</div>

## Organizers

<div>
<p>
<img class="align-left" width="125px" src="{{ site.url }}{{ site.baseurl }}/assets/images/sameer-singh.jpg">
<b>Sameer Singh</b><br/>
<i>Asst. Professor, Computer Science</i><br>
<a href="http://sameersingh.org" class="btn btn">Website</a>
</p>
</div>
<div>
<p>
<img class="align-left" width="125px" src="{{ site.url }}{{ site.baseurl }}/assets/images/padhraic-smyth.jpg">
<b>Padhraic Smyth</b><br/>
<i>Chancellor's Professor, Computer Science</i><br>
<a href="https://www.ics.uci.edu/~smyth/" class="btn">Website</a>
</p>
</div>

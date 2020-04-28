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
    vstodden:
        name: Victoria Stodden
        affiliation: Univ of Illinois, Urbana-Champaign
        title: Coming soon
        abstract: Coming soon
        bio: Coming soon
        website: http://stodden.net/
        image: /assets/images/reprod_symp20/vstodden.jpg
    jvanschoren:
        name: Joachim Vanschoren
        affiliation: Eindhoven University of Technology and OpenML
        title: Coming soon
        abstract: Coming soon
        bio: Coming soon
        website: https://joaquinvanschoren.github.io/
        image: /assets/images/reprod_symp20/jvanschoren.jpg
---

This event will be streamed live (link will be available on this website), with ability to ask and upvote questions during the talks, which we will ask the speakers.

More details coming soon!

## Dates

June 10th, 2020
9am to 1pm PT, [other timezones](https://www.timeanddate.com/worldclock/converter.html?iso=20200529T160000&p1=840&p2=179&p3=136)

## Schedule

_Subject to change_

| Start 	| End   	| Person             	| Topic           	|
|-------	|-------	|--------------------	|-----------------	|
| 9:00  	| 9:15  	| -                  	| Opening Remarks 	|
| 9:15  	| 10:00 	| **{{ page.speakers.kcranmer.name}}** | [{{ page.speakers.kcranmer.title}}](#kcranmer) |
| 10:00  	| 10:45 	| **{{ page.speakers.pliang.name}}** | [{{ page.speakers.pliang.title}}](#pliang) |
| 10:45 	| 11:00 	| -                  	| Break           	|
| 11:00  	| 11:45 	| **{{ page.speakers.vstodden.name}}** | [{{ page.speakers.vstodden.title}}](#vstoden) |
| 11:45  	| 12:30 	| **{{ page.speakers.jvanschoren.name}}** | [{{ page.speakers.jvanschoren.title}}](#jvanschoren) |
| 12:30 	| 1:00  	|                    	| Panel           	|

## Invited Speakers

<div>
{% for speaker in page.speakers %}
    <h3 id="{{speaker[0]}}">{{speaker[1].name}}</h3>
    {{speaker[1].affiliation}}, <a href="{{speaker[1].website}}" class="btn btn">Website</a>    
    <div>
    <p><b>{{speaker[1].title}}</b></p>
    <img class="align-left" width="125px" src="{{ site.url }}{{ site.baseurl }}{{ speaker[1].image }}">
    <p><i>{{speaker[1].abstract}}</i></p>
    <p><b>Bio:</b> {{speaker[1].bio}}</p>
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

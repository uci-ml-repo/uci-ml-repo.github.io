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
        title: "Reproducibility Matters Even If Models Can Discriminate Perfectly Between Chihuahuas and Blueberry Muffins"
        abstract: "My goal in this talk is to motivative a principled connection between reproducibility and Machine Learning, and show how this connection suggests a new set of fundamental ML research questions. Starting from a counterfactual - suppose a trained model achieves perfect prediction on the test data - brings into focus two rationales for reproducibility 1) methodological and scientific: evaluating expected model performance on extrapolated data; comparing and benchmarking model performance; assessing model refinements and changes to the training set; and assessing software implementation and computational system impact on model prediction performance; and 2) ethical: computational transparency; model interpretability; efficiency and productivity. I will present work that demonstrates the value and importance of these rationales in practice. AIM, an Abstraction for Improving Machine Learning, is a novel structure leveraging reproducibility for assessing winners in ML tournaments such as Kaggle and CodaLab Competitions. AIM presents a structured delivery of the ML pipeline to enable the direct evaluation, comparison, and re-use of defined workflow steps. AIM is demonstrated on the famous leukemia classification dataset (Golub '99) to illustrate the connection between ML and reproducibility."
        bio: |
            VICTORIA STODDEN is an Associate Professor in the School of Information Sciences at the University of Illinois at Urbana Champaign, with affiliate appointments in the Departments of Statistics and Computer Science, the School of Law, and the National Center for Supercomputer Applications. She received a Ph.D. in Statistics from Stanford University and a Law Degree from Stanford Law School. She graduated magna cum laude with her Bachelor’s in Economics from the University of Ottawa and holds a master’s degree in Economics from the University of British Columbia. She held the Kauffman Innovation fellowship at Yale Law School and was a Berkman Klein fellow at Harvard Law School. She was a postdoctoral researcher at MIT and has held faculty positions at the University of California, Berkeley and Columbia University, before accepting a tenured position at the University of Illinois at Urbana Champaign.<br>
            Stodden is an internationally recognized leader in improving the reliability of scientific results in the face of increasingly sophisticated computational approaches to research: understanding when and how inferences from data are valid and reproducible, what it means to have replicated a result, the effect of big data and computation on scientific inference, the design and implementation of scientific validation systems, standards of openness and transparency for data and code sharing, and resolving legal and policy barriers to disseminating reproducible research.<br>
            She has published more than 50 papers in scientific journals and conference proceedings, and has co-edited two professional books, published in 2014, Privacy, Big Data, and the Public Good: Frameworks for Engagement, published by Cambridge University Press and Implementing Reproducible Research, published by Taylor & Francis.<br>
            In 2009 she won the Access to Knowledge Kaltura prize for her publication on legal issues in reproducible research and scientific innovation. She serves on the Advisory Committee for the National Academy of Engineering Online Ethics Center for Ethics Education in Engineering and Science, and has served on the National Academies of Science, Engineering, and Medicine committees: “Reproducibility and Replication in Science” and “Fostering Research Integrity” and the NASEM Roundtable on "Data Science Post-Secondary Education." She co-chaired the National Science Foundation Advisory Committee for Cyberinfrastructure and was a member of the National Science Foundation Directorate for Computer and Information Science and Engineering (CISE) Advisory Committee. She has been quoted in The Economist (2013) and interviewed by publications such as Nature (2016) on research reproducibility.<br>
            She also testified on scientific reproducibility before the Congressional House Committee on Science, Space and Technology for the March 5, 2013 hearing on Scientific Integrity & Transparency.<br>
            She is PI on NSF awards #1941443 EAGER: Reproducibility and Cyberinfrastructure for Computational and Data-Enabled Science, and #1839010: EAGER: Preserve/Destroy Decisions for Simulation Data in Computational Physics and Beyond; and she is co-PI on the NSF award #1541450: CC*DNI DIBBS: Merging Science and Cyberinfrastructure Pathways: The Whole Tale. Her website is <a href="https://stodden.net">https://stodden.net</a>.
        website: http://stodden.net/
        image: /assets/images/reprod_symp20/vstodden.jpg
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

Please fill-in the following short registration form if interested in the event: [Registration Form](https://forms.gle/rBbvVKQr1rRPDGxe9)

## Dates

**June 10th, 2020**

9am to 1pm PT, [your timezone](https://time.is/0900AM_10_June_2020_in_PT?UCI_ML_Reproducibility_Symposium)

## Schedule

_Subject to change_

| Start 	| End   	| Person             	| Topic           	|
|-------	|-------	|--------------------	|-----------------	|
| 9:00  	| 9:15  	| -                  	| Opening Remarks 	|
| 9:15  	| 10:00 	| **{{ page.speakers.kcranmer.name}}** | [{{ page.speakers.kcranmer.title}}](#kcranmer) |
| 10:00  	| 10:45 	| **{{ page.speakers.pliang.name}}** | [{{ page.speakers.pliang.title}}](#pliang) |
| 10:45 	| 11:00 	| -                  	| Break           	|
| 11:00  	| 11:45 	| **{{ page.speakers.vstodden.name}}** | [{{ page.speakers.vstodden.title}}](#vstodden) |
| 11:45  	| 12:30 	| **{{ page.speakers.jvanschoren.name}}** | [{{ page.speakers.jvanschoren.title}}](#jvanschoren) |
| 12:30 	| 1:00  	|                    	| Panel: **{{ page.speakers.kcranmer.name}}**, **{{ page.speakers.vstodden.name}}**, **{{ page.speakers.jvanschoren.name}}**	|

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

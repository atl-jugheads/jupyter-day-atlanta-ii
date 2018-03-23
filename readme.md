
![](https://user-images.githubusercontent.com/4236275/35634953-fb4a3eb6-067a-11e8-81f7-8f06fcf0b052.png)


# Jupyter Day Atlanta II 

March 31, 2018 @ [Georgia Tech Research Institute](https://gtri.gatech.edu/) in Atlanta

---



## About

Jupyter Day Atlanta is a single-day conference for Jupyter users in the Southeast.  The [Atlanta
Jupyter User Group](https://www.meetup.com/Atlanta-Jupyter-User-Group/) is excited to host this event to showcase applications
of the open source software created by Project Jupyter and community. These interactive technologies
are reshaping how people interact with code and data in both industry and academia.  

Jupyter Day Atlanta is a chance for Jupyter users of all experience levels to share and learn about 
the state-of-the-art in open source scientific computing. This event is inspired by
[past and future events](docs/events.md) hosted by the Jupyter community, and hopes to connect
people across the Southeast including Atlanta, Athens, Raleigh, Columbia, Charlotte, and more.


Make plans to join us at the [GTRI Conference Center](https://gtri.gatech.edu/) in the heart of Atlanta
on March 31. 



# Important Dates

* [Call for Participation](https://docs.google.com/forms/d/e/1FAIpQLSeUJfyYnmsDtswuFanajOpAbAl_E4Ib6LsgM1fMk6Y42ZCf2w/viewform) Closes: __March 16, 2018__
* Speakers notified: __March 19, 2018__





## Morning session

* 9:00am - 9:15am — Registration with ☕️ & 🍩 from Project Jupyter
* 9:15am - 10am — Panel on Readability, Reusability, and Reproducibility
* 10am - 12pm — Invited Talks
* 12pm - 1pm — Lunch provided by O'Reilly Media

## Afternoon session

* 1pm - 1:40pm - Post Lunch Talk
* Breakout sessions

    * 1:40pm - 4:00pm Interacting and Collaborating with Jupyter
    * 1:40pm - 4:00pm Jupyter for Business and Science

* 4-4:15pm  — More ☕️ provided by Project Jupyter
* 4:15pm - 5:00pm - Featured Talk
* 5:00pm - 5:30pm — Town Hall and Closing Remarks



{% for i, _ in speakers.iterrows() %}{% set name=mapping[_['Your name or a site (e.g. twitter, github) handle.']]%}{{name}} {% if _['Job Title'] %}- {{_['Job Title']}} {% endif %} @ {{_['Affiliation']}}: {{_['Title']}}

{% endfor %}

# Invited Talks


## STEAM Workshops with Binder and JupyterHub


> [Carol Willing](https://twitter.com/WillingCarol) - _Research Software Engineer_  @ **[Project Jupyter](https://jupyter.org)**


Middle School and High School students can learn by doing. Jupyter Notebooks and the rich Python ecosystem with libraries on a variety of topics can engage many learners of the sciences and humanities. Interactive content, using Jupyter Widgets and visualization libraries, put the student in charge of manipulating content and extending their learning. Giving students engaging content in familiar subjects encourages them to develop and use computational skills to build upon their interests.

One difficulty of teaching workshops is access to computers and the ability to install software on those systems. This talk will demonstrate how a workshop organizer or teacher can deploy JupyterHub easily for a class using the Zero to JupyterHub Guide, Kubernetes, and Cloud Services. Even if students only have access to smartphones, tablets, or shared computers, a workshop can be held using Binder which allows a notebook environment to be served at the click of a button to any modern web browser.

## Human-in-the-loop with Jupyter notebooks


> [Paco Nathan](https://twitter.com/pacoid) - _Evil Mad Scientist_  @ **[O'Reilly Media](https://www.oreilly.com/learning)**


Imagine you have a few million documents, where sometimes the term `react` gets used to describe a JavaScript library, then sometimes it describes what people do during interviews. Even after parsing documents with the latest NLP libraries, "disambiguation" of overloaded terms is a hard problem.

One way to disambiguate terms in documents uses *active learning* for a *human-in-the-loop* approach.  While both "active learning" and "human-in-the-loop" have multiple meanings, this usage is about semi-supervised machine learning. It's a great technique to have in your toolkit when you want to prepare data for use at scale, such as preparing data sets for deep learning.

This talk will show an overview of active learning, how it's being used in industry.  While tooling can be expensive, we took an open source approach at O'Reilly Media based on Jupyter notebooks, nbformat, pandas, scikit-learn.  If all goes well, we'll include a live demo.

## Give a Little Bit of Your Notebooks to Me


> [Peter Parente](https://github.com/parente)  @ **Valassis Digital by day, Jupyter by night**


You've written an awesome notebook. It tells a great story, looks beautiful, and runs flawlessly. How do you share your pride and joy? Come and learn about some Jupyter tools that help make your work accessible to the masses.

There's so much that we need to share
So send a smile (& notebook) and show you care

## Just how hard is it to drive a car with a camera?


> [Stephen Welch](https://twitter.com/stephencwelch) - _Senior Engineer, Machine Learning_  @ **[Wheego Technologies, Welch labs](http://www.welchlabs.com/)**


In this talk, we'll use the Jupyter notebook to take a data-based approach to this question. Using real driving data and real algorithms in the notebook, we'll get as close as we can to the unique historical and modern approaches to this deep and compelling problem.

## Reproducible Segmentation of Not-Quite-Objects in Jupyter Notebooks


> [Shannon Quinn](https://twitter.com/SpectralFilter) - _Assistant Professor_  @ **[University of Georgia](http://cobweb.cs.uga.edu/~squinn/)**


A fundamental concept in computer vision is the process of segmenting an object of interest out from within an image or sequence of images. This process is difficult under the best of circumstances; in our case, we are interested not in single objects but rather a collection of deformable objects. Motile cilia are microscopic, hair-like structures that protrude from cells and beat in synchrony to move particulates and irritants away and bring nutrients in. Cilia line the exterior of cells in nearly every part of the body; as such, diseases that affect cilia and their ability to beat properly can have myriad and severe consequences on the patient's health. To that end, studying the motion of cilia is important to better understand the pathologies of these diseases. In this talk, we'll discuss some of the basics of object segmentation, and how many of the basic assumptions are violated in circumstances such as identifying cilia in a video. We'll look at live demonstrations of alternative segmentation approaches that can be used on diffuse motion patterns such as those created by moving cilia, using Jupyter notebooks and ipywidgets to create a beginner-friendly walkthrough of the basics of ciliary motion analysis and segmentation methods.




# Accepted Talks


## Accelerated Deep Learning with PyTorch


> [Wafa Louhichi](https://www.linkedin.com/in/wafa-louhichi-61520a10a/) - _Graduate Student_  @ **[Georgia Institute of Technology](https://www.gatech.edu/)**


Numpy and Jupyter notebooks are now a de-facto standard for data science. But what if we have a bigger problem to tackle? This tutorial introduces PyTorch, a Numpy-like library for deep learning that is being developed at Facebook. Along with a CPU-based NumPy back-end, PyTorch allows you to use GPU back-end without any knowledge of CUDA or other low level frameworks and languages. With PyTorch, advancing science from your web browser is fast and easy as never before! In our short tutorial we’re going to show you how to use PyTorch for regular data analytics tasks, how it’s different from Numpy, and how to train a neural network on a toy image classification dataset like MNIST or CIFAR-10. Finally, we show you how we used PyTorch to solve a real problem right at the intersection of Business and Science, namely, training a classifier to determine smooth or rough surface finish in metal parts manufactured on a CNC machine, all within the comfort of a Jupyter Notebook.

## The Markovian Birdsong Notebook


> [David Nicholson](https://github.com/NickleDave) - _post-doctoral fellow_  @ **Emory University**


Birdsong obeys a syntax, much like speech. To study this syntax, scientists label the elements of birdsong, known as syllables, producing strings of characters that can be modeled just like any other text. One common model applied to birdsong is a first-order Markov model: essentially a transition matrix containing the probabilities of transitioning from one character to any other in a sequence. Researchers have shown that such a model cannot capture the statistics of song for some bird species. These results demonstrate long time-scale dependencies in song that first-order Markov processes cannot reproduce, and imply that the songbird brain does more than simply flip a coin as it transitions between syllables. A recent study reported that using partially-observable Markov models with adaptation (POMMA) can reproduce the statistics of label sequences for one songbird species, the Bengalese finch. In this demo,  I show how I was able to reproduce in a single Jupyter notebook the results of this study. I apply the model to two publicly-shared repositories of labeled Bengalese finch song, including one from our lab. My results confirm that the model successfully describes the syntax of many individual Bengalese finches' songs but also reveals cases where alternative models may be a better fit. I present these results as a case study in reproducibility, to show how Jupyter can drive research forward by allowing editors, reviewers, and readers to interact with the results presented in any scientific study.

## Using Clojure in Jupyter 


> [Jeffrey Cummings](https://github.com/JeffAtAtl) - _Sr Developer and Data Engineer_  @ **AT&T/Insight Global**


This will be a live demo of how I added Clojure as a kernel (using existing plugin, clojupyter) and use cases on what it can be used for

## Achieving Reproducible and Deployable Data Science Workflows


> [John Patanian](https://github.com/JPatanian) - _Principal Data Scientist_  @ **General Electric**


Data science projects, especially those intended for production deployments, are often segmented into a ad-hoc discovery phase and production phase more akin to traditional software development.  

Within a group of data scientists, for collaboration purposes there are many benefits to using a standardized project structure, such as ease of review and the ability to automate and standardize model deployment. 

This presentation will demonstrate the use of Jupyter notebooks as part of a templatized, reproducible, and deployable workflow. Participants will learn to use the Cookiecutter templating framework, how to templatize notebooks and deployment artifacts through demonstration of amachine learning model development pipeline involving notebooks, GitHub and Docker.

## Journey Upstream: An Oral History of Jupyter


> [Nick Bollweg](https://github.com/bollwyvl) - _Software Developer_  @ **[Project Jupyter](https://jupyter.org)**


Two centuries ago, Lewis and Clark set out from St. Louis with $2,500 and 33 volunteers to map an uncharted continent. Along the way, they received aid, trade, and shelter from the folk who called this wilderness home. The Corps of Discovery returned with notebooks full of geographic, scientific, and cultural data. The journey to Jupyter started with 259 lines of Python in 2001... and is hardly over yet! In this talk, we'll map the code and community that supports IPython, the Notebook, and the upcoming JupyterLab, and look at some of the discoveries along the way.




## Breakout Sessions

### Interacting and Collaborating in Jupyter

In this session, the audience will learn about the core Jupyter
architecture (e.g. messaging, kernels) and subprojects (e.g. Notebook, JupyterHub, JupyterLab, ipywidgets, nbconvert).  


### Jupyter for Science

A favorite of Jupyter Day Atlanta 2016 the Jupyter for Science track will host a session demonstrating
the broad topics that scientists and engineers explore with Jupyter notebooks.



# [Code of Conduct][coc]

All participants, including speakers, must follow our [__Atlanta Jupyter Day Code of Conduct__][coc], the core of which is
this: __Atlanta Jupyter Day__ should be a safe and productive environment for everyone.

[coc]: conduct/code_of_conduct.md



# Sponsors

[![](http://www.southeastlinuxfest.org/wp-content/uploads/2014/06/ORM_logo_box1_cmyk.jpg)](https://www.oreilly.com/)
[![](https://raw.githubusercontent.com/jupyter/design/master/logos/Rectangle%20Logo/rectanglelogo-greytext-orangebody-greymoons/rectanglelogo-greytext-orangebody-greymoons.png)](https://jupyter.org)
[![](https://upload.wikimedia.org/wikipedia/en/1/1e/GTRI_Logo_2011.png)](https://gtri.gatech.edu/)



# Meetup Partners

The Atlanta Jupyter Group is an extension of [PyData Atlanta](https://www.meetup.com/PyData-Atlanta/) and the greater technology community 
in Atlanta.  We are excited to partner with these meetups.

[![](https://secure.meetupstatic.com/photos/event/2/7/2/8/global_452170024.jpeg)](https://www.meetup.com/PyData-Atlanta/)
[![](https://i.vimeocdn.com/portrait/5895081_600x600.webp)](https://www.meetup.com/Data-Science-ATL/)
## [<img style="display:inline" src="https://pbs.twimg.com/profile_images/780503095499452418/7YYwrvXr_400x400.jpg"/> PyData Triangle](https://www.meetup.com/PyData-Triangle/ "PyData Triangle")



<style>
a:link {
    color: #F37626;
    font-weight: normal !important;
}
button {
    color: white;
    background-color: #F37626;
}
button.btn-sm {
    font-size: 1em;
    padding: .25em;
    border-radius: .1em;
    width: 50%;
    border: 0;
}

button.btn-lg {
    font-size: 2em;
    padding: .5em;
    border-radius: .1em;
    width: 100%;
    border: 0;
}

a:hover {
    font-weight: normal !important;
}
</style>


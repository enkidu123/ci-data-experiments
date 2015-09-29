ci-data-experiments
===================
Playing around with Channel Island Open Data

Introduction
------------
The contents of this repo are an experiment started during the Jersey 2015 Health Hackathon
from http://hackjsy.com.

Inside, you will find some [Jupyter](http://jupyter.org) notebooks that begin to explore some of the
Open Data available in the Channel Islands (primarily from http://data.gg at this stage).


Aims
----
We are starting to see Open Data starting to be released, in usable electronic formats.
It would be disastrous if these datasets remain untouched.
This experiment is about:
- making sure that local Open Data is actually used
- helping people understand some of the tools available to work with the data
- identifying problems or limitations with existing Open Data datasets
- encouraging the release of _more_ Open Data

**There is no expectation of producing important scientific research!**
This is about awareness, and providing people with tools.


The notebooks
-------------
One of the reasons for choosing to host the notebooks on Github is that it has
[built in functionality to display Jupyter notebooks](https://github.com/blog/1995-github-jupyter-notebooks-3)!
This means that you require **no special software** to view the latest verion of a notebook. 

You can view the notebooks directly in the browser:

(Be warned - these are in very draft form and **probably contain errors!!!**)

[data-gg-health-concerns.ipynb](https://github.com/enkidu123/ci-data-experiments/blob/master/notebooks/data-gg-health-concerns.ipynb)
:	Examines the Chest and Heart screening data from http://data.gg.
:	The data is highly summarized, but a clear trend is identified in the limited data.

[data-gg-emissions-types.ipynb](https://github.com/enkidu123/ci-data-experiments/blob/master/notebooks/data-gg-emissions-types.ipynb)
:	Exploring Guernsey's record on Greenhouse gas emissions.
:	Guernsey's _per capita_ emissions are compared against an equivalent dataset from the USA.

[data-un-life-expectancy.ipynb](https://github.com/enkidu123/ci-data-experiments/blob/master/notebooks/data-un-life-expectancy.ipynb)
:	Looking for some larger datasets to work with, we draw on some UN data to compare national
    income against life expectancy around the world.

[data-gg-traffic-injuries.ipynb](https://github.com/enkidu123/ci-data-experiments/blob/master/notebooks/data-gg-traffic-injuries.ipynb)
:	Another dataset from http://data.gg - clearly displaying traffic accident injuries by type.
:	The limited population and dataset size makes it difficult to go much further.

[data-je-population.ipynb](https://github.com/enkidu123/ci-data-experiments/blob/master/notebooks/data-je-population.ipynb)
:	A first attempt at trying to get some Jersey data in - ended up having to OCR pages
	from a PDF report!
	Nothing of interest here yet, but hopefully more Jersey data is on its way soon...


Why Jupyter?
------------
- free!
- powerful tool, with incredible flexibility at the programming language level
- straightforward to get up-and-running with simple analyses
- well-established in a number of fields
- undergoing active development and significant funding
- notebook servers can run locally, or as a hosted service (wakari.io, Azure Machine Learning Studio) 


Why github?
-----------
Github is incredibly effective for allowing people to collaborate on _code_ to produce
excellent software products.

As the data analyses in these notebooks are "just code", why not try treating them as such,
and allow transparent collaboration to verify, fix and improve the analysis.

There are various roles that may become involved in an analysis, eg:
 - a **coder** can develop, fix or optimize computational aspects of the analysis
 - a **statistician** can offer robust reasoning on the data, and suggest valid statistical
   techniques to apply to substantiate arguments
 - a **domain expert** can provide context to an analysis, that is often lacking from data alone; 
   they may also suggest additional data that could be incorporated
 - anyone with **basic mathematical and computer skills** can download the notebooks and
   run and tweak the analyses themselves, or apply similar techniques to other datasets
 - an interested **layperson** can read the analysis


What's next?
------------
I don't know.
I will update these notebooks when I get the chance, and more data becomes available.
I welcome contributions, corrections, suggestions and hearing about your own analyses!
 

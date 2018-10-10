---
title       : Introduction to Reproducibility
subtitle    : 
author      : Natalie Thurlby
job         : Jean Golding Institute
logo        : askjgi-logo.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow   # 
url:
  lib: ../../librariesNew
  assets: ../../assets
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---




# Reproducible research

Activity.

---

## What is reproducibility?

__Reproducible:__ Your research is reproducible if other people get the same results running the same analysis on your data.

__Replicabile:__ Your research replicates if other people repeat the experiment and their results are consistent with yours. 

Being reproducible is a prerequisite for being replicable; at a minimum your work should be reproducible. Good practices in data analysis will help you with both (and there are lots of other upsides to them which we'll discuss later).

---

## Reproducibility crisis

Less than 40% of replications of well-known Psychology studies had significant results:

<center><img src="../../presentations/assets/img/reproducibility-intro/psychology-replication-paper.jpg" height=300></center>
<font size = 2 >"Open Science Collaboration. "Estimating the reproducibility of psychological science." Science 349.6251 (2015): aac4716.
"</font>

Only 11% of replications of well-known cancer biology studies had significant results. 

<font size = 2 >Begley, C. Glenn, and Lee M. Ellis. "Drug development: Raise standards for preclinical cancer research." Nature 483.7391 (2012): 531.</font>

---

## Most researchers think there is a problem

<center><img src="../../presentations/assets/img/reproducibility-intro/is-there-a-crisis.jpeg" height=400></center>
<center><font size = 2 >_Baker, Monya. "1,500 scientists lift the lid on reproducibility." Nature News 533.7604 (2016): 452_</font></center>

---

## The key challenge in data science

"Ask yourselves, what problem have you solved, ever, that was worth solving, where you knew all of the given information in advance? Where you didn't have a surplus of information and have to filter it out, or you didn't have insufficient information and have to go find some?"

<img src="../../assets/img/01_DataScientistToolbox/meyer.jpg" height=100 /> [Dan Myer, Mathematics Educator](http://www.ted.com/talks/dan_meyer_math_curriculum_makeover.html)

[The key word in data science is not data; it is science](http://simplystatistics.org/2013/12/12/the-key-word-in-data-science-is-not-data-it-is-science/)

---

## About us

<center> <font color="#CD3278">Data intensive</font> statistics in <font color="#008B45">biology and medicine</font></center>

* Brian Caffo 
  * Website [http://www.bcaffo.com/](http://www.bcaffo.com/)
  * Twitter [@bcaffo](https://twitter.com/bcaffo) 
  * Github [https://github.com/bcaffo](https://github.com/bcaffo)
* Jeff Leek 
  * Website [http://biostat.jhsph.edu/~jleek/](http://biostat.jhsph.edu/~jleek/), [http://simplystatistics.org/](http://simplystatistics.org/)
  * Twitter [@jtleek](https://twitter.com/jtleek) 
  * Github [https://github.com/jtleek](https://github.com/jtleek)
* Roger Peng
  * Website [http://www.biostat.jhsph.edu/~rpeng/](http://www.biostat.jhsph.edu/~rpeng/),[http://simplystatistics.org/](http://simplystatistics.org/)
  * Twitter [@rdpeng](https://twitter.com/rdpeng) 
  * Github [https://github.com/rdpeng](https://github.com/rdpeng)

---


## Why data science?

<img class=center src="../../assets/img/01_DataScientistToolbox/deluge.jpeg" height=400 />

[http://www.economist.com/node/15579717](http://www.economist.com/node/15579717)


---

## Why data science?

<img class=center src="../../assets/img/01_DataScientistToolbox/mckinsey.png" height=400 />

[http://www.mckinsey.com/insights/business_technology/big_data_the_next_frontier_for_innovation](http://www.mckinsey.com/insights/business_technology/big_data_the_next_frontier_for_innovation)

--- 

## Why statistical data science?

<img class=center src="../../assets/img/01_DataScientistToolbox/nytimes.png" height=400 />

[http://www.nytimes.com/2009/08/06/technology/06stats.html?_r=0](http://www.nytimes.com/2009/08/06/technology/06stats.html?_r=0)



---

## Why are you lucky?

<img class=center src="../../assets/img/01_DataScientistToolbox/bezos.jpg" height=400 />


---

## Why are you lucky?

<img class=center src=../../assets/img/01_DataScientistToolbox/heritage.png height=400 />

[Heritage Health Prize](http://www.heritagehealthprize.com/c/hhp)


---

## Why R? 

 <img class=center height=400 src=../../assets/img/01_DataScientistToolbox/nytimesr.png />

[http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html?pagewanted=all](http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html?pagewanted=all)

---

## Why R? 

* It is free
* It has a comprehensive set of packages
  * Data access
  * Data cleaning
  * Analysis
  * Data reporting
* It has one of the best development environments - Rstudio [http://www.rstudio.com/](http://www.rstudio.com/)
* It has an amazing ecosystem of developers
* Packages are easy to install and "play nicely together"



---

## Who is a data scientist?


<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/morey.jpeg />
[Daryl Morey](http://en.wikipedia.org/wiki/Daryl_Morey)


---

## Who is a data scientist?

<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/mason.jpeg />
[Hilary Mason](http://www.hilarymason.com/)


---

## Who is a data scientist?

<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/koller.jpeg />

[Daphne Koller](http://ai.stanford.edu/~koller/)


---

## Who is a data scientist?

 <img class=center height=400 src=../../assets/img/01_DataScientistToolbox/silver.jpeg />

[Nate Silver](http://fivethirtyeight.blogs.nytimes.com/)


---

## Our goal

 <img class=center height=400 src=../../assets/img/01_DataScientistToolbox/venn.png />



[Drew Conway](http://www.drewconway.com/zia/?p=2378)


---

## Plus jobs

<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/datajobs.png />

[http://radar.oreilly.com/2011/09/building-data-science-teams.html](http://radar.oreilly.com/2011/09/building-data-science-teams.html)

---

## This course

* Introducing you to the track
* Getting tools set up
* Giving you basic background

---
layout: best_practices_symposium
title:  "Best practices in data analysis and statistics symposium"
---
## [Best practices in data analysis and statistics symposium](index.html)

The program is not final, expect to see some changes.

The talks will be 15 minutes long, and the discussions will be practically unlimited.

Some of the talk materials will be available on [OSF Meetings](https://osf.io/view/bestpracticessymposium2017/).

### Program

#### Session 1: Analysis tools


__Best tools and practices for collaborative open research__

_Tamás Nagy (Eötvös Loránd University, Department of Personality and Health Psychology)_

Open research may become the standard practice for several fields of science in the future. This means that not only the resulting publications are published in open access journals, but all research documents and tools – like the study protocol, data, and analysis scripts – are made public. This can grant extra visibility to the research, promoting scientific collaboration, boosting citations, and granting quick access to practitioners, lawmakers, and the public.

Managing an open research project requires tools and practices that promote a real-time, cloud based collaboration. Fortunately, several IT tools have been created for this purpose, and most of them are free. In this presentation, I am going to introduce tools and an optimal workflow that can aid the creation and management of open research projects. The tools correspond to four key areas of a research project: 1) file sharing and version control, 2) data analysis, 3) team communication, and 4) project management. I am going to demonstrate how to integrate these tools into a workflow in an ongoing open research project.

__Combining the power of R and Python: using Jupyter Notebook for data analysis__

_Ádám Markója (Learning & Memory Research Group, Department of Cognitive Science, Budapest University of Technology and Economics)_

When we want to choose a programming language as a well-powered tool to analyse our data  we face with a high amount of „Python versus R” debates. The aim of my presentation is not to extend the long line of debates, rather to introduce how to combine the best features of these two programming languages.

Jupyter Notebook (former IPython Notebook) is an interactive developer tool (you can try it under [https://try.jupyter.org/](https://try.jupyter.org/)). It is not a standalone programming language, rather a HTML and JSON based server-client application in which we can edit and execute notebook documents via a web browser (1). This could be done with the help of a kernel which compiles the code embedded in the notebook written on the predefined programming language. There are many kernels which can be used (eg. Python, R, Matlab, for full list see [https://github.com/jupyter/jupyter/wiki/Jupyter-kernels/](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels/)). And that is the point when we can profit from the advantages of Python. It is a Swiss Army Knife with the ability of establishing contact with other kernels, additionally push and pull variables across programming languages. Imagine if we can combine the visualization power and simplicity of seaborn (Python package) with the flexibility of pandas (Python package), meanwhile we can use the full functionality of tidyverse (R library), create tons of fancy mixed models and perform Bayesian analysis what we are only able to do in R during an interactive coding process.

This is the opportunity what Jupyter Notebook offers us. The code in a notebook is splitted up into cells which can be themselves executed while the variables are stored after the execution and can be accessed from the other cells. Whit this feature we are capable to build and immediately show a bar chart from our data in the middle of coding and then continue the analysis, what makes it an extremely powerful and flexible method for data processing, visualization and analysis. Python has many packages to communicate with other kernels (eg. RPy2 for R) and this feature has a cell magic integration in Jupyter Notebook which we can write entire code blocks in other languages during a Python session using our previously defined variables.

Additionally, Jupyter provides us a dashboard to manage our documents and kernels with tons of other advanced features (eg. using comments and markdowns combined with LaTeX document preparation system) which makes us able to turn our notebook into a fully formatted documentation and analysis of an experiment.

I want to introduce you the benefits of this new and flexible approach to the programmed statistics illustrated with concrete examples.

(1) What is the Jupyter Notebook? ([http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html), retrieved on 29/10/2017)

__RapidMiner GUI based data analytics tool: a tutorial__

_Balázs Péter Hámornik (RapidMiner; Budapest University of Technology and Economics)_

RapidMiner is a data science platform designed to make analytics fast and simple. It provides a graphic user interface to design analytics processes and also capable to add code. Fast because of drag and drop and link operators as pieces of actions. Simple that it provides an overview of the whole analytics process in a visually explaining way that also can be annotated.

The RapidMiner Studio aims non-coding users or users not primarily preferring to code. This makes is easier to onboard for people with background in humanities. Hence one prefers to add custom codes into the visually designed process it is possible to use R and Python. 

With RapidMiner one can access various data sources, perform data preparation, data cleaning, calculate descriptive statistics illustrated with charts, and perform predictive statistical analyses. With extensions available among others, time series and text data can also be processed. 

Once and analytic workflow has been designed in a RapidMiner process it can be run multiple times if the data changes or new records and samples are available. These processes can be easily changed to fit the current needs. Sets of operators in the processes can also be reapplied in other processes to save time.

The user interface contains built in help section describing not just what to click but the basic statistical knowledge to understand the actions can be done by the operator. Another helpful feature the “wisdom of the crowds” helps to find the most used operator settings by recommendation. This leads to good defaults what help beginners to run processes.

In this tutorial, I’m going to demonstrate the capabilities described above in an interactive session on an analytic process.

With these capabilities RapidMiner Studio can be successfully applied by researchers and students in cognitive science.

__Automatic data analysis with CogStat__

_Attila Krajcsi (Eötvös Loránd University, Department of Cognitive Psychology)_

Many times, while analyzing the data, the very same steps and decisions should be made. In most software solutions, these steps are independent tasks, and the researcher runs them independently. CogStat ([www.cogstat.org](http://www.cogstat.org)) is an automatic data analysis software which after a task is specified (e.g., compare groups, explore a variable pair, etc.), automatically compiles the relevant analyses, e.g., displays the raw data, calculates the descriptive statistics, calculates the effect sizes, runs the hypothesis tests with the appropriate assumption checks, calculates interval estimations, displays the results in APA format. Such an automatic data analysis can be useful for different reasons. First, researchers can analyze their data faster, more precisely and more consistently. Second, students can run their analysis more easily, and can learn new methods. Third, methodologists can consider automatic analysis software as a platform to make efficient methods more accessible and a platform to find consensus about best practices.

#### Session 2: New methods

__Bayes Factor Analysis: Why and How?__

_Balázs Aczél (Eötvös Loránd University)_

The two major competing statistical approaches in today's psychological research are the traditional Null-hypothesis Significance Testing (NHST) and the less frequently used Bayes Factor analysis. In this talk, I will argue why Bayes Factor Analysis is more adequate, appropriate and practical for psychology researchers. Despite the advantages of the Bayes Factor analysis, it posits a challenge to researchers, as it requires a different thinking about data-collection, evidence and conclusion. With luck, the talk will give guidelines to this task for those interested in opening their mind to modern statistical methods.

__New cluster-analytic developments in ROPstat__

_András Vargha (Károli Gáspár University, Eötvös Loránd University, Budapest)_

The presentation focuses on some new methods of the ROPstat statistical software that are important in the evaluation of the quality of a cluster solution, no matter, what type of cluster analysis (CA) was used. For this purpose a number of quality coefficients (QCs) are presented. For each QC there is a rule of thumb for the decision whether a solution can be judged as good, acceptable, or poor. However, a simulation study shows that even in random samples of independent normal variables the quality of a cluster solution depends highly on the number of variables and the number of clusters. Consequently, cluster results have to be related to a structure obtained by means of randomized input variables as a set of control variables. Four types of creating random control variables are introduced along with a new measure of relative improvement (called MORI), by means of which QC values can be evaluated. In the last part of the presentation a new feature of the Residue module of ROPstat is described, which allows the user to identify dense points (core points) in a multivariate data set.

__The network approach to psychopathology__

_Bertalan Polner (Laboratory for Perception & Cognition and Clinical Neuroscience, Department of Cognitive Science, Budapest University of Technology and Economics)_

Mental disorders are characterized by fluctuating and interacting symptoms. For instance, in the domain of depression, insomnia can lead to fatigue and concentration problems, or in the case of psychosis, the interaction between affective disturbances,anomalous experiences and hallucinations may play a causal role in the formation of delusions. It has been argued that if we assume that symptoms are caused by an unobservable disease, and apply factor analysis to our data in order to extract latent variables reflecting such hidden disease processes, we can overlook a very important aspect of mental disorders - the interactions between individual symptoms that may play a key role in the emergence and maintenance of psychopathology. 

The network approach to psychopathology attempts to overcome this limitation by modelling mental disorders as complex networks, where nodes and links represent symptoms and their interactions, respectively (see Cramer et al. 2010 doi:10.1017/S0140525X09991567 and Fried et al. 2017 doi:10.1007/s00127-016-1319-z). Once the network is estimated, one may choose from a wide variety of established analytical tools to examine the structure and dynamics of the network. The derived network metrics can be used to make inferences which can have theoretical and practical implications as well. I am going to provide an overview and a critical appraisal of the literature on psychopathology networks, and will also give a brief introduction to network analysis in R. 

__Why go multifractal?__

_Zsolt Palatinus (University of Szeged)_

Interactions are fundamental to complex systemic behavior, such as weather patterns, brain functions, perception, cognition and social behavior. There is growing concern (Riley & Van Orden, 2005; Molenaar, 2008.) that traditional statistical methods seldom provide reliable emprical window into interactive behavior. Tools built on the assumption of normal distribution and linear causation are less successful in describing and predicting systems with nonnormal distributions and bidirectional causation and massive interdependence. Natural systems often exhibit power-law distributions and the variation of their components are correlated across both spatial and temporal scales (Van Orden et al., 2003, 2005). These correlations allow inquiry into the number, and strength of interactions among the active components. In recent years, the concept of multifractality has become more popular in modeling, exploration and prediction of complex dynamical system behavior. Multifractals were first put to work in interaction driven physics and atmospheric sciences (Kavasseri & Nagarajan, 2005; Lovejoy & Schertzer, 2006). Later, multifractal concepts and tools were applied to problems in economics, ecology, medical sciences, diagnostics and behavior. For example, in psychology, introductory reports (i.e. Ihlen and Vereijken 2010) were soon followed by tutorials and practical guidance (Ihlen, 2012; Kelty-Stephen et al., 2013). I will briefly introduce fundamental concepts of the most commonly used techniques through notable recent results and I will provide practical guidance in getting started with these relatively new and exciting methods.

Methods
MFDFA (Matlab, R), Chaabra & Jensen method (Matlab), Box Counting Dimension (Matlab, ImageJ),
WTMM (Matlab), supporting statistical modeling tools.

Data types
Motion capture, Force plate, EEG, Image, Video, Audio

Ihlen, E. A. (2012). Introduction to multifractal detrended ﬂuctuation analysis in Matlab. Frontiers in Physiology-Fractal Physiology, 3, 141. 

Ihlen, E. A. F., & Vereijken, B. (2010). Interaction-dominant dynamics in human cognition: Beyond 1/f ﬂuctuation. Journal of Experimental Psychology: General, 139, 436–463.

Kavasseri, R. G., & Nagarajan, R. (2005). A multifractal description of wind speed records. Chaos, Solitons, & Fractals, 24, 165–173. 

Kelty-Stephen, D. G., Palatinus, K., Saltzman, E., & Dixon, J. A. (2013). A tutorial on multifractality, cascades, and interactivity for empirical time series in ecological science. Ecological Psychology, 25, 1-62. 

Lovejoy, S., & Schertzer, D. (2006). Multifractals, cloud radiance, and rain. Journal of Hydrology, 322, 59–88. 

Molenaar, P. C. M. (2008). On the implications of the classical ergodic theorems: Analysis of developmental processes has to focus on intraindividual variation. Developmental Psychobiology, 50, 60–69.

Riley, M. A., & Van Orden, G. C. (Eds.). (2005). Tutorials in contemporary nonlinear methods for the behavioral sciences. Arlington, VA: National Science Foundation.

Van Orden, G. C., Holden, J. G., & Turvey,M. T. (2003). Self-organization of cognitive performance. Journal of Experimental Psychology: General, 132, 331–350. 

Van Orden, G. C., Holden, J. G., & Turvey, M. T. (2005). Human cognition and 1/f scaling. Journal of Experimental Psychology: General, 134, 117–123.


<div class='four spacing'></div>
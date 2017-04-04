# Open-Source Analysis in Neuroscience, Atlanta

Hands-on tutorials teaching you how to analyze data with open-source software, with a focus on neuroscience

## Saturday, April 8th, 2017

## [Emory School of Medicine](https://www.google.com/maps/dir/''/1648+Pierce+Dr+NE,+Atlanta,+GA+30322/@33.7938878,-84.3242572,17z/data=!3m1!4b1!4m8!4m7!1m0!1m5!1m1!1s0x88f506fa0c2fe91d:0x39cfe7f977692e9b!2m2!1d-84.3220685!2d33.7938878?hl=en)

### sponsored by the [Computational Neuroscience Training Program grant](http://compneurosci.college.emory.edu/index.html)

## Schedule

*Please see below for abstracts*

8:30-9:00. Light breakfast

Time | Room 120 | Room 130
--- | --- | ---
9:00-10:30 |  **Introduction to plotting in R using ggplot2.** Hasse Walum. | **Models of calcium imaging with generative adversarial neural nets using GANDLF.** Ben Bolte.
10:45-12:15 | **Sex differences in gene expression as shown with R and the edgeR package.** David Sinkiewicz. | **Not Just For Python: Using Matlab In Jupyter Notebooks for Data Analysis and Visualization.** Rhett Morissette.

12:15-1:00. Lunch with speakers (requires RSVP through Eventbrite)

Time | Room 120 | Room 130
--- | --- | ---
1:00-2:30 | **Using simulation in R to calculate statistical power.** Hasse Walum. | **A TensorFlow tutorial: Cross-Cultural Facial Emotion Representation Learning Using Convolutional Networks.** Safoora Yousefi.
2:45-4:15 | **Generalized Linear Models Tutorial for Neuroscientists using the Python package statsmodels.** David Hofmann. | **Intro to Machine Learning in Python with scikit-learn.** David Nicholson.


Time | Room 110
--- | ---
1:00-2:30 | **Configurable Pipeline for the Analysis of Connectomes (C-PAC) tutorial.** Cameron Craddock.

## abstracts

### *Introduction to plotting in R using ggplot2.* Hasse Walum.
One of the benefits of using R is that it has great graphics capabilities, but plotting in R comes with a somewhat steep learning curve. During this workshop I will give an introduction to the package ggplot2. I will show the basics of how you can use this package to create publication quality plots.

----------------------------------------------------------------------------------------------------------------------

### *Models of calcium imaging with generative adversarial neural nets using GANDLF.* Ben Bolte
In neuroscience, one of the most challenging tasks is obtaining reliable recordings of neuron spiking behavior. One approach is to use calcium imaging to show the spiking behavior of a population of neurons. This approach uses a calcium indicator dye, which fluoresces when calcium is present. Calcium concentration in a neuron is closely related to spiking behavior, but inferring the spikes from calcium fluorescence level is a non-trivial task. There are often sources of noise in the recordings, and the relationship between the amount of calcium in the cell and the cell's membrane voltage is non-linear and time-dependent. In this tutorial, we will use recent methods from deep learning to characterize the distribution of calcium fluorescence signals that correspond to a spike. This tutorial assumes you have an idea of the fundamentals of deep learning. We will use the deep learning framework Keras to build our models. The tutorial will use the training data provided from the SpikeFinder competition. At the same time we will build up our understand of deep learning methods which can be applied to other tasks.
[https://github.com/codekansas/calcium-gan](https://github.com/codekansas/calcium-gan)

----------------------------------------------------------------------------------------------------------------------

### *Sex differences in gene expression as shown with R, RSEM, and edgeR.* David Sinkiewicz.

Transcriptomics is a relatively new field that provides a powerful opportunity for observing genetic responses to changes in behavior, hormonal state, or many other stimuli an organism may encounter. We have utilized next-gen RNAseq techniques to produce a novel transcriptome for Syrian hamster brains. Additionally, using R (an environment for performing and graphing statistical analyses), we were able to use our sequencing data to analyze gene expression in these brains. We used two R packages, RSEM, used to compare raw RNAseq output to an assembled transcriptome resulting in expression values for each identified transcript, and EdgeR, which determines what transcripts in the transcriptome are differentially expressed based on a manipulation. This session will walk you through an EdgeR analysis of sex differences in whole brain transcriptomes of Syrian hamsters and will include an opportunity to perform your own analysis on a sample data set. The steps you will walk through are the same that you can apply to an RNAseq dataset of your own. 

----------------------------------------------------------------------------------------------------------------------

### *Not Just For Python: Using Matlab In Jupyter Notebooks for Data Analysis and Visualization.* Rhett Morissette.

MATLAB is a numerical computing and programming language, optimized for designing and writing powerful programs with few lines of code. The relative power and simplicity of MATLAB makes it a top choice for academic researchers and engineers needing to manipulate, analyze, and visualize data. While there are numerous advantages to MATLAB, recent tools have been developed that create more interactive environments for programming, analysis, and visualizations in open-source programming languages such as Python, R, Julia, and Octave. One such tool is Jupyter, a web application through which users can create notebooks in their browsers that contain cells of live code alongside text and plots. To utilize the advantages of both MATLAB and Jupyter, the open-source community has developed a MATLAB “kernel” or programming environment that runs within Jupyter. In this workshop, I will demonstrate how to install and setup the matlab kernel in Jupyter and will demonstrate an example of a data analysis workflow using data from my own behavioral and imaging experiments. 

----------------------------------------------------------------------------------------------------------------------

### *Using simulation in R to calculate statistical power.* Hasse Walum.
Estimating statistical power is an important part of experimental design. There are many programs and packages that will calculate power, but often limited regarding th be underlying statistical model the calculations are based on. During this workshop I will give an introduction to how power can be estimated using simulation, a flexible method that can used for any design.

------------------------------------------------------------------------------------------------

### *A TensorFlow tutorial: Cross-Cultural Facial Emotion Representation Learning Using Convolutional Networks.* Safoora Yousefi.
Tensorflow is an open-source library that uses data flow graphs for numerical computation. It was developed by the Google Brain team for deep learning research. Google now uses Tensorflow in many areas, including search, voice recognition, translation and photos. In this tutorial, we are going to use Tensorflow to build a facial emotion classifier. We will explore how this library is flexible and smart enough to allow us to focus on research and design questions rather than implementation details. Through a Jupyter notebook, we will learn to use Tensorflow to investigate how different cultures express their facial emotions in different ways.

------------------------------------------------------------------------------------------------

### *Configurable Pipeline for the Analysis of Connectomes (C-PAC) tutorial.* Cameron Craddock.
The Configurable Pipeline for the Analysis of Connectomes (C-PAC) is an open-source software pipeline for automated preprocessing and analysis of resting-state fMRI data. C-PAC builds upon a robust set of existing software packages including AFNI, FSL, and ANTS, and makes it easy for both novice users and experts to explore their data using a wide array of analytic tools. Users define analysis pipelines by specifying a combination of preprocessing options and analyses to be run on an arbitrary number of subjects. In this session, the project director and co-principal investigator behind C-PAC, Cameron Craddock will walk attendees through using the GUI or text editor to configure a pipeline for analysis. Hence attendees will leave the session prepared to apply C-PAC to their own data.
[https://fcp-indi.github.io/](https://fcp-indi.github.io/)

------------------------------------------------------------------------------------------------

### *Generalized Linear Models Tutorial for Neuroscientists using the Python package statsmodels.* David Hofmann.
Generalized Linear Models (GLMs) are a simple yet powerful stochastic modeling tool. They provide a natural extension of the well known linear regression to statistics beyond Gaussian that still belong to the exponential family. Assuming a Poisson statistics, they are often used as a simple stochastic model of a spiking neuron. They have been used in neuroscience to model receptive fields (Bush et al. 2016, Truccolo et al. 2011) as well as effective connectivity between neurons (Pillow et al. 2008). In this tutorial we will review the formal framework of GLMs and use the implementation that comes with the Python toolbox "statsmodels" to test it on some previously published data. Finally, we discuss the limitations of GLMs.

------------------------------------------------------------------------------------------------

### *Intro to Machine Learning in Python with scikit-learn.* David Nicholson.
Machine learning can be thought of as a collection of algorithms that build statistical models given a set of data. For instance, an algorithm might build a model that classifies neuron type after being trained with morphological features like soma diameter and number of branches in the dendritic tree. Many software libraries exist that implement machine learning algorithms. Perhaps one of the most popular and easiest to use is the Python package *scikit-learn*. In this tutorial I will introduce the *scikit-learn* interface, and walk you through the basic background you need to succesfully apply supervised learning algorithms to your data.

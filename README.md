# Decoding Behaviour from neural data - NMA 2020 Project

The [Neuromatch Academy](https://www.neuromatchacademy.org/) was a summer school that happened in the summer of 2020. In the midst of a pandemic, the school emerged on an online platform reaching out to everyone across the world. The academy served the purpose of training neuroscientists to learn computational tools, make connections to real world neuroscience problems, and promote networking with researchers.

The academy also provided an opportunity for the students to carry out their own mini-project that would last three weeks. Several datasets were provided for exploration. Our group Decision Makers, from the pod 041-Gregarious-sambars have decided to go with the Steinmetz data set. Below us is a description of the Steinmetz data set that we chose.


## Description and objectives

During a decision making task like the one in the Steinmetz experiment, a number of different brain regions are involved in the processing of sensory information to decision making to motor action. These regions act together in particular networks.

Can we predict the rodent’s movement based on activity from the visual regions before or after the movement has occurred?

Our questions were inspired by some of the original questions from some [exemplary projects](https://docs.google.com/presentation/d/1WAHfJcBPM4rmwwvreAAS92sRYtltJRwklxH-82NzCYo/preview?pru=AAABc3cRwPE*S0Y87T5BNFvf9wvSREdLUQ&slide=id.p).

We decided to focus on one rodent’s data, from one session (Session no. 11). Our chosen regions were the visual cortex, thalamus and the secondary motor area (MOs, MOp). These two are anatomically and functionally distinct, hence they were our best shot at investigating differences in activity. 

We believe that the dataset has enough potential, and given enough time we can build better models to represent the temporal activities of regions. However for the time being we shall settle on the simpler task.

## Status - *Completed*

We have successfully completed the project. All the relevant details can be found in our supporting documentation file. which can be accessed [here](https://docs.google.com/document/d/1WPnaAyMBlNrnGwVGrvI8BBtGozhbzqw_azzl161bB88/edit?usp=sharing). 

## Dataset

The dataset used for this purpose was the dataset procured by [Steinmetz et al. 2019](https://figshare.com/articles/steinmetz/9598406).

The Steinmetz dataset is an electrophysiological recording from multiple regions of the mouse brain during a 2-Alternative Forced Choice Task paradigm. Neuropixel probes were used to record from approx. 30,000 neurons from 42 regions, while the mouse performed a visual discrimination task. In each trial (multiple trials conducted over each session; and a total of 39 sessions), a mouse was placed on a wheel with its head fixed, surrounded by 3 screens (left, right and in front). Images of differential contrast were presented to either the left, right or both the screens and the mouse had to turn the wheel in the correct direction in order to bring the greater-contrast image to the front-screen. If there was no image presented on either side, the correct response was to hold the wheel steady for 1.5s. Neural activity was continuously recorded for the entire duration of the task. 

Code for the analysis was written in Python, with the help of scientific packages; Numpy, Scipy, Sklearn, Neural_Decoding, Matplotlib

To load the data into our notebooks for further analysis, we used some [code](https://github.com/MouseLand/steinmetz2019_NMA) provided by Dr. Marius Pachitariu.

For a detailed description of the dataset see [this](https://github.com/nsteinme/steinmetz-et-al-2019/wiki/data-files) document by Dr. Nick Steinmetz and [this](https://docs.google.com/document/d/1WPnaAyMBlNrnGwVGrvI8BBtGozhbzqw_azzl161bB88/edit?usp=sharing) writeup by us.


## Resources

**Literature:**
* [Distributed coding of choice, action and engagement across the mouse brain](https://www.nature.com/articles/s41586-019-1787-x)
* [A perceptual decision requires sensory but not action coding in mouse cortex](https://www.biorxiv.org/content/10.1101/501627v3)
* [Theoretical Neuroscience](https://mitpress.mit.edu/books/theoretical-neuroscience)
* [Perceptual Decision Making in Rodents, Monkeys, and Humans](https://www.sciencedirect.com/science/article/pii/S0896627316309424)


**Packages:**
* [NumPy](https://numpy.org/)
* [SciPy](https://www.scipy.org/)
* [MatPlotLib](https://matplotlib.org/)
* [Neural_Decoding](https://github.com/KordingLab/Neural_Decoding)
* [Scikit-learn](https://scikit-learn.org/stable/)

**Code References:**
* [steinmetz-et-al-2019 data description](https://github.com/nsteinme/steinmetz-et-al-2019/wiki/data-files)
* [steinmetz2019_NMA by Dr. Marius Pachitariu](https://github.com/MouseLand/steinmetz2019_NMA)
* [Neuromatch Academy](https://github.com/NeuromatchAcademy/course-content)

**Documentation:**
* [GitHub Repo](https://github.com/piyushchauhan1/behaviour-decoder)
* [Presentation](https://docs.google.com/presentation/d/1FgJZ6W-nIBQ3u_UKMXYFKUAiQH-RlVQIMSp2UUtr2uo/edit?usp=sharing)
* [Documentation](https://docs.google.com/document/d/1WPnaAyMBlNrnGwVGrvI8BBtGozhbzqw_azzl161bB88/edit?usp=sharing)
* [Data Descrtiption File](https://docs.google.com/document/d/1iDkVdRwfNnwH7mg--xJijK5lbxgtE879HlcwWts3yGw/edit?usp=sharing)

## People

* [Nathalie Rochefort (Mentor)](https://github.com/nathalierochefort)
* [Zane Mitrevica (TA)](https://github.com/zanemit)
* [Omika Wadhwa](https://github.com/om-git216)
* [Hsieh, Kun-lin](https://github.com/v738301)
* [Piyush Chauhan](https://github.com/piyushchauhan1)

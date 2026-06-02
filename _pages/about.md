---
permalink: /
title: "Welcome to my academic website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Ayako Tsuchiyama is a PhD candidate in Geophysics, Department of Earth, Atmospheric and Planetary Sciences, Massachusetts Institute of Technology. My research focuses on seismology, including deep earthquakes and deformation processes in subduction zones, as well as planetary seismology applications to the Moon and Titan. I am expected to graduate in spring 2027 and am actively seeking postdoctoral positions.

Main project: Deep earthquakes in subduction zones
------
I have been working on the mechanisms of deep earthquakes (depth > 70 km) since starting graduate school. My first paper investigates the source mechanisms of deep-focus earthquakes in central Japan, showing nearly identical waveforms and focal mechanism solutions despite differences in source parameters. These results suggest that different mechanisms of deep earthquakes can coexist at the same depth. This work was published in Physics of the Earth and Planetary Interiors as [Tsuchiyama and Nakajima, 2021](https://www.sciencedirect.com/science/article/abs/pii/S0031920121000534).

I began my PhD at MIT, where I started working on the Bucaramanga Nest in Colombia. I transitioned from Japanese to English for research and from Fortran to Python and MATLAB for programming. My work includes constructing a six-year earthquake catalog using matched-filter detection, relocating events using GrowClust and HypoDD, and developing a method to resolve kilometer-scale spatial variations in deep earthquakes using teleseismic observations. I also proposed a self-sustaining stress transfer mechanism driven by thermal shear instability. The manuscript was submitted in September 2025 and revised based on two constructive reviews. 

Other project 1: Low-frequency earthquakes in continental crust
------
I have also worked on identifying low-frequency earthquakes in the shallow crust. My second paper analyzes the seismic spectra of aftershocks in the 2019 Ridgecrest sequence and identifies low-frequency aftershocks (LFAs) using amplitude ratios between low- and high-frequency bands. The results suggest that LFAs are associated with highly fractured fault zones and local heterogeneity, likely related to cross-faulting induced by the aftershock sequence at shallow depths. These observations imply that elevated pore-fluid pressure in fractured fault zones may contribute to the band-limited nature of LFAs and LFEs. This work was published in the Bulletin of the Seismological Society of America [Tsuchiyama et al., 2022](https://pubs.geoscienceworld.org/ssa/bssa/article/112/2/750/610613/Emergence-of-Low-Frequency-Aftershocks-of-the-2019?guestAccessKey=)

Other project 2: Delta deposition under sea-level cycles of Titan
------

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

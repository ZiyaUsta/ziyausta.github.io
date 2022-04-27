---
permalink: /
title: "Hi, I am Ziya"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I hold a PhD and a MSc in Geomatic Engineering ([Karadeniz Technical University](https://www.ktu.edu.tr/en), Turkey), and a BSc in Geodesy and Photogrammetry Engineering ([Yıldız Technical University](https://www.yildiz.edu.tr/en), Turkey). 

I was a short-term visiting researcher in the Geo-Spatial Analytics Lab at the [University of South Florida](www.usfsp.edu) in the United States, worked with [Barnali Dixon](https://bit.ly/2x54xLW) during my master and was a visiting researcher in the [Department of Earth Observation](https://bit.ly/3acKpWA) at the [Friedrich-Schiller-University of Jena](https://bit.ly/2x9ayaw) in Germany, worked with [Christiane Schmullius](https://bit.ly/2vutNKX) during my PhD. 

Currently, I am working as an assistant professor for the [Department of Architecture and City Planning (Mapping and Cadastre Programme)](https://myo.artvin.edu.tr/harita-ve-kadastro) of [Artvin Vocational School](https://myo.artvin.edu.tr/tr) in Artvin Coruh University, Turkey. Also, I worked as a research assistant from March 2011 to June 2020 at the [Department of Geomatic Engineering](http://www.hrm.yildiz.edu.tr/en) in Yildiz Technical University, Turkey. 

As an editorial task, I have been serving as an [associate editor](https://www.springer.com/journal/12517/editors) for the [Arabian Journal of Geosciences](https://www.springer.com/journal/12517).
 
My main research interests include Polarimetric Synthetic Aperture Radar (PolSAR) Remote Sensing, Applied Machine Learning and particularly ensemble learning algorithms. I'm the member of [IEEE Geoscience and Remote Sensing Society](http://www.grss-ieee.org/) and [International Society for Photogrammetry and Remote Sensing](https://www.isprs.org/). I received the award for Top Reviewers for Geosciences - September 2018 from [Publons](https://publons.com/researcher/1175331/mustafa-ustuner/). I have been voluntarily working for the [IEEE Geoscience and Remote Sensing Society](http://www.grss-ieee.org/) as the social media chair as well as the social media coordinator for [ISPRS Student Consortium](http://sc.isprs.org/home.html). I was the publicity co-chair for [IGARSS 2020](https://igarss2020.org/OrganizingCommittee.asp) where serving for social media and outreach activities.

Also, I have been serving as a reviewer for the following journals: IEEE Transactions on Geoscience and Remote Sensing, IEEE Geoscience and Remote Sensing Letters, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, International Journal of Remote Sensing, European Journal of Remote Sensing, Journal of Applied Remote Sensing, Remote Sensing Letters, International Journal of Applied Earth Observation and Geoinformation, Geocarto International, Computers and Electronics in Agriculture, Remote Sensing, IEEE Access, IET Image Processing, Geo-Spatial Information Science, SN Applied Sciences, Concurrency and Computation: Practice and Experience, Sensors and Turkish Journal of Remote Sensing and GIS.

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.


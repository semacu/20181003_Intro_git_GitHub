<img align="right" src=images/github_icon.png width="225">

# Beginners introduction to Git and GitHub

- Date and time: 3rd October 2018, 10:00 - 12:00
- Location: [Drosophila Connectomics Group - Jefferis lab](https://www.zoo.cam.ac.uk/research/groups/connectomics/), [Department of Zoology](https://www.zoo.cam.ac.uk/), University of Cambridge, UK
- Please bring your laptop or mobile device if you'd like to follow the practical part



## Overview

**Morning session**:

- [Background and motivation](README.md#background-and-motivation)
- [What is version control? What is Git? What is GitHub?](README.md#what-is-version-control-what-is-git-what-is-github)
- [How can you use Git and GitHub? How can they be useful for you?](README.md#how-can-you-use-git-and-github-how-can-they-be-useful-for-you)
- [Practical session: working with Git and GitHub](README.md#practical-session-working-with-git-and-github)

**Afternoon session**: markdown, pages and wikis; creating good README files; issue tracking; sofware licenses



## Background and motivation

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/finaldoc.gif width="600">
</p>

<p align="right">
(http://phdcomics.com/comics/archive_print.php?comicid=1531)
</p>


**Being more open and reproducible helps to improve science**:

- Nature Methods 2018 editorial [**Easing the burden of code review**](https://www.nature.com/articles/s41592-018-0137-5):

*An increasing share of modern research relies on analytical code and software. In turn, a good deal of irreproducible research can be attributed to computational tools that are difficult to decipher, use or recreate. Through the concerted efforts of computational researchers and stricter guidelines from publishers, the culture of scientific software is now more open and geared toward dissemination than ever [...]*

- GitHub has become the go-to site when releasing code associated to a manuscript or scripts developed within a project



## What is version control? What is Git? What is GitHub?

[**Version control**](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) is the management of *changes* (a.k.a. *revisions*) to any types of information
  - Simple versioning: adding v1.0, v1.1, v1.2, v2.0 ... to file names
  - Basic tools: Google Drive, Dropbox ...
  - Advanced tools: Git

The first version control systems were created by groups writing software and code, but they can now be used for any kind of files or projects.

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/vcs.png width="800">
</p>

<p align="right">
(adapted from http://lhzuigao.com/309note.html)
</p>

Advantages of *distributed* (right) over *centralised* (left) version control systems involve:

  - If the central repository (server) crashes, it could be recovered / backed up from any of the local repositories created e.g. by the researcher, collaborator or group leader.
  - Each person can make changes to their local repositories *offline*. Then integrate their individual changes in the central repository (server) when connected *online*.


[**Git**](https://git-scm.com) is a *distributed* version control system to keep track and compare the history of *changes* made to your scripts and files. It allows groups of people to work on the same documents at the same time, and without stepping on each other's toes. It was created by Linus Torvalds in 2005 for the development of the Linux project. It is **free** and **open source** and helps you with:
  - Creating repositories to host your projects using the [command-line](https://en.wikipedia.org/wiki/Command-line_interface)
  - Tracking changes in the files and folders within your repositories


[**GitHub**](https://github.com/) is a platform to share and showcase your work online with collaborators and the wider audience. A tool to help you build projects that are collaborative, well documented, and version-controlled. It provides you with:
  - A place to host and backup your repositories online
  - A nice web interface to your repositories
  - A strategy to collaborate with colleagues

Versions in Git and GitHub are identified by a *revision number*, e.g. 60363b1, also known as *commit*. Each revision is associated with a *timestamp* and the *person* making the change. Revisions can be **compared**, **restored**, and with some types of files, **merged**.

There are other softwares for version control similar to Git, e.g. [svn](https://en.wikipedia.org/wiki/Apache_Subversion). Also, there are other online platforms similar to GitHub to share and collaborate code, e.g. [GitLab](https://about.gitlab.com/).



## How can you use Git and GitHub? How can they be useful for you?

The interfaces to Git and GitHub are:

- Via the command-line using *git*

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/git_commandline.png width="600">
</p>

- Directly [online](http://github.com/)

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/github_online.png width="800">
</p>

- Github [Desktop](https://desktop.github.com/) (available for Mac and Windows)

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/github_desktop.png width="800">
</p>

<p align="right">
(https://programminghistorian.org/lessons/getting-started-with-github-desktop)
</p>

For this workshop, we will mainly use GitHub's online interface and git commands.



## Practical session: working with Git and GitHub



## Future outlook

- Nature Methods 2018 editorial [**Easing the burden of code review**](https://www.nature.com/articles/s41592-018-0137-5):

*[...] Yet, even in the era of Git repositories, peer reviewing code can be frustrating and time consuming [...] Computational tools are complex objects that depend on many components to run. Dependencies include the operating system, programming language, external code libraries, configuration settings and run parameters. Reproducing these conditions is made even harder by the fact that components typically exist in multiple versions. Many come with their own prerequisites, creating a maddening rabbit hole of dependencies on dependencies [...]*

Two tools that begin to make a difference in the area of code reproducibility and will be the aim of future workshops:

- [Code Ocean](https://codeocean.com/)
- [Binder](https://mybinder.org/)



## The End

Many Thanks for your attention! Enjoy Git and GitHub! :octocat:

Feedback: please complete the following [short survey]()

Any later questions about this workshop and materials? Just email: sermarcue@gmail.com or mark.fernandes@cruk.cam.ac.uk



## References and materials

Blogs:
- [Beyond Basic R - Version Control with Git](https://owi.usgs.gov/blog/beyond-basic-git/)

Books:
- [Happy Git and GitHub for the R user](http://happygitwithr.com/)

Courses:
- [A Friendly Introduction to GitHub](https://kirstiejane.github.io/friendly-github-intro/)
- [Software Carpentry: Version Control with Git](http://swcarpentry.github.io/git-novice/)
- [Resources to learn Git](http://try.github.io/)
- [GitHub On Demand Training](https://services.github.com/on-demand/)
- [A quick introduction to Git and GitHub](http://www.datacarpentry.org/semester-biology/materials/git-in-30-minutes/)

Help:
- GitHub [Help](https://help.github.com/)

Papers:
- Nature Methods 2018 editorial, [Easing the burden of code review](https://www.nature.com/articles/s41592-018-0137-5)
- Perkel 2018:
  - [When it comes to reproducible science, Git is code for success](https://www.natureindex.com/news-blog/when-it-comes-to-reproducible-science-git-is-code-for-success)
  - [TechBlog: Git: The reproducibility tool scientists love to hate](http://blogs.nature.com/naturejobs/2018/06/11/git-the-reproducibility-tool-scientists-love-to-hate/)
- Silver 2018 [Microsoft’s purchase of GitHub leaves some scientists uneasy](https://www.nature.com/articles/d41586-018-05426-0)
- Russell et *al.* 2018 [A large-scale analysis of bioinformatics code on GitHub](https://www.biorxiv.org/content/early/2018/05/14/321919)
- Perez-Riverol et *al.* 2016 [Ten Simple Rules for Taking Advantage of Git and GitHub](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004947)
- Perkel 2016 [Democratic databases: science on GitHub](https://www.nature.com/news/democratic-databases-science-on-github-1.20719)
- Markowetz 2015 [Five selfish reasons to work reproducibly](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-015-0850-7)

Videos:
- [GitHub Training & Guides](https://www.youtube.com/githubguides)
- [Git & GitHub tutorial for Beginners](https://www.youtube.com/watch?v=3RjQznt-8kE&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)

Websites:
- [git](https://git-scm.com/)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)



## Acknowledgements

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/UniversityCambridge_logo.png height="50"> <img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/CRUKCI_logo.jpg height="50"> <img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/Jisc_logo.png height="50"> <img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/WellcomeTrust_logo.jpg height="50">
</p>

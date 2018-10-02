
<img align="right" src=images/github_icon.png width="225">

# Beginners introduction to Git and GitHub

- Date and time: 3rd October 2018, 10:00 - 12:00
- Location: [Drosophila Connectomics Group - Jefferis lab](https://www.zoo.cam.ac.uk/research/groups/connectomics/), [Department of Zoology](https://www.zoo.cam.ac.uk/), University of Cambridge, UK
- Please bring your laptop or mobile device if you'd like to follow the practical part



## Overview

**Morning session** (Sergio and Mark):

- [Background and motivation](README.md#background-and-motivation)
- [What is version control? What is Git? What is GitHub?](README.md#what-is-version-control-what-is-git-what-is-github)
- [How can you use Git and GitHub? How can they be useful for you?](README.md#how-can-you-use-git-and-github-how-can-they-be-useful-for-you)
- [Practical session: working with Git and GitHub](README.md#practical-session-working-with-git-and-github)

**Afternoon session** (Mark and Anne): markdown, pages and wikis; creating good README files; issue tracking; sofware licenses



## Background and motivation

- When repeating / reviewing previous work, researchers greatly benefit from having access to detailed documention of the methods used.

- Keeping track of the different versions of your project is one more way of being more reproducible.

- Some of the manual approaches to version control have **clear limitations**:

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/finaldoc.gif width="600">
</p>

<p align="right">
(http://phdcomics.com/comics/archive_print.php?comicid=1531)
</p>

- The scientific community is beginning to consider the value of peer reviewing computer code - see Nature Methods August 2018 editorial [**Easing the burden of code review**](https://www.nature.com/articles/s41592-018-0137-5):

*An increasing share of modern research relies on analytical code and software. In turn, a good deal of irreproducible research can be attributed to computational tools that are difficult to decipher, use or recreate. Through the concerted efforts of computational researchers and stricter guidelines from publishers, the culture of scientific software is now more open and geared toward dissemination than ever [...]*

- GitHub is becoming the go-to site when it comes to releasing / sharing the code associated to a manuscript or the scripts developed within a project.



## What is version control? What is Git? What is GitHub?

[**Version control**](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) is the management of *changes* (a.k.a. *revisions*) to any types of information
  - Simple versioning: adding v1.0, v1.1, v1.2, v2.0 ... to file names
  - Basic tools: Google Drive, Dropbox ...
  - Advanced tools: Git

The first version control systems were created by groups writing software and code. Fortunately they can now be used not only for computer code but for any type of files :smile:

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

For this workshop, we will use Git commands and GitHub's online interface.


### Examples

- To host and share your research outputs and software
  - Laboratories sharing own research e.g. the [Jefferis](https://github.com/jefferislab) or [Balasubramanian](https://github.com/sblab-bioinformatics) groups
  - Software source codes e.g. [BWA](https://github.com/lh3/bwa), an aligner of DNA sequences to reference genomes, and [PIDGIN](https://github.com/lhm30/PIDGINv2), and algorithm to predict protein targets for drug-like molecules
  - Or even to share research slides - see [Bérénice Batut](https://bebatut-slides.github.io/backofen_lab_retreat_04_17/#/)

- To create websites using [GitHub pages]((https://pages.github.com/))
  - Personal research websites, e.g. [Mike Love site](http://mikelove.github.io/)
  - Courses and activities, e.g.
    - [A Friendly Introduction to GitHub](https://kirstiejane.github.io/friendly-github-intro/)
    - [Statistics course in the University of British Columbia](http://stat545.com/index.html)

- To share the contents of a book, e.g. [Bioinformatics Data Skills](https://github.com/vsbuffalo/bds-files) or [Happy Git and GitHub for the R user](http://happygitwithr.com/)

- To write your PhD thesis, e.g. [A reasoning framework for C4 photosynthesis research based on high-throughput analysis](http://rik.smith-unna.com/phd/thesis.html)


### In the context of our research group

- Communication is key as most projects have both experimental and computational leaders
- Building from the classical ways of sharing - conversations/meetings, email, Dropbox, shared folders ... we want to build an environment where:
  - Computational colleagues can share code, figures and tables. Review others work and get credit from their collaborative work
  - Experimental colleagues can follow computational developments, access results and learn methods of data analysis

- And ideally avoiding situations like ...

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/reproducibility.gif width="800">
</p>

<p align="right">
(http://phdcomics.com/comics.php?f=1689)
</p>

- Parhaps a happier lifetime for a research project:

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/project_timeline.png width="800">
</p>

<p align="right">
(https://github.com/semacu/20170703_GitHubintheLab_CRUK-CI)
</p>


### Public (free) and private repositories

If you want to start creating repositories in GitHub, your first need to open an account:

- Public repositories are free, and can be browsed and downloaded by anyone
- Private repositories have associated costs - see [pricing of plans](https://github.com/pricing). The developer plan costs $7/month but it is free if you are [a student or an academic](https://education.github.com/pack)

Alternatively, [GitLab](https://about.gitlab.com/) uses a different business strategy with free private repositories and cost plans for public ones. There are other alternatives e.g. [Bitbucket](https://bitbucket.org/).


### Markdown

GitHub uses Markdown for text edition, a language with plain text formatting syntax, to render pages online. Some examples of Markdown syntax are available [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).



## Practical session: working with Git and GitHub

We have four possible tutorials:

- [Create a GitHub account](README.md#create-a-github-account) (+)
- [Create your first repository](README.md#create-your-first-repository) (+)
- [Explore your first repository and GitHub account](README.md#explore-your-first-repository-and-github-account) (++)
- [Making changes using Git in the command-line](README.md#making-changes-using-git-in-the-command-line) (+++)

### Create a GitHub account

- Go to https://github.com
- Fill in your **Username**, **Email** and **Password**. Then click on the green button "Sign up for GitHub".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p1_1.png width="800">
</p>

- Choose your personal plan page. Select "Free plan" and then click on "Continue".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p1_2.png width="800">
</p>

- Tailor your experience page. Choose the boxes that apply to you and click on "Submit". Otherwise, just go to "skip this step".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p1_3.png width="800">
</p>

- You have created a GitHub account! :smile:



### Create your first repository

- If you are not already signed in, sign in to GitHub using the **Username/Email** and **Password** created before.
- Click on the top-right "avatar icon" and select "Your profile". Have a quick browse through your page.

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_1.png width="800">
</p>

- Click on the top-right "+" icon and select "New repository". **Verify your email address**. You should have just received an email from GitHub in the address provided before. Find this email and click on "Verify email address".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_2.png width="400"> <img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_3.png width="400">
</p>

- Create a new repository page. Fill in a "Repository name", e.g. my_first_repository or my_analysis_script. For now choose "Public" and select the box to initialize this repository with a README. Finally, click on "Create repository".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_4.png width="800">
</p>

- You created your first repository! :rocket:



### Explore your first repository and GitHub account

#### Your first repository

- Click on **README.md** and go to the right pencil "Edit this file". Type anything to change the file, e.g. "GitHub is fun!".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_1.png width="800">
</p>

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_2.png width="800">
</p>

- Scroll down. Introduce a commit change message, e.g. "My first update", and select the radio button "Commit directly to the master branch". Then click on "Commit changes". Voilá!

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_3.png width="800">
</p>

- To view your **history of commits** for **README.md**, click on **README.md** and then on the "History" button on the right.
- Alternatively, to view your **history of commits** for your first repository, click on the name of your repository and select the tab depicting a small clock and the number of commits next to it.

Bonus points (5 min):

- Try to create a new file
- In your new repository, have a look at the "Settings" tab, explore "Collaborators" and try to add the person sitting next to you.


#### Your GitHub account

- Click on your top-right "avatar" icon and select "Settings".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_4.png width="800">
</p>

- Explore the tabs "Profile", "Account" and "Emails".




### Making changes using Git in the command-line

#### Check if Git is already installed in your computer, otherwise install Git

- (If in Mac), go to *Finder* -> *Applications* -> *Utilities* -> *Terminal* and type `git --version`.
  - If you get as output something like `git version 2.5.4 (Apple Git-61)`, then Git is already installed -> Jump to the next section.
  - If you get something around `git: command not found`, keep reading.

- To install Git in Mac, follow one of the next strategies:
  1. When running one of the following commands `git --version`, `git config` or `xcode-select --install` you may be offered to install developer command line tools. Accept the offer and follow with "Install".
  2. Go to https://git-scm.com/downloads and download git. Double click on the downloaded executable and follow instructions.
  3. If you have `homebrew` installed, type the following in the Terminal: `brew install git`.

- Check the following for installing in [Windows](http://happygitwithr.com/install-git.html#windows) or [Linux](http://happygitwithr.com/install-git.html#linux).


#### Tell git who you are (your GitHub username) and what your email address is

Example:

```bash
cd ~/Desktop
git config --global user.name "githubchemistry"
git config --global user.email "sm848@cam.ac.uk"
```

Check:

```bash
git config --list
```


#### Clone the repository created before

```bash
git clone https://github.com/githubchemistry/my_first_repository.git
cd my_first_repository
ls -lh
#-rw-r--r--  1 martin03  1310    38B 24 Oct 09:16 README.md
```

Your first repository created using GitHub is now a local repository located in your Desktop folder.


#### Tell git what's your repository url to pull and push commits

```bash
cd ~/Desktop/my_first_repository
git remote set-url origin https://githubchemistry@github.com/githubchemistry/my_first_repository.git
```

Check:

```bash
git remote -v
```


#### Make a change to the `README.md` file using your favourite text editor

- In your Desktop, go the cloned folder and open `README.md` with a text editor, e.g. TextEdit.
- Change the file, e.g. add a new line "This is my second line of script" and save changes.
- Check how changes are tracked by Git:

```bash
cd ~/Desktop/my_first_repository
git status
```

Now the status of `README.md` is modified.


#### Stage and commit the change

Staging:

```bash
git add README.md
git status
```

Committing:

```bash
git commit -a -m "My second update"
git status
```

#### Push changes to your online GitHub repository

```bash
git push origin master
```

Now check that your change to `README.md` made to your online GitHub repository.

Bonus points:

- Make another change to `README.md` using the online GitHub repository and pull the change to your local repository (Hint: `git pull`).

Done!




## Future outlook

- In the context of computational reproducibility, going back to the Nature Methods August 2018 editorial [**Easing the burden of code review**](https://www.nature.com/articles/s41592-018-0137-5):

*[...] Yet, even in the era of Git repositories, peer reviewing code can be frustrating and time consuming [...] Computational tools are complex objects that depend on many components to run. Dependencies include the operating system, programming language, external code libraries, configuration settings and run parameters. Reproducing these conditions is made even harder by the fact that components typically exist in multiple versions. Many come with their own prerequisites, creating a maddening rabbit hole of dependencies on dependencies [...]*

In other words, future steps will be to be able to execute code directly online (cloud). Two new resources are beginning to make a difference in this area - check them out :wink:

- [Code Ocean](https://codeocean.com/): Nature Methods, Nature Biotechnology and Nature Machine Intelligence have launched a trial to facilitate the peer review of computational methods and to improve their reproducibility
- [Binder](https://mybinder.org/)



## The End

Many Thanks for your attention! Enjoy Git and GitHub! :octocat:

Feedback: please complete the following [short survey]()

Any later questions about this workshop or the materials? Just email: sermarcue@gmail.com or mark.fernandes@cruk.cam.ac.uk



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

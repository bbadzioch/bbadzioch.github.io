# CDSE Python Workshop

This will be a hands-on workshop - we will write code thought it.
All participants need to bring laptops. Any operating system (Windows/Mac/Linux) is fine.
The instructions below describe how to install software and some additional
files we will need.


## Software installation

 * Install the [Anaconda distribution of Python 3.7](https://www.anaconda.com/download)
   (be sure to select the Python 3.7 version). If you have Anaconda previously installed,
   make sure that the you have either Python 3.6 or 3.7 and that you have fairly recent
   versions of the the Jupter notebook and the following Python packages: numpy, matplotlib,
   bokeh, pandas, requests, beautifulsoup4. Upgrade if needed. If you  installing Anaconda
   for the first time you don't need to worry about it, everything is included in the distribution.  



![Success](images/success.png)

This little guide demonstrate how to turn any [Github](http://github.com) repository with a bunch of [Markdown](https://en.wikipedia.org/wiki/Markdown) files into a simple website using [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

* You don't need to use the command line or anything other than your browser.
* It doesn't require any knowledge in Jekyll.
* It's completely compatible with any bunch of markdown files you already have in any existing repository without any modification to those files. That includes the basic `README.md` almost all repositories contain.
* The markdown files will remain just as readable and usable in Github than in your website.

In fact this guide uses the same configuration and can be read both in Github and in Github Pages, at your preference:

* [Here is the link to the Github version](https://github.com/nicolas-van/easy-markdown-to-github-pages)
* [Here is the link to the Github Pages version](https://nicolas-van.github.io/easy-markdown-to-github-pages/)

## Step by step instructions

### Determine the repository where you want to activate Github Pages

You can of course create a new repository if you want.

### Create the `_.config.yml` file

That file should be created on the root of your repository. Here is some content to copy-paste in it:

```
plugins:
  - jekyll-relative-links
relative_links:
  enabled: true
  collections: true
include:
  - CONTRIBUTING.md
  - README.md
  - LICENSE.md
  - COPYING.md
  - CODE_OF_CONDUCT.md
  - CONTRIBUTING.md
  - ISSUE_TEMPLATE.md
  - PULL_REQUEST_TEMPLATE.md
```

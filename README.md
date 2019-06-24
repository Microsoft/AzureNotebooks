[![Azure Notebooks](https://notebooks.azure.com/launch.svg)](https://notebooks.azure.com/Microsoft/libraries/samples)

### Azure Notebooks at Microsoft Connect() 2018

The Azure Notebooks team is excited to share with you our latest update that we
announced at Connect() 2018 during Scott Hanselman’s keynote.
[Here’s what’s new](https://github.com/Microsoft/AzureNotebooks/wiki/Azure-Notebooks-at-Microsoft-Connect()-2018).

# Azure Notebooks

Azure Notebooks is a hosted service for [Jupyter Notebooks](#jupyter) that
requires no installation.  It enables you to get started quickly on
prototyping, data science, academic research, or learning to program F#,Python or
R.  You can combine code, markdown, images, videos, graphs, all in one format
and easily share with partners.

Best of all, this service is free to use, making it a great environment for:

- Teachers who need a hassle-free F#/Python/R environment for classes,
- Presenters who don't want attendees to spend 45 mins installing software,
- Developers and hobbyist who need a quick coding scratchpad,
- Data scientists who need a full F#, R, Python (Anaconda) environment and don't
  want to spend the time installing everything.

Documentation for Azure Notebooks is found on
[https://docs.microsoft.com/azure/notebooks](https://docs.microsoft.com/azure/notebooks).

## Interesting samples

In addition to the notebooks in this repository, which you can also find on the
[Azure Notebooks samples library](https://notebooks.azure.com/Microsoft/projects/samples),
there are some good external resources as well:

- [Intro to Jupyter notebooks](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)
- [Intro to Data Science](https://github.com/jakevdp/PythonDataScienceHandbook) by Jake Vanderplas
- See the Sample notebooks on the
  [Azure Notebooks](https://notebooks.azure.com/) front page
- A [curated list of interesting Jupyter notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)

Note: You don't need an account to view notebooks, but you will need a
Microsoft account (Outlook, Hotmail, Xbox, etc) to run them.  You will be
prompted to create an account when needed.

## Data sources

There are many interesting sources of data to use in notebooks.  A couple of
good resources are:

- [List of public data sources fit for machine learning](https://blog.bigml.com/list-of-public-data-sources-fit-for-machine-learning/)
- [35 Brilliant and Free Data Sources](http://www.forbes.com/sites/bernardmarr/2016/02/12/big-data-35-brilliant-and-free-data-sources-for-2016/#469939567961)

Note that data must be accessible to the service — you can use Github, Dropbox,
OneDrive, Azure blobs, SQLAzure, and more.

## Jupyter resources

- [Jupyter.org docs](http://jupyter.org)
- [Jupyter on YouTube](https://www.youtube.com/results?search_query=jupyter+notebook+tutorial)
  - [Cell magics](https://youtu.be/zxkdO07L29Q)
  - [Making slide shows with executable code](https://youtu.be/EOpcxy0RA1A)
  - [All about Jupyter](https://www.youtube.com/watch?v=GMKZD1Ohlzk)

## Get involved

* [File an issue](https://github.com/Microsoft/AzureNotebooks/issues/new) for
  bugs, feature requests, etc.  If you need immediate assistance, ping us at
  <nbhelp@microsoft.com>.
* Have a cool notebook you want to share?  Upload & tweet with `#Azurenotebooks`!
* Are you teacher giving a large class or want to give webinar?  Test drive the
  site and if possible give us a heads up on the date & number of users at
  <nbhelp@microsoft.com>.

## [Filing issues](https://github.com/Microsoft/AzureNotebooks/issues/new)

Knowing the context of your issue will help us solve it faster.  Please include
as much of the following as you can when creating a issue:

* Whether the issue is related to Jupyter Notebooks or the Project feature.
* The Jupyter Kernel (`python36`, `python2`, `python3`, `R`, etc) in case of
  problems with a Jupyter Notebook.
* Time of occurrence.
* Web browser the issue occurred in.
* If the issue occurred once or can be reproduced (with steps to repro it).
* Library ID and Notebook Name.
* Logs (`!cat .nb.log` or: New > Terminal, `$ cat .nb.log`).
* Usage scenario: teaching a class, doing homework, evaluating results for
  research.
* Add template to root.

## Short FAQ

### What is Jupyter?

Jupyter (formerly IPython), is a multi-lingual REPL on steroids.  Azure
notebooks is a free service that provides Jupyter notebooks along with
supporting libraries as a service.  It means you can just login and use it, no
installation or setup is necessary.  Instructors can also use the service by
easily sharing a notebook.  Students get their own private copies that they can
run.  The service is provided by the Python team @ Microsoft, which is part of
the Data Group.

### What environments are supported and how can I install packages?

Python 3.6.x and Python 2.7.x (Anaconda3 and Anaconda2 5.3.0), with many
additional packages.
- You can install packages in a Python notebook: `!pip install <pkg-name>`
- You can also install packages using conda:
  `!conda install -y --name root <pkg-name>`

We also support R (3.4.1 running MRO), and F# (4.1).
- To install packages in R: `install.packages("pkg-name")`

See also [our full FAQ](https://notebooks.azure.com/faq).

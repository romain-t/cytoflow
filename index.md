---
layout: default
title: {{ site.name }}
---
# Welcome!  New to Cytoflow?  Start with a [screencast.](https://www.youtube.com/watch?v=vfEfeFGVtro)

# What's wrong with other packages?  

Packages such as FACSDiva and FlowJo are focused on primarily on **identifying
and counting subpopulations** of cells.  While this is important for many
different applications, it reflects flow cytometry's origins in separating
mixtures of cells based on differential staining of their cell surface markers.

Recent experiments in our lab and others have been more interested in
using a cytometer to **compare distributions** of cells, asking how these
distributions change in response to **experimental variables.** Existing
packages don't handle this gracefully!

# How is Cytoflow different?

* An emphasis on **metadata**.  Cytoflow assumes that you are measuring
  fluorescence on several samples that were treated differently: either
  they were collected at different times, treated with varying levels
  of inducers, etc.  You specify the conditions for each sample up front,
  then use those conditions to control the analysis.

* Cytometry analysis represented as a **workflow**. Operations such as
  gating and compensation are applied sequentially; a workflow can be 
  saved and re-used, or shared with your coworkers.

* **Easy to use.**  Sane defaults; good documentation; focused on doing one
  thing and doing it well.

* **Good visualization.**  I don't know about you, but I'm getting really
  tired of FACSDiva plots.

* The point-and-click interface is built on **Python modules**.  Do you 
  analyze data with Python?  If so, head over to the 
  [developer documentation](https://cytoflow.readthedocs.io/) to use these 
  modules in your own workflow.  They have been designed to work well in a 
  [Jupyter notebook](http://jupyter.org/); in fact, the GUI will even export 
  a workflow directly to a notebook!

* **Free and open-source.**  Download the source code from 
  [the GitHub project page](https://github.com/bpteague/cytoflow) and modify it 
  to suit your own needs, then contribute your changes back so the rest of 
  the community can benefit from them.

## Note: this is still beta software!  
## It is stable and full-featured, but you may still encounter bugs!
  
# Installation

**There isn't any!**  The binaries at the top of the page are all you need.
On a Mac, you'll have to extract the ZIP archive -- then, just double-click
to start the program!  It takes a minute to decompress the one-click archive
before it runs, though, so be patient.

# Documentation

You can find the [developer documentation at ReadTheDocs.](https://cytoflow.readthedocs.io/).  GUI documentation for the currently selected operation or
view appears in the "Help" panel in the GUI.  If you don't see a "Help" 
panel, make sure it's activated by going to the "View" menu and selecting
"Help".

# Example Data

The Jupyter notebooks and screencasts use two example data sets.  
If you'd like to play with them yourself, you can download them here:

* [Basic examples](https://github.com/bpteague/cytoflow/releases/download/{{ site.version }}/cytoflow-{{ site.version }}-examples-basic.zip)
* [Advanced examples](https://github.com/bpteague/cytoflow/releases/download/{{ site.version }}/cytoflow-{{ site.version }}-examples-advanced.zip)

# Help!  I found a bug!

First, are you using the current version?  To check, which version 
you're using, go to the Help menu (Windows) or Cytoflow menu (Mac)
and choose "About Cytoflow...".

You can also try to reproduce the bug in the latest build from git HEAD. 
Those binaries are [on BinTray](https://bintray.com/bpteague/cytoflow/cytoflow#files).

If you have found a bug in the most recent version, there are three ways to 
report it.  First, you can navigate to the Help menu and choose "Report a 
problem...".  This will open an email to the developers, including some 
information about the version of cytoflow you're using and some logs.

Second, you can join the 
[cytoflow-dev](https://groups.google.com/forum/#!forum/cytoflow-dev) 
mailing list and communicate your bug to the developers directly.

Finally, you can submit your bug report to the 
[Github issues tracker](https://github.com/bpteague/cytoflow/issues).

# I want to keep up with new Cytoflow releases!

Great!  Subscribe to 
[cytoflow-announce](https://groups.google.com/forum/#!forum/cytoflow-announce) 
and we'll send you an email when a new version is released.


# Are there screenshots?

[There are screenshots.]({{ site.baseurl }}/screenshots.html)

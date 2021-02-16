# Crafting beautiful maps with PyGMT: Tutorial submission for SciPy 2021

<!--
**16 February 2021**  
Tutorial submission deadline

**30 April 2021**  
Tutorial speakers and schedule announced

**11 June 2021**  
Final submission of tutorial materials, software version numbers, and test
scripts

**12–13 July 2021**  
SciPy 2021 tutorials

From the
[SciPy webpage on tutorials](https://www.scipy2021.scipy.org/tutorials), the
following is required:
-->

## Summary

<!--
> A description of the tutorial, suitable for posting on the SciPy website for
  attendees to view. It should include the target audience, the expected level
  of knowledge prior to the class, and the goals of the class.
-->

In many scientific disciplines, accurate, intuitive, and aesthetically pleasing
display of geospatial information is a critical tool. PyGMT (a Python interface to
GMT, the [Generic Mapping Tools](https://www.generic-mapping-tools.org/)) is a mapping
toolbox designed to produce publication-quality figures and maps for insertion into
posters, reports, and manuscripts. This class is geared towards SciPy attendees
interested in creating beautiful maps using Python. Only basic Python knowledge is
needed, and a background in cartography is not required to use PyGMT effectively!
By the end of this tutorial, students will be able to:

* Craft basic maps with geographic map frames using different projections
* Add context to their figures, such as legends, colorbars, and inset overview maps
* Use PyGMT to process PyData data structures (pandas/xarray) and plot them on maps
* Understand how PyGMT can be used for various applications in the Earth sciences and
  beyond!
  
## Presenters

<!--
> A short bio of the presenter or team members, containing a description of
  past experiences as a trainer/teacher/speaker, and (ideally) links to videos
  of these experiences if available.
-->

* [Liam Toney](https://liam.earth/)

Liam (he/him/his) is a PhD student studying seismology and infrasound at the
University of Alaska Fairbanks Geophysical Institute in Fairbanks, Alaska, USA.
He is a contributor to PyGMT and, in summer 2020, taught a module on PyGMT for
the inaugural
[Remote Online Sessions for Emerging Seismologists (ROSES)](https://www.iris.edu/hq/inclass/course/roses)
summer school. The materials for the ROSES module can be found in
[this GitHub repository](https://github.com/fdannemanndugick/roses2020), and a
one-hour-long video recording of part of the course can be viewed on YouTube
[here](https://youtu.be/SSIGJEe0BIk). Liam also led a
[sprint for PyGMT](https://github.com/GenericMappingTools/pygmt/issues?q=label%3Ascipy-sprint)
at SciPy 2020.

* [Wei Ji Leong](https://github.com/weiji14)

Wei Ji (he/him/his) is a PhD student in glaciology at the Antarctic Research
Centre in Wellington, New Zealand, specializing in satellite remote sensing and
deep learning. He is one of the core developers of PyGMT and was the instructor
for the
[PyGMT for Geoscientists workshop](https://2019.foss4g-oceania.org/schedule/2019-11-12?sessionId=SPGUQV)
and [Community Day code sprint](https://2019.foss4g-oceania.org/community-day)
at the FOSS4G Oceania 2019 conference. Jupyter notebooks for the workshop are
available on at
[github.com/GenericMappingTools/foss4g2019oceania](https://github.com/GenericMappingTools/foss4g2019oceania).

* [Tyler Newton](http://tnewton.com/)

Tyler (he/him/his) is a PhD student studying seismology and fault mechanics at
the University of Oregon in Eugene, Oregon, USA. He is a PyGMT contributor and
first got involved with PyGMT during the SciPy 2020 sprint. Tyler has assisted with
teaching computational Earth science, including mapping with GMT, as a teaching
assistant at the University of Oregon. 

* [Meghan Jones]( https://github.com/meghanrjones)

Meghan (she/her/hers) is a postdoctoral researcher at the University of Hawai'i
at Mānoa working on building the GMT developer community, maintaining the GMT
and PyGMT libraries, and refactoring GMT's C source code. She has developed and
taught course material in oceanography and has led informal workshops on data
processing and visualization using GMT.

## Prerequisites

<!--
A list of prerequisite skills expected of attendees, so that participants can
  choose level appropriate tutorials.
-->

Basic Python knowledge (how to install and import packages, how to use positional
and keyword arguments, etc.). No prior mapping experience is necessary!

## Detailed timeline

<!--
> A more detailed outline of the tutorial content, including the duration of
  each part and exercise sessions. Please include a description of how you plan
  to make the tutorial hands-on.
-->
  
The four-hour-long tentative schedule below is based upon content from
[github.com/GenericMappingTools/2020-unavco-course](https://github.com/GenericMappingTools/2020-unavco-course)
and
[github.com/GenericMappingTools/foss4g2019oceania](https://github.com/GenericMappingTools/foss4g2019oceania),
adapted to fit a more general scientific audience. Each of the 30–45 minute sessions
will involve a quick (~10 minute) walkthrough by the speaker, followed by a more
hands-on session in breakout rooms where tutorial participants work on the topic
(using interactive Jupyter notebooks) in a guided environment with one of four
instructors on hand to answer questions.

| Time         | Event                                                                  |
|:-------------|:-----------------------------------------------------------------------|
| 20 minutes   | Introduction and orientation to PyGMT and associated resources         |
| 30 minutes   | Mapping basics (frames, projections, coastlines, etc.)                 |
| 45 minutes   | Plotting basics (lines, points, legends, colorbars, inset maps, etc.)  |
| *10 minutes* | *Break*                                                                |
| 45 minutes   | PyData and PyGMT (`pandas.DataFrame` and `xarray.DataArray` ingestion) |
| 45 minutes   | Applications: <br> 1. LiDAR — Processing 3D point clouds to Digital Elevation Model grids <br> 2. Seismology — Visualizing focal mechanisms from recent earthquakes |
| 30 minutes   | Group projects in breakouts                                            |
| 15 minutes   | Wrap up                                                                |

## Installation instructions

<!--
> Detailed installation instructions for various common Python environments so
  that attendees can have everything ready for participating before heading to
  SciPy.
-->

Installation instructions for PyGMT can be found
[here](https://www.pygmt.org/latest/install.html). To run the tutorial
notebooks, you'll also need to
[install Jupyterlab/Notebook](https://jupyter.org/install).

The tutorial environment, containing both requirements mentioned above, is specified
in the `environment.yml` file found in this repository. It can be installed via
[conda](https://docs.conda.io/en/latest/) with the following command:
```
conda env create -f environment.yml
```

If local installation is challenging or impossible, you can access this environment
on a cloud machine by clicking on the badge below — **but note that your work will
not be saved between sessions with this method, so download your work (e.g.,
notebooks) often!** 🚨

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/GenericMappingTools/scipy2021/main)

## Tutorial material

<!--
> If available, the tutorial notes, slides, exercise files, and IPython
  notebooks, even if they are preliminary.
-->

Jupyter notebooks from previous tutorials and classes are available
[here](https://github.com/GenericMappingTools/foss4g2019oceania) and
[here](https://github.com/fdannemanndugick/roses2020/tree/master/unit08).
These will be modified and expanded to be made more suitable for a general SciPy
audience (i.e., not just Earth scientists 🌎).

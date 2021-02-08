# Crafting beautiful maps with PyGMT: Tutorial submission for SciPy 2021

## Timeline

**16 February 2021**  
Tutorial submission deadline

**30 April 2021**  
Tutorial speakers and schedule announced

**11 June 2021**  
Final submission of tutorial materials, software version numbers, and test
scripts

**12–13 July 2021**  
SciPy 2021 tutorials

## Submission materials

From the
[SciPy webpage on tutorials](https://www.scipy2021.scipy.org/tutorials), the
following is required:

> A short bio of the presenter or team members, containing a description of
  past experiences as a trainer/teacher/speaker, and (ideally) links to videos
  of these experiences if available.

Presenters:
* [Liam Toney](https://liam.earth/)

Liam (he/him/his) is a PhD student studying seismology and infrasound at the
University of Alaska Fairbanks Geophysical Institute in Fairbanks, Alaska, USA.
He is a contributor to PyGMT and, in summer 2020, taught a module on PyGMT for
the inaugural
[Remote Online Sessions for Emerging Seismologists (ROSES)](https://www.iris.edu/hq/inclass/course/roses)
summer school. The materials for the ROSES module can be found in
[this GitHub repository](https://github.com/fdannemanndugick/roses2020), and a
1-hour-long video recording of part of the course can be viewed on YouTube
[here](https://youtu.be/SSIGJEe0BIk). ⚠️  **TODO: Add SciPy 2020 sprint info!** ⚠️

* [Wei Ji Leong](https://github.com/weiji14)

Wei Ji (he/him/his) is a PhD student in Glaciology at the Antarctic Research
Centre in Wellington, New Zealand, specializing in satellite remote sensing and
deep learning. He is one of the core developers of PyGMT and was the instructor
for the [PyGMT for geoscientists workshop](https://2019.foss4g-oceania.org/schedule/2019-11-12?sessionId=SPGUQV)
and [Community Day code sprint](https://2019.foss4g-oceania.org/community-day)
at the FOSS4G Oceania 2019 conference. Jupyter notebooks for the workshop are
available on Github at https://github.com/GenericMappingTools/foss4g2019oceania.

* *Other presenters/team members (if applicable), add your names here!*

> A list of prerequisite skills expected of attendees, so that participants can
  choose level appropriate tutorials.

> A description of the tutorial, suitable for posting on the SciPy website for
  attendees to view. It should include the target audience, the expected level
  of knowledge prior to the class, and the goals of the class.

> A more detailed outline of the tutorial content, including the duration of
  each part and exercise sessions. Please include a description of how you plan
  to make the tutorial hands-on.

> Detailed installation instructions for various common Python environments so
  that attendees can have everything ready for participating before heading to
  SciPy.

Installation instructions for PyGMT can be found
[here](https://www.pygmt.org/latest/install.html). To run the tutorial
notebooks, you'll also need to
[install Jupyter Notebook](https://jupyter.org/install).

The tutorial environment, containing both requirements mentioned above, can be
installed via [conda](https://docs.conda.io/en/latest/) through creation of a
new environment (recommended):
```
conda create --name pygmt --channel conda-forge notebook pygmt
```

You can also use [pip](https://pip.pypa.io/en/stable/)... ⚠️  **TODO: Add pip
instructions, maybe also Binder?** ⚠️

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/GenericMappingTools/scipy2021/main)

> If available, the tutorial notes, slides, exercise files, and IPython
  notebooks, even if they are preliminary.

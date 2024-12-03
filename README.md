# ASTR 3010
## Observational Astronomy

<h1 align="center">
  <a href="https://www.python.org/"><img alt="Python" src="https://img.shields.io/badge/-Python 3.10+-blue?style=for-the-badge&logo=python&logoColor=white"></a>
</h1>

This is the repository for the ASTR 3010 course for UGA@Oxford during the Fall (Michaelmas) 2024 term. It will provide the basic code and information used for the course.

The class format will be 8 one-hour lectures. There will be a total of 5 assignments, the average of which will be the final grade. All assignments will be returned with feedback before the next assignment is released. The grading scale is as follows:

- 100-92%: A
- 91-87%: A-
- 86-85%: B+
- 84-80%: B
- 79-74%: B-
- 74-71%: C+
- 70-67%: C
- 66-65%: C-
- 64-60%: D
- 59-0%: F

"Observational Astronomy" 3rd Ed. by Lena et al. will be the main textbook for the conceptual aspects of the course. It is available via the [UGA library](https://uga.view.usg.edu/content/enforced4/3247905-CO.180.ASTR3010.53676.20252/ObservationalAstrophysics.pdf?ou=3247905_) with proper credentials.

This class will be include pratical lectures. We will use Python for all the programming and data analysis. The data used for the class will mostly be in the form of .fits files, which is the standard format for astronomical data. All data will come from real observatiors, including [JWST](https://mast.stsci.edu/portal/Mashup/Clients/Mast/Portal.html), [MUSE](https://archive.eso.org/eso/eso_archive_main.html), and [ALMA](https://almascience.nrao.edu/aq/). These telescopes are run by [NASA](https://www.nasa.gov/), the [ESO](https://www.eso.org/public/), [STScI](https://www.stsci.edu/), and [NRAO](https://www.nrao.edu/). Any data from these sources must be properly cited in all published work derived from them.

Projects will be almost entirely computational. You will be expected to write code to analyze data and present your results. Jupyter notebooks will be the main format for this. A good project will be one that has well-documented code, makes appropriate visualizations, explains how any conclusions are reached, and includes appropriate citations.

## Tentative Schedule

<h2>Schedule</h2>

<h3>Class 1: Relevant Methods in Python</h3>
<p>Focusing on general Python skills that are used in most astronomical data analysis</p>
<ul>
  <li><strong>Assignment 1:</strong> Python scripting</li>
</ul>

<h3>Class 2: Observations 1</h3>
<p>Quick overview of what observing is, its history, the coordinate systems used, important values, basic concepts, and challenges</p>

<h3>Class 3: Data visualization and manipulation</h3>
<p>Focusing on loading, visualizing, and basic analysis of the main types of astronomical data</p>
<ul>
  <li><strong>Assignment 2:</strong> Presenting and extracting observational data of various types</li>
</ul>

<h3>Class 4: Spectral analysis</h3>
<p>Introduction to spectral data with a particular focus on .fits files, integral field spectroscopy, and basic analysis</p>
<ul>
  <li><strong>Assignment 3:</strong> Spectral fitting and analysis in Python using MUSE data</li>
</ul>

<h3>Class 5: Observations 2</h3>
<p>Overview of basic technologies used in visible, IR, and radio observations</p>

<h3>Class 6: Photometry</h3>
<p>Focusing on detecting and cleaning photometric data</p>
<ul>
  <li><strong>Assignment 4:</strong> Galaxy detection and segmentation using JWST data</li>
</ul>

<h3>Class 7: Observations 3</h3>
<p>Overview of UV, X-ray, (gamma ray and neutrino if time) astronomy</p>

<h3>Class 8: Modern Techniques</h3>
<p>Exoplanet detection methods, basic machine learning, other topics of interest (feel free to recommend something that you’re interested in!)</p>
<ul>
  <li><strong>Assignment 5:</strong> Full data analysis and presentation pipeline with ALMA and/or JWST data</li>
</ul>

## Necessary Software

- [Python 3.10+](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Astropy](https://www.astropy.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciPy](https://www.scipy.org/)
- More to come...

We will be using lots of .fits files. When working with these in Python/Jupyter, I recommend using the [Astropy](https://docs.astropy.org/en/stable/io/fits/index.html) library. There are several packages that let you visualize .fits files, but I recommend using [QFitsView](https://www.mpe.mpg.de/~ott/QFitsView/), [CARTA](https://cartavis.org/), or [DS9](https://sites.google.com/cfa.harvard.edu/saoimageds9) for this purpose. Some don't play well with different versions of Mac (e.g., you might not be able to open .fits files directly from the finder), but they are all free and open source.




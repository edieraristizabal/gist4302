---
layout: base
Author: Guofeng Cao
---

# [GIST 4302/5302: Spatial Analysis and Modeling](http://www.gis.ttu.edu/gist4302)

| **Instructor:** | **Dr. Guofeng Cao**|  **TA: Tarek Kandakji**            |
|----------------- |:----------------------------------- |:----------------------------------- | 
|**Office** | Holden Hall 211   |  Holden Hall 218                   |
|**Office hours**| TR 1:30-3:30pm or by appointment | T,TR 1:30-2:30pm or by appointment             | 
|**Email**| guofeng.cao@ttu.edu | tarek.kandakji@ttu.edu           |

## Prerequisites

Prerequisites of this course includes an understanding of basic algebra,
general statistics (e.g., knowledge of statistical significance) and matrix
manipulations, and working knowledge of at least one GIS software packages,
e.g. ArcGIS, which could be fulfilled with *GIST 3300/5300*. However,
students from different disciplines are welcome, please contact the
instructor should there any question about the prerequisites.

## Course description

With the continuing advances of technological development, spatial data
have been easily and increasingly available in the past decades and
becoming important information sources in daily decision makings. This
class is intended for students (undergraduate and graduate students)
from relevant disciplines (e.g., geography, geology, environmental
science and social sciences) who are interested in analysis of spatial
data. Students will be encouraged to engage this course with their
thesis/dissertation topics and research interests.

This course will introduce fundamental concepts and commonly used
methods in quantitative analysis of spatial data. Specifically, this
course includes:

-   Representation of spatial data (fundamentals in spatial databases)

-   Concepts in spatial analysis and spatial statistics

-   Spatial analysis methods for various types of spatial data (spatial
    points, networks, and areal/lattice data), including
    overlay/suitability analysis, spatial statistical methods such as
    exploratory spatial data analysis (e.g., Moran’s I), spatial
    interpolation (e.g. kriging) and spatial regression.

A lab/discussion session (approximately *2* hours) follows the lecture
for students to gain hands-on experiences on real-world datasets by
using multiple software tools. The software packages utilized in lab
sessions include ArcGIS, Open GeoDa, R or Matlab. Students ( in
particular) with expertise or interest in the statistical package R or
Matlab are encouraged to use them but it is not required.

## Course Schedule
<!--
|Week |Lecture Dates| Lecture Topics | Readings | Lab/Discussion Topics |
| --- | ----------- | -------------- | -------- | --------------------- |
|1    |Jan. 19 |[Overview of the course](blob/lectures/lecture1.pdf); |   | No lab | 
|2    | Jan. 24, Jan. 26|[Introduction to spatial analysis](blob/lectures/lecture2.pdf)| O'S & U ch.1   | Review of map projection and ArcGIS |
|3    |Jan 31, Feb. 2  |Spatial representation: [vector analysis](blob/lectures/lecture3.pdf); [compact version of the slides](blob/lectures/lecture3-compact.pdf)| O'S & U ch.1 and 10  | Spatial query I |
|4    |Feb. 7, 9 |Spatial representation: vector analysis| O'S & U ch.1 and 10   |Spatial query II |
|5    |Feb 14, 16 |Spatial representation: raster analysis | O'S & U ch.1 and 10   |Raster analysis I | 
|6    |Feb 21, 23 |Spatial representation: raster analysis, [geocoding](blob/lectures/lecture4.pdf)| O'S & U ch.1 and 10  | Model builder | 
|7    |Feb 28, Mar 2 |[Statistics review; pitfalls and potential of spatial data](blob/lectures/lecture5-statistics.pdf) | O'S & U ch.2, 3 and Appendix  | Geocoding; Homework assignment |
|7    |Feb 28, Mar 2 |Statistics review; pitfalls and potential of spatial data | O'S & U ch.2, 3 and Appendix A-B  | Geocoding; Homework assignment | 
|8    | Mar 7, 9 |[review](blob/lectures/review.pdf); midterm |   |Project discussion |
|9    | Mar 14, 16 | Spring break|  | |
|10    | Mar 21, 23 |[Point pattern analysis](blob/lectures/lecture6.pdf)| O'S & U ch.4 and 5  |Point pattern analysis |
|11    | Mar 28, 30 |[Spatial statistics of areal objects & exploratory analysis](blob/lectures/lecture7.pdf)| O'S &U ch.7 | Mapping and cluster detection with GeoDa | 
|12   | Apr 4, 6 |Spatial statistics of areal objects & exploratory analysis| O'S &U ch.7 | Regression with GeoDa ; Proposal due | 
|13   | Apr 11, 13  |Spatial regression| handouts  |Regression with GeoDa |
|14   | Apr 18, 20  |Spatial regression| handouts |Spatial interpolation |
|15   | Apr 25, 27  |[Spatial interpolation](blob/lectures/lecture8.pdf)| O'S&U ch.8 and 9 | Class project|
|16   | May 2, 4 |Spatial interpolation| O'S&U ch.8 and 9 |Class project |
|17   | May 9 | [Review](blob/lectures/review2.pdf)|  | Project presentation |
|18   | May 16 1:30-4:00pm  | Final |  | |
-->

|Week |Lecture Dates| Lecture Topics | Readings | Lab/Discussion Topics |
| --- | ---------| --------------------------- | -------| --------------------------- |
|1    |Aug 29, Aug 31|[Overview of the course](blob/lectures/lecture1.pdf); [Introduction to spatial analysis](blob/lectures/lecture2.pdf)| O'S & U ch.1   | Review of map projection and ArcGIS | 
|2    |Sept 5, 7  |Spatial representation: [vector analysis](blob/lectures/lecture3-vector.pdf)| O'S & U ch.1 and 10  | Spatial query I |
|3    |Sept 12, 14 |Spatial representation: vector analysis| O'S & U ch.1 and 10   |Spatial query II |
|4    |Sept 19, 21 |Spatial representation: [raster analysis](blob/lectures/lecture3-raster.pdf) | O'S & U ch.1 and 10   |Raster analysis | 
|5    |Sept 26, 28 |Spatial representation: raster analysis, [geocoding](blob/lectures/lecture4.pdf)| O'S & U ch.1 and 10  | Model builder | 
|6    |Oct 3, 5 |[Statistics review; pitfalls and potential of spatial data](blob/lectures/lecture5.pdf) | O'S & U ch.2, 3 and Appendix A-B  | Geocoding and homework assignment | 
|8    | Oct 10, 12 |Student project discussion; [midterm review](blob/lectures/review.pdf)|  | Project discussion |
|7    | Oct 17, 19 |Point pattern analysis| O'S & U ch.4 and 5  | Point pattern analysis |
|9    | Oct 24, 26 |Spatial statistics of areal objects & exploratory analysis| O'S &U ch.7 | Getting started with GeoDa | 
|10   | Oct 31, Nov 1  |Spatial statistics of areal objects & exploratory analysis| O'S &U ch.7 | Mapping and cluster detection with GeoDa ; Proposal due | 
|11   | Nov 7, 9  |Spatial interpolation| handouts  |Spatial interpolation I |
|12   | Nov 14, 16 |Spatial interpolation| handouts |Spatial interpolation II |
|13   | Thanksgiving  | Fall break |  | |
|14   | Nov 28, Nov 30 |Spatial interpolation| O'S&U ch.8 and 9 |Class project |
|15   | Dec 5 | Review|  | Project presentation |
|16   | Dec 9 10:30am-1:00pm  | Final |  | |

## Learning outcomes

After completing this course, the **undergraduate** of this class are expected to learn
how to:

-   formulate real-world problems in the context of geographic
    information systems and spatial analysis

-   apply appropriate spatial analytical methods to solve the problems

-   utilize mainstream software tools (commercial or open-source) to
    solve spatial problems

-   communicate results of spatial analysis in the forms of writing and
    presentation

In addition to the above, the **graduate** students of this class are expected to learn

-   the concept of spatial uncertainty

-   commonly used spatial statistical methods work and connect them to
    the thesis and dissertation work

-   evaluation and assessment of the results of alternative methods


## Readings

The main course text is:

-   O’Sullivan, David and David J. Unwin (2010), *Geographic Information
    Analysis, 2nd Edition*, John Wily & Sons. The first edition of this
    book works in the most cases as well.

The following book will be helpful for some topics of this class.
Additional readings and handouts ill be suggested as the class
progresses.

-   de Smith, Michael J., Paul A. Longley and Michael F. Goodchild
    (2013), *Geospatial Analysis: A Comprehensive Guide to Principles,
    Techniques and Software Tools, 4th Edition*. Available in both print
    and web () version at <http://www.spatialanalysisonline.com>

For the lab assignments, you have different options of software tools to
choose from. If using ArcGIS, you might find the following book helpful:

-   Allen, David W. (2011), *GIS Tutorial 2, Spatial Analysis Workbook
    for ArcGIS 10*, Esri Press.

-   Mitchell, A. (2009), *The ESRI Guide to GIS Analysis, vol. 2:
    spatial measurements and statistics*, ESRI Press.

if using R:

-   Bivand Roger S., Pebesma, Edzer J., and Gómez-Rubio, Virgilio
    (2008), *Applied Spatial Data Analysis with R*, Springer.

if using Matlab:

-   Martinez, W.L. and Martinez, A.R. (2007), *Computational Statistics
    Handbook with MATLAB, 2nd Edition*, Taylor & Francis – Chapman
    & Hall/CRC.

## Assessment

There are two written exams in this course (a midterm and a final), lab
exercises, and a final project that includes a project proposal and final
report. **Graduate students** will have extra questions for the lab and the
exams, and higher standard for the final project outcomes.  The exams are
used to assess your understanding of the basic concepts discussed in the
lecture, and the format of the exams will consist of a combination of
multiple choice, short answer and short essay questions. 

The purpose of the final project is to provide experiences for students to
apply the methods and tools learned from this class to real-world spatial
problems.  Topics of the final project could be related to the spatial
aspect of a thesis or another course work. The proposal associated with the
final project should include a clear description of the proposed problems
with appropriate background literatures justifying the motivation,
description of the collected data sources, and methodology adopted to
address the problem.  When the project proposal is due (Nov.3rd), students
are expected to have collected the necessary data at hand. The final
project will require a presentation of about 6-10 mins [*PechaKucha
style*](http://en.wikipedia.org/wiki/Pecha_Kucha) or a poster session, and
a final project report. Students are encouraged to start thinking of
project ideas early in the semester, and communicate them with the
instructor and the TA for feedbacks and comments.

## Grading

Each exam, lab exercise and final project is worth $100$ points, and the
final points will be a combination of these three elements according to
the following weights:

-   two written exams: 30% (each 15%)

-   six (out of ten) lab exercises: 40% (each ~ 6.6%)

-   final project proposal (5%), presentation (10%) and paper (15%) :
    30%

To ensure a specific grade in this course you must meet the following
minimum requirements: A - 90%, B - 80%, C - 70%, D - 60%.

## University policy

-   Academic honesty (OP 34.12):
    <http://www.depts.ttu.edu/opmanual/OP34.12.pdf>

-   Students with disabilities (OP 34.22):
    <http://www.depts.ttu.edu/opmanual/OP34.22.pdf>

-   Students absence for observance of a religious holy day (OP 34.19):
    <http://www.depts.ttu.edu/opmanual/OP34.19.pdf>


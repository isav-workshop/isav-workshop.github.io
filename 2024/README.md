---
title: "ISAV 2024: In Situ Infrastructures for Enabling Extreme-scale Analysis and Visualization"
description: >
  Information for the SC'24 conference ISAV workshop
year: 2024
current: true
permalink: /2024/
---

<style type="text/css">

#isav-sc24-banner {
    margin: 2px 2px 2px 2px;
    background: url("/2024/isav24_logo.png") 0 0 no-repeat;
    height: 130px;
    border: 0px solid white;
    border-bottom: 0px solid beige;
    align: center;
}

.container-lg > h1:first-of-type {
    display: none;
}

p { text-align: justify; }

</style>

<div id="isav-sc24-banner"> </div>

# ISAV 2024: In Situ Infrastructures for Enabling Extreme-scale Analysis and Visualization

<p style="text-align: left;" markdown="1">

<br>

 In conjunction with:  
[SC24, The International Conference for High Performance Computing, Networking, Storage, and Analysis](https://sc24.supercomputing.org) <br>
<br>
Sunday, 17 November 2024, 2 pm - 5:30 pm EDT <br>

</p>

## Workshop Theme

In situ analysis and visualization are essential workflow components in modern HPC due to several factors.
First are significant cost savings, directly addressing the growing compute to I/O bandwidth gap as data is analyzed/visualized while being generated, without first storing to a file system.
Second is the potential for increased accuracy, where fine temporal sampling of transient analysis might expose some complex behavior missed in coarse temporal sampling.
Third is the ability to achieve speedups by using fully parallel resources, CPUs and accelerators, in the computation of analysis products.

The workshop brings together researchers, developers and practitioners from industry, academia, and government laboratories developing, applying, and deploying in situ methods in extreme-scale, high performance computing.
The goal is to present research findings, lessons learned, and insights related to developing and applying in situ methods and infrastructure across a range of science and engineering applications in HPC environments; to discuss topics like opportunities presented by new architectures, new domain science applications, existing infrastructure needs, requirements, and gaps, and experiences to foster and enable in situ analysis and visualization. ISAV aims to serve as a "center of gravity" for researchers, practitioners, and users/consumers of in situ methods and infrastructure in the HPC space.
Consequently, reflections on the development of this area of research as well as possible future directions and trends are also welcome.


## Participation/Call for Papers

We invite two types of submissions to ISAV 2024:
(1) short, 5-page (+references) papers that present research results, that identify opportunities or challenges, and that present case studies/best practices for in situ methods/infrastructure in the areas of data management, analysis and visualization;
(2) lightning presentation submissions, consisting of a 1- or 2-page (+references) submission, for a brief oral presentation at the workshop.
Short papers will appear in the workshop proceedings and authors will be invited to give an oral presentation of 15 to 20 minutes; lightning round submissions invited to present at the workshop will have author names and titles included as part of the proceedings. Submissions of both types are welcome that fall within one or more areas of interest.
Areas of interest for ISAV include, but are not limited to:
* **In situ infrastructures:** Novel designs for systems and libraries; Opportunities; Gaps
* **System resources, hardware, and emerging architectures:** Elasticity, Cloud-, HPC-, and/or Edge-based approaches; Enabling Hardware; Hardware and architectures that provide opportunities for In situ processing, such as burst buffers, staging computations on I/O nodes, sharing cores within a node for both simulation and in situ processing; Efficient use of heterogeneous architectures.
* **Methods/algorithms:** Best practices; Analysis: AI/ML, feature detection, statistical methods, temporal methods, geometric and topological methods; Visualization: information visualization, scientific visualization, time-varying methods; Data reduction/compression.
* **Case Studies and Data Sources:** Examples/case studies of solving a specific science challenge with in situ methods/infrastructure; In situ methods/systems applied to data from simulations and/or experiments/observations.
* **Simulation and Workflows:** Integration, data modeling, software-engineering; Resilience: error detection, fault recovery; Workflows for supporting complex in situ processing pipelines.
* **Requirements and Usability:** Reproducibility, provenance and metadata; Using in situ to enable rapid and flexible post-processing; Simplified access to extreme heterogeneous resources; real-time coupling of computing / "digital twins" with physical measurements.

For the submissions we are not only looking for success stories, but are also particularly interested in those experiments that started with a certain goal or idea in mind, but later were shattered by reality or insufficient hardware/software. What in situ methods are used or needed in practice of scientific/academic/industry with HPC, cloud and edge computing? What are the reasons for adoption or avoidance of methods and products and where should in situ processing go from here?


## Review Process

All submissions will undergo a peer-review process consisting of three reviews by experts in the field, and evaluated according to relevance to the workshop theme, technical soundness, creativity, originality, and impact of method/results.
Lightning round submissions will be evaluated primarily for relevance to the workshop.


## Submission Process

Authors are invited to submit papers of at most 5 pages in PDF format, excluding references, and lightning presentations of at most 2 pages in PDF format, excluding references.
Papers must be submitted in PDF format (readable by Adobe Acrobat Reader 5.0 and higher) and formatted for 8.5in x 11in (U.S. Letter).

In earlier editions of the workshop a +1 spillover page for references was granted during review.
Note that this changed and is now 5 + 1 from the beginning.

All authors must use the new proceedings templates and the CCS2012 guide that are available at:
[http://www.acm.org/publications/article-templates/proceedings-template.html](http://www.acm.org/publications/article-templates/proceedings-template.html).
Authors must use the ``sigconf`` template variant, as shown in ``samples/sample-sigconf.tex`` in the downloadable archive.

We believe that reproducible science is essential, and that SC should be a leader in this effort.
As a consequence, ISAV 2024 participates in the SC reproducibility initiative and encourages submitters to include an appendix with reproducibility information.
While we will not disqualify a paper based on information provided or not provided in this appendix, nor if the appendix is not available, the availability and quality of an appendix will be used in ranking a paper.
For more information, see the [ISAV reproducibility FAQ](https://docs.google.com/document/d/1nGkpXf5yFq-00TxzRKEatbDe7FkwE219VM4ctBtJiS0/edit?usp=sharing).

Papers must be self-contained and provide the technical substance required for the program committee to evaluate their contributions.
Submitted papers must be original work that has not appeared in and is not under consideration for another conference or a journal.

Papers may be submitted using this link (TBD).
A preview of the paper submission form is available at this link (TBD).


## Publication in proceedings, presentation at the workshop

All paper submissions that receive favorable reviews will be included as part of the workshop proceedings, which will be published.
Lightning round submissions and the keynote speaker abstract will not be included as part of the proceedings.
Subject to the constraints of workshop length, some subset of the accepted publications will be invited to give a brief oral presentation at the workshop.
The exact number of such presentations and their length will be determined after the review process has been completed.

[Last year's ISAV 2023 Proceedings are online.](https://dl.acm.org/doi/proceedings/10.1145/3624062#heading20)

Update on September, 8th:
We received 14 submissions, 12 short papers and 2 lightning talks.
Each submission received 5 reviews.
After all reviews were submitted, the reviewers held an online discussion of their impressions and ratings.
Based on the review ratings and reviewer discussions, we decided to accept 3 full papers and 9 lightning talks.


## Timeline/Important Dates

:------------------|:--------------------------------------
02 Aug 2024        | Paper submission deadline
06 Sep 2024        | Author notification 
15 Sep 2024        | Camera ready copy due (note: this deadline is FIRM)
Nov 2024           | ISAV'24 workshop at SC24


## Committees and Chairs

#### Chairs

  * General chair: Matt Larsen, *Luminary Cloud, USA*
  * General co-chair: Axel Huebl, *Lawrence Berkeley National Laboratory, USA*
  * Program chair: Will Usher, *Luminary Cloud, USA*
  * Program co-chair: Estelle Dirand, *TotalEnergies, France*
  * Publicity chair: Earl Duque, *Intelligent Light, USA*
  * Publication chair: Nicola Ferrier, *Argonne National Laboratory, USA*
  * Early Career Program Committee Chair: Silvio Rizzi, *Argonne National Laboratory, USA*
  * At-large Chair: E. Wes Bethel, *San Francisco State University and Lawrence Berkeley National Laboratory, USA*

#### Organizing Committee

  * Sean Ziegeler, *US Department of Defense HPC Modernization Program / GDIT, USA*
  * Axel Huebl, *Lawrence Berkeley National Laboratory, USA*
  * Nicola Ferrier, *Argonne National Laboratory, USA*
  * Matt Larsen, *Luminary Cloud, USA*
  * E. Wes Bethel, *San Francisco State University and Lawrence Berkeley National Laboratory, USA*
  * Earl Duque, *Intelligent Light, USA*
  * Christoph Garth, *University of Kaiserslautern, Germany*
  * Kenneth Moreland, *Oak Ridge National Laboratory, USA*
  * Patrick O'Leary, *Kitware, USA*
  * Guido Reina , *University of Stuttgart, Germany*
  * Silvio Rizzi,  *Argonne National Laboratory, USA*
  * Tom Vierjahn, *Westphalian University of Applied Sciences, Germany*
  * Gunther H. Weber, *Lawrence Berkeley National Laboratory, USA*
  * Matthew Wolf, *Samsung Electronics, USA*
  * Sean Ziegeler, *US Department of Defense HPC Modernization Program / GDIT, USA*

#### Program Committee

To be announced soon

#### Best Paper Committee

TBD

### Contact Us
 * Matt Larsen, General Chair, matt at luminarycloud dot com
 * Will Usher, Papers Chair, will at willusher dot io

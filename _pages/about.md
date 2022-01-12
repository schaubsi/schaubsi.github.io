---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a postdoctoral researcher at the [Visual Inference Lab](https://www.visinf.tu-darmstadt.de/) at the Technical University of Darmstadt since September 2020. Since December 2021 am leading the newly founded group EVA. I obtained my doctoral degree from [ETHZ](https://www.inf.ethz.ch/) in 2018, advised by Prof. Dr. Markus Gross and in collaboration with [Disney Research Zurich](https://studios.disneyresearch.com/). My research interests lie at the intersection of computer vision, computer graphics, and machine learning with a focus on motion representation, temporal interpolation, and video frame synthesis. Prior to joining TU Darmstadt I was a postdoctoral researcher at the [Media Technology Lab](https://mtc.ethz.ch/) at ETH Zurich working on augmented reality.

The data-Efficient Video Analysis (EVA) group is researching novel AI methods for visual data with a focus on developing efficient, robust and controllable methods and algorithms that can learn from limited data by exploiting low-level perception and high-level reasoning. EVA has been created as a DEPTH research group within the HMWK-funded cluster project "The Third Wave of Artificial Intelligence (3AI)". The cluster project is embedded into [hessian.AI](https://hessian.ai), the Hessian Centre for Artificial Intelligence, with its mission to “understand the interplay of AI algorithms, AI systems, and synergies between artificial and natural intelligence to provide the foundation for AI transformation”.

## News
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include news.html %}


## Publications
<style style="text/css"> .hoverTable{ width:85%; border-collapse:collapse; border: 0px; } .hoverTable td{ padding:7px; border:#4e95f4 0px solid; } /* Define the default color for all the table rows */ .hoverTable tr{ background: #ffffff; } /* Define the hover highlight color for the table row */ .hoverTable tr:hover { background-color: #f7f7f7; } </style> {% for post in site.publications reversed %} {% include publications.html %} {% endfor %}
---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am an independent research group leader (Image & Video Analysis) at the Technical University of Darmstadt, as well as affiliated with the Hessian Center for Artificial Intelligence ([hessian.AI](https://hessian.ai)). I recently got the renowned [Emmy Noether Programme](https://www.dfg.de/en/research-funding/funding-opportunities/programmes/individual/emmy-noether) (ENP) fund of the German Research Foundation (DFG) supporting my research group. The focus of my research is on developing efficient, robust, and understandable methods and algorithms for image and video analysis. Before starting my own group, I was a postdoctoral researcher in the [Visual Inference Lab](https://www.visinf.tu-darmstadt.de/visual_inference/index.en.jsp) of Prof. Stefan Roth. Prior to joining TU Darmstadt, I was a postdoctoral researcher at the [Media Technology Center](https://mtc.ethz.ch/) at ETH Zurich working on augmented reality. I obtained my doctoral degree from [ETH Zurich](https://inf.ethz.ch/de/news-und-veranstaltungen/spotlights/2019/11/ETHmedalDoctoral.html), advised by Prof. Dr. Markus Gross and in collaboration with [Disney Research Zurich.](https://studios.disneyresearch.com/) In my doctoral thesis, awarded with the ETH Medal, I developed novel methods for motion representation and video frame interpolation.

I also head the Efficient Video Analysis (EVA) project group at [hessian.AI](https://hessian.ai),  researching novel AI methods for visual data with a focus on developing efficient, robust, and controllable methods and algorithms that can learn from limited data by exploiting low-level perception and high-level reasoning. EVA has been created as a DEPTH research group within the HMWK-funded cluster project "The Third Wave of Artificial Intelligence (3AI)". The cluster project is embedded into [hessian.AI](https://hessian.ai), the Hessian Centre for Artificial Intelligence, with its mission to “understand the interplay of AI algorithms, AI systems, and synergies between artificial and natural intelligence to provide the foundation for AI transformation”.


## News
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include news.html %}


## Publications
<style style="text/css"> .hoverTable{ width:85%; border-collapse:collapse; border: 0px; } .hoverTable td{ padding:7px; border:#4e95f4 0px solid; } /* Define the default color for all the table rows */ .hoverTable tr{ background: #ffffff; } /* Define the hover highlight color for the table row */ .hoverTable tr:hover { background-color: #f7f7f7; } </style> {% for post in site.publications reversed %} {% include publications.html %} {% endfor %}
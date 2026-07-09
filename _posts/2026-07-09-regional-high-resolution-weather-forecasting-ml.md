---
layout: single
title: "Towards Regional High-Resolution Weather Forecasting with Machine Learning"
date: 2026-07-03
categories:
  - Blog
tags:
  - Artificial Intelligence
  - Machine Learning
  - Weather Forecasting
  - Regional Modeling
  - High-Resolution Forecasting
excerpt: "A panel reflection on regional machine-learning weather forecasting — from limited-area and stretched-grid models to probabilistic prediction, operational trust, and locally deployable forecasting systems."
author_profile: false
---

As part of the Machine Learning for Earth System Modeling training course, I had the pleasure of moderating a panel discussion on “Towards Regional High-Resolution Weather Forecasting with Machine Learning.” The discussion brought together experts from Met Norway, ETH Zürich, DWD, the Finnish Meteorological Institute, and ECMWF, spanning regional AI forecasting, limited-area modeling, stretched-grid approaches, operational forecasting, and deployable AI-based forecast systems.

The motivation for the panel was clear: while global machine-learning weather prediction models have developed rapidly, many of the most important forecast decisions are regional and local. In high-resolution weather forecasting, users often care most about details — precipitation, wind, complex terrain, aviation-relevant variables, local extremes, and warning-relevant events. This raises an important question: how should machine-learning models be designed, trained, verified, and integrated when the target is not only global skill, but local usefulness?

A central theme was the diversity of current pathways. Some groups are developing limited-area models in which a regional ML model is driven by information from a larger-scale global model. Others are exploring stretched-grid models, where the model remains global but has enhanced resolution over a region of interest. A third pathway is downscaling or super-resolution, where coarse forecasts are transformed into locally detailed products. The discussion made clear that there is no single obvious winner yet. Each approach has strengths and weaknesses, depending on the available data, computing resources, operational workflow, and target application.

The panel also highlighted how many open scientific questions remain. How should information pass between coarse and high-resolution domains? How sensitive are regional ML models to the data on which they are trained? Can models trained in one region transfer reliably to another climate regime or terrain type? How do we preserve large-scale consistency while adding local detail? These questions are especially important because regional forecasting often depends on physical features that are not easy to learn from limited training data alone, such as orography, land use, vegetation, coastlines, and local convective behavior.

Another important discussion focused on probabilistic forecasting. At high resolution, deterministic models can easily become overly smooth, especially for variables such as precipitation that are uncertain and intermittent. Probabilistic training approaches, including CRPS-based methods, offer a way to represent uncertainty more directly and to produce ensemble forecasts that better reflect the range of plausible outcomes. This is particularly relevant for regional forecasting, where users often need to know not only what is most likely, but also what could happen in warning-relevant situations.

Operational trust was another recurring theme. Regional ML forecasts cannot simply be judged by aggregate scores. They need to be examined in real forecast workflows, compared with existing numerical models, evaluated in key local cases, and discussed with forecasters. Several panelists emphasized the value of running these models in pre-operational mode, exposing forecasters to the products early, collecting feedback, and gradually building experience. Trust emerges not only from verification statistics but also from repeated use in situations that matter.

The panel closed with a discussion of Forecast-in-a-Box, an ECMWF-led open-source effort to package AI weather models together with the tools needed to retrieve initial conditions, run forecasts, compute downstream products, and visualize results. I found this part especially interesting because it shifts the discussion from models alone to usable forecasting systems. If AI forecasts are fast, lightweight, and portable, then regional forecasting could become more accessible — not only for national weather services, but also for partners in data-sparse regions and local user communities.

From my perspective as a moderator, the discussion showed that regional ML-based weather forecasting is entering a very exciting yet still exploratory phase. There is enormous freedom in how these systems can be built: limited-area models, stretched grids, downscalers, probabilistic ensembles, task-specific decoders, and portable forecast platforms. At the same time, this freedom brings responsibility. The community still needs to understand when these models work, where they fail, how they respond to new regions and extremes, and how they can be trusted in operational warning contexts.

The future of regional high-resolution weather forecasting with machine learning will likely not be defined by a single architecture. Instead, it may involve a combination of regional models, global AI systems, physical models, local observations, probabilistic methods, and operational expertise. The challenge ahead is to turn this growing set of tools into forecast systems that are not only fast and skillful but also reliable, interpretable, and locally useful.

A recording of the panel discussion is available on YouTube:

[Watch the panel discussion](https://www.youtube.com/watch?v=ROPD9pPtFtA)

---
layout: single
title: "Predictability for AI-Based Earth System Models"
date: 2026-02-16
categories:
  - Blog
tags:
  - Artificial Intelligence
  - Machine Learning
  - Earth System Modeling
  - Weather Forecasting
  - Predictability
  - Uncertainty
excerpt: "A podcast reflection on predictability in AI-based Earth system models — from deterministic chaos and ensemble forecasting to the butterfly effect, uncertainty growth, and the limits of current AI weather models."
author_profile: true
---

As part of the Machine Learning for Earth System Modeling training series, I had the pleasure of recording a podcast with Tobias Selz from the Karlsruhe Institute of Technology on “Predictability for AI-Based Earth System Models.” The conversation focused on one of the most fundamental questions in weather and climate science: what makes the atmosphere predictable, what limits that predictability, and how well current AI-based weather models represent uncertainty growth.

We began with the basic idea of predictability. Weather prediction is based on deterministic equations, but this does not mean that the future can be predicted indefinitely. The atmosphere is highly sensitive to initial conditions: even very small errors in our estimate of the current state can grow with time. This is why ensemble forecasts are so important. They do not simply provide many versions of the same forecast; they help us estimate how uncertainty evolves and when a forecast may no longer be useful.

A key part of the discussion was the scale dependence of predictability. Small-scale systems, such as convective clouds, typically lose predictability within hours, while larger systems, such as cyclones, can remain predictable for several days. This means that predictability is not a single fixed number. It depends on the atmospheric situation, the spatial scale, the variable of interest, and how much uncertainty a user is willing to tolerate.

The podcast then moved to the butterfly effect. Tobias explained that the butterfly effect is not simply another name for chaos, but a particular process in which very small initial perturbations first affect small scales and then grow upscale through interactions across scales. In the atmosphere, this can eventually limit predictability even at planetary scales. The current estimate for this fundamental limit is roughly two weeks, although present-day operational forecasts are still mostly limited by larger initial-condition uncertainties rather than true butterfly-like perturbations.

This distinction becomes especially important for AI-based weather models. Current AI models appear to represent the growth of large-amplitude uncertainties reasonably well. In other words, when the initial perturbations resemble the uncertainty levels seen in operational forecasting, these models can capture many aspects of uncertainty growth. However, when the perturbations are reduced to very tiny, butterfly-like amplitudes, the AI models studied so far do not reproduce the expected upscale growth process. Instead, they tend to treat these tiny perturbations more like larger ones.

This raises an important scientific question: are current AI weather models learning the relevant physical mechanisms of predictability, or are they mainly learning the dominant patterns present in their training data? The answer may depend on the amplitude and scale of the perturbations. If the relevant processes are not resolved, such as small-scale convection, then the model may struggle to represent how uncertainty should initially grow and cascade across scales.

Another interesting point in the conversation was trust. If a model result changes depending on whether it is run on a CPU or GPU, then it becomes difficult to interpret that result as physically meaningful. For scientific questions such as the butterfly effect, where we cannot create a second physical copy of the Earth to test perturbations directly, we must rely on models. This makes it especially important to compare AI models with physically based numerical models, theoretical arguments, and process-level diagnostics.

From my perspective, the podcast highlighted a useful distinction between AI models as forecasting tools and AI models as scientific tools. For medium-range weather prediction, current AI models are already extremely promising, and the butterfly effect may not yet be the main practical limitation. But if we want AI models to answer deeper scientific questions about predictability, uncertainty growth, and the fundamental limits of weather prediction, then they must be tested in ways that go beyond standard forecast scores.

The future research challenge is therefore twofold. First, AI weather models need to keep improving as practical forecasting systems: higher resolution, better stability, better limited-area capability, and more reliable probabilistic forecasts. Second, if we want to use them for scientific understanding, they must be able to represent uncertainty growth across scales, including the small-amplitude perturbations that underlie the butterfly effect.

A recording of the podcast is available on YouTube: [Watch the podcast](https://www.youtube.com/watch?v=9pHsZGEW9fM&list=PLwv2rZ5UPWUH9rIJn1klqvKl9VvIV_EvY&index=9)

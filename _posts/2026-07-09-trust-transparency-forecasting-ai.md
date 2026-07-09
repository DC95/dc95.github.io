---
layout: single
title: "Trust, Transparency, and the Changing Skill of Forecasting in the Age of AI"
date: 2026-02-11
categories:
  - Blog
tags:
  - Artificial Intelligence
  - Weather Forecasting
  - Operational Forecasting
  - Trust
  - Verification
excerpt: "A podcast reflection on how AI is changing operational weather forecasting — from trustworthy AI workflows and human-in-the-loop systems to verification, data assimilation, and the evolving role of meteorological expertise."
author_profile: false
---

As part of the Machine Learning for Earth System Modeling training series, I had the pleasure of recording a podcast with Stefanie Hollborn from the German Weather Service, Deutscher Wetterdienst (DWD), on “Trust, Transparency, and the Changing Skill of Forecasting in the Age of AI.” The conversation focused on how a national meteorological service can adopt AI not only as a research tool, but as part of operational forecasting, service delivery, verification, and organizational change.

A central theme of the discussion was that AI at a weather service is not only about building a better model. It is also about building trustworthy workflows around that model. At DWD, this includes both physics-based AI, such as machine-learning weather prediction models, and language-based AI, such as secure interfaces to large language models. These two areas have different goals, but both require careful attention to transparency, privacy, reliability, and user trust.

One important example was FRAIM, the Framework for Artificial Intelligence in Meteorology. Stefanie described it as a modular blueprint for how AI models are built, trained, evaluated, and eventually operated at DWD. This modularity is important because weather services need systems that can be maintained, reused, and connected to existing operational pipelines. If the data source, architecture, or training method changes, the evaluation and operational components should not have to be rebuilt from scratch.

We also discussed DAWID, DWD’s secure gateway for language-based AI. The idea is not simply to expose users to generic chatbots, but to provide controlled access to different language models depending on the task and data sensitivity. Some models can run locally on DWD systems, while others may be accessed in accordance with applicable data protection rules. This is particularly important for meteorological services, where AI-generated text could support routine reports, internal workflows, or customer-facing products — but only with clear safeguards in place.

A recurring point was the importance of the human in the loop. AI can support forecasters by reducing repetitive work, suggesting features such as fronts, or helping draft routine summaries. But the expert remains responsible for checking, adjusting, and interpreting the final product. This is especially important because AI systems can produce confident-sounding answers that are not necessarily correct. In forecasting, as in language generation, probability must not be mistaken for certainty.

The discussion then moved toward scientific and research-oriented activities, especially DWD’s AI-based forecasting model AICON. AICON is trained on DWD’s ICON-DREAM reanalysis and is evaluated alongside forecasters in daily operations. A regional version, AICON-LAM, is also being developed for Europe. This reflects a broader shift: AI weather models are moving from impressive research demonstrations toward tools that must be tested, compared, verified, and eventually integrated into operational workflows.

Verification was one of the most important parts of the conversation. Traditional numerical weather prediction models are built on physical equations, while AI models learn patterns from data. This means that standard verification scores are necessary but not sufficient. AI models can sometimes appear better because they are smoother and lose small-scale activity, which may improve some metrics while reducing physically meaningful variability. Therefore, DWD is extending verification toward scale-dependent diagnostics, observation-based verification, spatial verification, cyclone tracking, energy spectra, and methods that distinguish real information from smoothing effects.

Another important topic was data assimilation. Current AI weather models usually still rely on analyses produced by classical data assimilation systems. This means that even if the forecast model itself is fast, the full forecasting chain still depends on computationally expensive analysis production. Stefanie described DWD’s work on AI-VAR, which uses ideas from variational data assimilation within an AI framework. This is an exciting direction because it tries to bring observations more directly into AI-based forecasting while retaining knowledge from established data-assimilation methods.

From my perspective, the podcast highlighted that the AI transition in weather services is as much cultural and organizational as it is technical. Meteorologists, forecasters, data assimilation experts, software engineers, and AI developers need to work together. DWD is addressing this through training, shared tools, documentation, tutorials, internal AI forums, and use-case-driven development. This is important because meteorologists' expertise remains one of the strongest assets of a weather service, even as the tools around them change rapidly.

The main message I took away from the conversation is that trustworthy AI for weather forecasting cannot be built solely through models. It requires transparent workflows, careful verification, secure deployment, human oversight, and close interaction with domain experts. AI may change the skill of forecasting, but it also changes what it means to evaluate, explain, and responsibly use a forecast.

A recording of the podcast is available on YouTube: [Watch the podcast](https://www.youtube.com/watch?v=jSR1JeTn1UM&list=PLwv2rZ5UPWUH9rIJn1klqvKl9VvIV_EvY&index=10)

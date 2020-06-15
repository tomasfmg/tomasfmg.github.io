---
layout: post
title:  "First results"
date:   2020-06-14 16:00 +0530
categories: jekyll update
---

Hello!

During the past couple of weeks, the basic version of `ParametricOptInterface.jl` (or `POI` for short) was implemented. 
We can already add affine and linear constraints and objective functions with parameters that can be updated without the need to initialize another model.
Documentation is currently being written. but there is already a test that implements an example that can clarify its usage.

The most challenging task that I faced during these first two weeks was to adapt myself to the way `MathOptInterface.jl` (`MOI` for short) is structured. Until now, I only used `JuMP.jl`, which works differently.
As I develop `POI`, I have to think in two directions: the integration with `MOI`, which can be thought as a lower level optimization modelling tool, and the integration with `JuMP.jl`, which would be a higher level one.

After some initial barriers, I feel much more confident writing code on a brooader aspect, as I learned a lot from my mentors.
I would already like to thamk them for several valuable lessons. Couldn't be more excited for the next months under their supervision.

The next steps are to finish all possible pairs of functions and sets that are used in `MOI` and to start documentation that fits the community guidelines.






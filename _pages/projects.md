---
title: "Projects"
permalink: /projects/
excerpt: ""
---

## Control and Optimization of Networks under Uncertainty

Modern infrastructure systems face significant levels of uncertainty due to various factors such as renewable integration, aging components, and imprecise system models. Optimization problems routinely solved for operational decision making for these systems therefore must account for these uncertainties to ensure secure operations. The ANSI team develops efficient algorithmic frameworks for optimization problems under uncertainty that can be broadly categorized into two lines of research: (i) efficient uncertainty quantification methods that can be seamlessly incorporated in optimization formulations, and (ii) machine learning methods to learn critical features of uncertain optimization problems, to enable fast real-time solutions in response to uncertainty realizations.


## Analysis of Extreme Events on Networked Systems

As the threat of natural disasters and malicious agents continues to grow, there is an increasing need to understand how complex networked systems respond to large scale damage and sophisticated targeted attacks.  To this end, ANSI has developed computational tools for analyzing how electric power and natural gas networks respond after severe damage has been inflicted.  These tools have been leveraged to quantify the possible impacts of a variety of effects such as, seasonal hurricanes, space weather, and electromagnetic pules.


## Design of Resilient Networks

Critical networked infrastructures such as electric power, natural gas, cyber, and water, are under increasing stress from extreme events such as hurricanes, earthquakes, ice storms, and temperature swings. Thus, there is a need for approaches that improve the resiliency of networks to extreme events. To address this need, ANSI has developed tools that optimally design and operate networks for resiliency criteria.


## Interdependencies Across Multiple Networks

Modern networked infrastructures are increasingly independent on one another. For example, historically low natural gas prices has driven unprecedented growth in natural gas based generators on electric power systems.  This has made the power system more susceptible to natural gas price fluctuations and disruptions (e.g. Northeast U.S. cold snap, winter 2013-2014). In practice these systems are managed and modeled in isolation and these approaches miss key details of the joint systems. To address this gap, ANSI has developed optimization, control, and analysis tools to model interdependencies networks at varying temporal and spatial scales to better manage and operate this systems in presence of these relationships.


## Machine Learning and Data Analytics for Networks

Developing statistical methods that quantify uncertainty in networked systems as well as techniques for learning models of this uncertainty are of great interest to ANSI. The framework of graphical models is a natural abstraction for representing the statistical dependencies between constituents in a network. Our research primarily focuses on basic research challenges in graphical model inference and learning, as well as applications of graphical models in critical infrastructure and cyber-physical systems.


## Optimization Algorithms for Networks

Many of the applications areas of interest to ANSI feature nonlinear equations and a mixture of both continuous and discrete decision variables.  To address the challenge of finding optimal solutions to these mixed-integer nonlinear mathematical programs (MINLPs) in practice, ANSI is exploring a variety of novel algorithms for solving these types of mathematical programs.  These efforts include: [POD](https://github.com/lanl-ansi/POD.jl), global optimization solver for nonconvex mixed-integer nonlinear programs based on piecewise convex relaxation, polyhedral outer-approximation, and dynamic discretization; [Pajarito](https://github.com/JuliaOpt/Pajarito.jl), global optimization solver for mixed-integer convex programs; and [Juniper](https://github.com/lanl-ansi/Juniper.jl), a heuristic nonlinear branch and bound solver.

As the pace of Moore's Law beings to slow down a variety of novel analog computing architectures such as, quantum computers and neuromorphic chips, are already commercially available. Leveraging Los Alamos National Laboratory's D-Wave 2X quantum computer and other DOE user facilities, ANSI is currently exploring how these novel computational platforms can be leveraged to accelerate both machine learning and optimization algorithms.


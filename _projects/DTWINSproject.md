---
title: "Digital Twins for Triple Negative Breast Cancer"
excerpt: "Framework for treatment regimen personalization based on model predictive control"
sidebar:
    - title: "Type"
      text: "Dissertation project"
    - title: "Responsibilities"
      text: "Lead researcher, conceptualization, data processing, methodology, analysis, writing"
order: 4
---
![image](/assets/images/DTWINS_overview.png)

This project combined previous work in predictive modeling for TNBC using reduced order models, to make decisions about optimal treatment regimens under assumptions of uncertainty. 
We provid a framework for constructing a digital twin of a patient directly from imaging data with an underlying mathematical model calibrated with an approximate Bayesian method. 
This provides a probablistic model for simulating response to a given chemotherapy schedule. Using constrained optimization, a patient-specific regimen is provided that minimizes 
either the tumor burden, or the total dose delivered to the patient.

Depending on the optimal control problem, we were able to show that we can acheive significantly improved response (~17% smaller tumors) while keeping the same dose, or provide
the a signifcantly similar response with less dose (~12% reduction in chemotherapy). we additionally explore constraints on how toxicity of given regimen should be quantified, without
access to direct measurements.

Despite the introduction of the probabilistic model component, we were able to keep computational burden relatively low due to the reduced order models capabilities. The entire framework is capable
of running on a laptop in just a few hours, with the only computational constraint being the memory burden of building the ROM.

The full publication, Personalizing neoadjuvant chemotherapy regimens for triple-negative breast cancer using a biology-based digital twin, is available [here](https://doi.org/10.1038/s41540-025-00531-z)

Check out the [GitHub!](https://github.com/cchristenson2/TNBC_DigitalTwins)

---
title: "Radionuclide response model in GBM"
excerpt: "Model development and validation for predicting response of glioblastoma patients to rhenium based nanoparticles"
sidebar:
    - title: "Type"
      text: "Dissertation project"
    - title: "Responsibilities"
      text: "Lead researcher, conceptualization, data processing, methodology, analysis, writing"
---
![image](/assets/images/RNL_overview.png)

The main goal of this project was to be able to predict the efficacy of radionuclide therapy in patients with recurrent glioblastoma. To make this prediction, we calibrated a biology-based mathematical model to quantitative imaging data directly from patients during this treatment. The first step to making predictions was to determine the optimal model for the low-dose rate, continuous exposure (high total dose; >100Gy) that radionuclide therapy provides.

After evaluating a family of models, we found that a net proliferation model, or one that doesn't require the spatial distribution of radionuclide was the optimal across a 10 patient dataset. This tracks with the finding that local estimations of cell death (based on quantitative MRI) are not well correlated with exposure levels at each voxel. The main take away from a broader perspective than fitting models, is that the local response to high dosage therapies is not well understood and involves many non-cancerous cell types in the region.
Despite selecting the simplest model from the family, we were able to make accurate predictions of tumor burden up to 3 months early. This provides valuable information on whether the treatment is going to be successful or if a change of course is needed.

![image](/assets/images/RNL_model.png)

The full publication, Predicting the spatio-temporal response of recurrent glioblastoma treated with rhenium-186 labelled nanoliposomes, is available [here](https://doi.org/10.1016/j.brain.2023.100084)

Check out the [GitHub!](https://github.com/cchristenson2/RNL_responseModel)

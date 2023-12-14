---
title: "atallah-analysis-plan.md"
author: "Andy Atallah"
date: "2023-12-12"
output: html_document
---

# Planned revisions to reproduction of Spielman et al. 2023
The paper whose analysis I aim to revise is the following:

Spielman, S. E., Tuccillo, J., Folch, D. C., Schweikert, A., Davies, R., Wood, N., & Tate, E. (2020). Evaluating social vulnerability indicators: Criteria and their application to the Social Vulnerability Index. Natural Hazards, 100(1), 417–436. <https://doi.org/10.1007/s11069-019-03820-z>.


## Analysis
1. I will download the weighted notebook from Professor Joseph Holler and run the changes.
2. I will create a national SoVI map.
3. I will add to the discussion section to explain the results of reweighting PCA by percentage of variance explained.

## Results

1. The code from Professor Holler will include all changes to the workflow which multiply principal components by their percentage of variance explained.
2. The national SoVI map will be constructed using the `folium` package. It will display SoVI scores for each county in the United States.
3. The discussion section will add to the existing section by explaining reanalysis changes as they pertain to the consistency of SoVI.

## Discussion

1. Using the code from Professor Holler was recommended by him in his capacity as instructor of the course. It will allow for a new approach to PCA.
2. The national map will provide context to the reader and visualize data which was not shown in the original paper.
3. The discussion section will add to the rich discussion of internal and theoretical consistency in Spielman et al. (2020) by assessing whether a change to PCA produces significant improvements to the problems which the original authors present with the model.

**Note**: In full transparency, this analysis plan was completed after much of the study had been written.
# Social Media Sanctions and Politcal Beliefs

Discussions on politics and sanctions in social media have raised concerns about potential biases. Specifically, users with conservative beliefs often claim they are more likely to face sanctions compared to those with liberal beliefs.

However, increased sanctions may not necessarily result from different policies by social media platforms. It could be that users with conservative beliefs share more questionable content, leading to a higher likelihood of sanctions, even under a neutral enforcement policy.

A recent study in *Nature* by Mohshen Moshel et al. examined whether social media sanctions are politically biased or if they stem from differences in misinformation-sharing behaviors among political groups. The findings suggest that social media sanctions are not inherently biased but are instead a consequence of misinformation-sharing tendencies.

## Project Overview

This repository aims to:

- **Reproduce Key Findings**: Analyze the dataset and validate claims from the study.
- **Investigate Biases**: Assess whether misinformation-sharing patterns differ across political groups.
- **Conduct Statistical Analysis**: Apply relevant methods to compare misinformation-sharing behaviors.
- **Visualize Data**: Present findings through clear and informative visualizations.
- **Discuss Implications**: Interpret results and consider their broader impact.

## Usage Instructions

The analysis is conducted using Python with libraries such as pandas, numpy, matplotlib, and seaborn.

- The Jupyter Notebook is structured with markdown explanations for each step.
- Results include statistical analysis, visualizations, and key interpretations.

## Dataset Description

The dataset comprises social media posts labeled for misinformation. It includes:

- **User Political Alignment**
- **Misinformation Flags** (whether a post was flagged as misinformation)
- **Sanction Status** (e.g., post removal, user suspension)
- **Engagement Metrics** (likes, shares, comments)

## Results and Findings

### Statistical Insights

- A strong correlation exists between misinformation-sharing and political alignment.
- Principal Component Analysis (PCA) highlights misinformation and political orientation as key distinguishing factors.

### Model Analysis

- A regression model was implemented to assess the likelihood of sanctions based on misinformation and political alignment.
- Findings indicate that misinformation-sharing significantly increases the probability of facing sanctions.

## Conclusion

The analysis supports the argument that misinformation-sharing behavior is associated with political alignment and that sanctions are more frequent for users engaging in misinformation-sharing. However, this does not necessarily imply an intentional bias by social media platforms, but rather a reflection of differing content-sharing behaviors across political groups.

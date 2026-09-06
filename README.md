## COVID Morality

### Publication

This repository holds the code and trained models behind:

> Xu, H. (2024). Examining public attitudes and ideological divides through media engagement: An empirical analysis of moral foundations theory amidst the COVID-19 pandemic. *Current Research in Social Psychology*, 33(2). [PDF](https://crisp.org.uiowa.edu/sites/crisp.org.uiowa.edu/files/2024-03/Xu%20CRISP%2033.2.pdf)

An earlier version was presented at the 72nd Annual ICA Conference (Paris, France, virtual, 2022) as "Pandemic Politics, Moralized: How Morality Predicts Audience Engagement with COVID-19 Messages from Partisan and Science Media on Facebook" (Yilang Peng & Huacen Xu).

If you use this repository, please cite the paper above and consider giving the repo a star.

### Introduction

The research explores the relationship between moral framing and audience engagement with COVID-19 messages from partisan and science media on Facebook. We build a liberty dictionary and score posts for liberty morality, which the extended Moral Foundations Dictionary (eMFD) does not cover, then model engagement against moral-foundation scores. Run the notebooks in sequence:

1. `1. Data_preparation.ipynb`
2. `2. Extract_topics.ipynb`
3. `3. eMFDscore_Tutorial.ipynb`
4. `4. Liberty dictionary`
5. `5. Liberty_scoring.ipynb`
6. `6. Data_analysis_1226.ipynb`

### Data

Textual data was extracted from public Facebook pages, then transformed and loaded into the notebooks. The dataset is not distributed with this repository.

### Install

The notebooks were run with Anaconda Navigator (version 6.4.8). No other software is needed.

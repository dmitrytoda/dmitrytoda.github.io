---
layout: single
permalink: /ds/Ships
sidebar:
  - nav: sidebar-ds
---

# Ships detection in satellite imagery

Satellite imagery provides unique insights into various markets, including agriculture, defense and intelligence, energy, and finance. New commercial imagery providers, such as Planet, are using constellations of small satellites to capture images of the entire Earth every day.

This flood of new imagery is outgrowing the ability for organizations to manually look at each image that gets captured, and there is a need for machine learning and computer vision algorithms to help automate the analysis process.

Most publicly available image-processing networks have been trained on regular pictures taken with something like a phone camera. While satellite images look very different,  one can use transfer learning on existing CNNs and retrain them on satellite data. *1st row: no-ship examples, 2nd row: ship examples*

![1st row: no-ship, 2nd row: ship](/assets/images/ships/2x4.png "1st row: no-ship, 2nd row: ship")

#### Data:
* publicly available [kaggle dataset](https://www.kaggle.com/rhammell/ships-in-satellite-imagery) of 4000 80x80 RGB satellite ship images 
* imbalanced classes (1 positive example for 3 negatives)

#### Algorithms:
* transfer learning on VGG16 and Inception v3 CNNs
* for each pretrained CNN, implemented and trained 3 classifiers using different techniques of dealing with imbalanced classes (baseline, class weights and data augmentation)

#### Findings:
* the best solution was a combination of VGG16 + classifier with data augmentation
* yields accuracy 97.25%, precision 92.63% and recall 95.65% on unseen data
* see best model's training history and final confusion matrix on test data below:

![training history](/assets/images/ships/history.png "training history")

![confusion matrix](/assets/images/ships/cm.png "confusion matrix")
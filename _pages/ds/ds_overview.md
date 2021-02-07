---
layout: single
permalink: /ds
sidebar:
  - nav: sidebar-ds
---

In 2007, when I got my degree in Applied Mathematics from Moscow Institute of Physics and Technology (MIPT), artificial intelligence was still more of a concept than a working industry. It took over a decade of managing software development projects in finance, e-commerce and online gaming before I discovered my passion for data science and building machine learning systems with my own hands.

* **Tools**: Python (numpy, pandas, sklearn, matplotlib), R (data.table, ggplot2, caret), SQL
* **Algorithms**: prediction and classification, SVM, KNN, PCA, random forest, gradient boosting, ensembling, time series analysis, recommender systems, anomaly detection
* **Deep learning**
	- CNN: image classification, object localization, object detection, landmark finding, face recognition
	- RNN: GRU, LSTM, word embeddings, attention models, trigger word detection
	- Technology: TensorFlow, Keras
* **Statistical inference**: hypothesis testing, regression models

### Some projects that I've done:

<style>
	h3 {
    margin-top: 0em;
</style>

<div class="container-list">
	<div class="container-outer" onclick="location.href='/ds/WordAlign';" style="cursor: pointer;">
		<div class="container-inner">
			<h3>WordAlign</h3>
		</div>
		<div class="container-inner">
			<img class="img-prev" src="/assets/images/wordalign/mapping.png">
			<div class="txt-box">
			<big>Word alignment for Russian-Chinese bitext</big> using BERT contextualized embeddings and further fine-tuning on unique parallel corpus
			</div>
		</div>
	</div>
	
	<div class="container-outer" onclick="location.href='/ds/SwiftPredict';" style="cursor: pointer;">
		<div class="container-inner">
			<h3>SwiftPredict</h3>
		</div>
		<div class="container-inner">
			<img class="img-prev" src="/assets/images/swiftkey.jpg">
			<div class="txt-box">
			<big>Ngram text prediction model for mobile keyboards</big> that can be trained from scratch on a laptop, occupies only 219 MB RAM and provides suggestions within 22 msec			
			</div>
		</div>
	</div>
	
	<div class="container-outer" onclick="location.href='/ds/Ships';" style="cursor: pointer;">
		<div class="container-inner">
			<h3>Ships detection in satellite imagery</h3>
		</div>
		<div class="container-inner">
			<img class="img-prev" src="/assets/images/ships/thumb.png">
			<div class="txt-box">
			<big>96.77% F1 score</big> detecting ships in satellite imagery with imbalanced classes, using transfer learning with VGG16 and Inception v3 CNNs
			</div>
		</div>
	</div>
</div>
	
### Formal education:
* Specialization in Data Science, Johns Hopkins University, 2021 (expected)
* Specialization in Deep Learning, [deeplearning.ai](https://coursera.org/share/44d344705c4c0e3ae0236fba7f54eea0), 2020
* Bachelor's degree in Applied Mathematics, Moscow Institute of Physics and Technology ([MIPT](https://mipt.ru/english/)), 2007
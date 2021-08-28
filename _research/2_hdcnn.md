---
title: "<font color='green'>HAR from Smartphone to smartwatch accelerometer data (vice versa)</font>"
excerpt: "Feature representation from different smart devices<br/><img src='/images/portfolio/smartphone_to_smartwatch_transfer.png' style='width: 500px; height: 250px; align: middle;'>"
collection: portfolio
---
We investigate the problem of making human activity recognition (AR) scalable–i.e., allowing AR classifiers trained in one context to be readily adapted to a different contextual domain. This is important because AR technologies can achieve high accuracy if the classifiers are trained for a specific individual or device, but show significant degradation when the same classifier is applied context–e.g., to a different device located at a different on-body position. To allow such adaptation without requiring the onerous step of collecting large volumes of labeled training data in the target domain, we proposed a transductive transfer learning model that is specifically tuned to the properties of convolutional neural networks (CNNs). Our model, called HDCNN, assumes that the relative distribution of weights in the different CNN layers will remain invariant, as long as the set of activities being monitored does not change. Evaluation on realworld data shows that HDCNN is able to achieve high accuracy even without any labeled training data in the target domain, and offers even higher accuracy (significantly outperforming competitive shallow and deep classifiers) when even a modest amount of labeled training data is available. <br/>

<center>
<figure>
	<img src='/images/portfolio/hdcnn.png' class='center' >
	<figcaption>Fig. Heterogeneous Deep Convolutional Neural Network (HDCNN) architecture</figcaption>
</figure>
</center>

<br/>
<b>Key Contributions Contributions:</b>
<br/>
<li> <b><font color='blue'>Deep Learning-based Domain Adaptation:</font></b> We propose a transfer learning motivated CNN-based activity recognition framework, called Heterogeneous Deep Convolutional Neural Network (HDCNN) that automatically adapts and learns the model across different domains–i.e.,
<i>user, device type, device instances </i> combinations. Our adaptation model works on the assumption that the distribution of weights in the convolutional layers remains largely unchanged across different contexts, and thus automatically adjusts the weights while minimizing this divergence in weight distributions.
</li>
<li><b><font color='blue'>Ability to Adapt with No or Minimal Labeled Data in Target Context:</font></b> Our approach assumes that the set of
daily lifestyle activities being monitored (i.e., the set of output activity labels) remains the same in both source
and target contexts. We design the transfer learning approach such that it implicitly incorporates the source context activity labels, and thus does not require any explicitly-labeled target training data. If even a modest amount of target-domain labeled data is available, then the classifier can be rapidly adapted further, to provide superior performance.
</li>
<li>
	<b><font color='blue'>Empirical Demonstration of Superior Performance:</font></b> We use our real-world data to demonstrate how HDCNN outperforms other alternatives. In particular, HDCNN achieves more than 80% accuracy when adapting in the absence of any target-domain labeled data, with this accuracy exceeding 87% accuracy with only 10% labeled (about 26 mins of activity) data in the target domain. Noticeably, HDCNN achieves approx. 80% classification accuracy when adapting across deviceinstances (smartwatch!smartphone, and vice versa), where unadapted baseline model achieves accuracy 38% (smartphone!smartwatch, and vice versa), outperforming competitive transfer learning models by over 10%.
</li>

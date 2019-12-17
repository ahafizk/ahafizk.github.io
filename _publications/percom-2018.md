---
title: "Scaling Human Activity Recognition via Deep Learning-based Domain Adaptation."
collection: publications
permalink: /publication/percom-2018
excerpt: ''
venue: 'PerCom'
citation: '<b>Md Abdullah Al Hafiz Khan</b>, Nirmalya Roy. In IEEE international conference on Pervasive Computing and Communication, <b>PerCom 2018</b>. Athens, Greece.'
---

[Download PDF](https://ahafizk.github.io/files/PerCom-2018.pdf)

<b>Abstract:</b>

We investigate the problem of making human activity
recognition (AR) scalable–i.e., allowing AR classifiers trained
in one context to be readily adapted to a different contextual
domain. This is important because AR technologies can achieve
high accuracy if the classifiers are trained for a specific individual
or device, but show significant degradation when the same
classifier is applied context–e.g., to a different device located at
a different on-body position. To allow such adaptation without
requiring the onerous step of collecting large volumes of labeled
training data in the target domain, we proposed a transductive
transfer learning model that is specifically tuned to the properties
of convolutional neural networks (CNNs). Our model, called
HDCNN, assumes that the relative distribution of weights in the
different CNN layers will remain invariant, as long as the set of
activities being monitored does not change. Evaluation on realworld
data shows that HDCNN is able to achieve high accuracy
even without any labeled training data in the target domain,
and offers even higher accuracy (significantly outperforming
competitive shallow and deep classifiers) when even a modest
amount of labeled training data is available.
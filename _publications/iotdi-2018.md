---
title: "UnTran: Recognizing Unseen Activities with Unlabeled data using Transfer Learning."
collection: publications
permalink: /publications/iotdi-2018
excerpt: ''
venue: 'IoTDI'
citation: '<b>Md Abdullah Al Hafiz Khan</b>, Nirmalya Roy. In ACM/IEEE International Conference on Internet-of-Things Design and Implementation, <i><b>IoTDI 2018</b></i>. Orlando, Florida, USA.'
---

<script>
function goBack() {
  window.history.back()
}
</script>

<button onclick="goBack()">Go Back</button>

[Download PDF](https://ahafizk.github.io/files/UnTran.pdf)

<b>Abstract:</b>
The success and impact of activity recognition algorithms
largely depends on the availability of the labeled training
samples and adaptability of activity recognition models across
various domains. In a new environment, the pre-trained activity
recognition models face challenges in presence of sensing biasness,
device heterogeneities, and inherent variabilities in human
behaviors and activities. Activity Recognition (AR) system built
in one environment does not scale well in another environment,
if it has to learn new activities and the annotated activity
samples are scarce. Indeed building a new activity recognition
model and training the model with large annotated samples
often help overcome this challenging problem. However, collecting
annotated samples is cost-sensitive and learning activity model
at wild is computationally expensive. In this work, we propose
an activity recognition framework, UnTran that utilizes source
domains’ pre-trained autoencoder enabled activity model that
transfers two layers of this network to generate a common feature
space for both source and target domain activities. We postulate
a hybrid AR framework that helps fuse the decisions from a
trained model in source domain and two activity models (raw and
deep-feature based activity model) in target domain reducing the
demand of annotated activity samples to help recognize unseen
activities. We evaluated our framework with three real-world
data traces consisting of 41 users and 26 activities in total. Our
proposed UnTran AR framework achieves ≈ 75% F1 score in
recognizing unseen new activities using only 10% labeled activity
data in the target domain. UnTran attains ≈ 98% F1 score while
recognizing seen activities in presence of only 2-3% of labeled
activity samples.




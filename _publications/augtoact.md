---
title: "AugToAct: Scaling Complex Human Activity Recognition with Few Labels"
collection: publications
permalink: /publications/augtoact
excerpt: ''
venue: 'PerCom'
citation: 'Abu Zaher Md Faridee, <b>Md Abdullah Al Hafiz Khan</b>, Nilavra Pathak, Nirmalya Roy.
<i>16th EAI International Conference on Mobile and Ubiquitous Systems: Computing, Networking and Services, MobiQuitous 2019. Houston, United States.</i>'
---

<script>
function goBack() {
  window.history.back()
}
</script>

<button onclick="goBack()">Go Back</button>

[Download PDF](https://ahafizk.github.io/files/augtoact.pdf)

<b>Abstract:</b>

Human activity recognition (HAR) from wearable sensor data has
recently gained widespread adoption in a number of fields. However,
recognizing complex human activities, postural and rhythmic
body movements (e.g. dance, sports) is challenging due to the lack
of domain-specific labeling information, the perpetual variability
in human movement kinematics profiles due to age, sex, dexterity
and the level of professional training. In this paper, we propose a
deep activity recognition model to work with limited labeled data,
both for simple and complex human activities. To mitigate the intra
and inter-user spatio-temporal variability of movements, we posit
novel data augmentation and domain normalization techniques.
We depict a semi-supervised technique that learns noise and transformation
invariant feature representation from sparsely labeled
data to accommodate intra-personal and inter-user variations of
human movement kinematics. We also postulate a transfer learning
approach to learn domain invariant feature representations by
minimizing the feature distribution distance between the source
and target domains.We showcase the improved performance of our
proposed framework, AugToAct, using a public HAR dataset. We
also design our own data collection, annotation and experimental
setup on complex dance activity recognition steps and kinematics
movements where we achieved higher performance metrics with
limited label data compared to simple activity recognition tasks.
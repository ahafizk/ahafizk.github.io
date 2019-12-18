---
title: "Acoustic Based Appliance State Identifications for Fine-Grained Energy Analytics"
collection: publications
permalink: /publications/appliance
excerpt: ''
venue: 'PerCom'
citation: 'Nilavra Pathak, <b>Md Abdullah Al Hafiz Khan</b>, Nirmalya Roy. <i>In PerCom 2015, St. Louis, Missouri. </i>'
---

<script>
function goBack() {
  window.history.back()
}
</script>

<button onclick="goBack()">Go Back</button>

[Download PDF](https://ahafizk.github.io/files/appliance.pdf)

<b>Abstract:</b>

Fine-grained monitoring of everyday appliances
can provide better feedback to the consumers and motivate
them to change behavior in order to reduce their energy usage.
It also helps to detect abnormal power consumption events,
long-term appliance malfunctions and potential safety concerns.
Commercially available plug meters can be used for individual
appliance monitoring but for an entire house, each such individual
plug meters are expensive and tedious to setup. Alternative
methods relying on Non-Intrusive Load Monitoring techniques
help disaggregate electricity consumption data and learn about
the individual appliance’s power states and signatures. However
fine-grained events (e.g., appliance malfunctions, abnormal power
consumption, etc.) remain undetected and thus inferred contexts
(such as safety hazards etc.) become invisible. In this work, we
correlate an appliance’s inherent acoustic noise with its energy
consumption pattern individually and in presence of multiple
appliances. We initially investigate classification techniques to
establish the relationship between appliance power and acoustic
states for efficient energy disaggregation and abnormal events
detection. While promising, this approach fails when there are
multiple appliances simultaneously in ‘ON’ state. To further
improve the accuracy of our energy disaggregation algorithm, we
propose a probabilistic graphical model, based on a variation of
Factorial Hidden Markov Model (FHMM) for multiple appliances
energy disaggregation. We combine our probabilistic model with
the appliances acoustic analytics and postulate a hybrid model
for energy disaggregation. Our approach helps to improve the
performance of energy disaggregation algorithms and provide
critical insights on appliance longevity, abnormal power consumption,
consumer behavior and their everyday lifestyle activities.
We evaluate the performance of our proposed algorithms on
real data traces and show that the fusion of acoustic and power
signatures can successfully detect a number of appliances with
95% accuracy.
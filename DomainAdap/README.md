# Problem Statement

For these experiments, we use two sets of datasets: MNIST-USPS
(https://www.kaggle.com/datasets/bistaumanga/usps-dataset), Clipart and Realworld categories of the Office-Home dataset
(https://www.hemanthdv.org/officeHomeDataset.html). The former is the case
where both the datastes contain images of handwritten digits and the latter
contains images of 65 categories from four domains (of which you are supposed
to work on only Clipart and Real-world categories). The following are the tasks:

A. Implement Adversarial Discriminative Domain Adaptation (ADDA) with
Resent-50 as the base classifier on the source data. Use the Wasserstein
metric for adversarial feature learning.

B. Implement a Cycle-GAN for the pair of MNIST-USPS datasets. Use the
output of the converted target in the source classifier and report the result
on adaptation.

# E2E - ML4SCI Tasks
## Self-Supervised Learning with ResNet-15 and Barlow Twins

This repo contains the common task and the task for "Next generation vision transformers for end to end mass regression and classification" for Google Summer of Code 2025

-----

This project demonstrates the power of Self-Supervised Learning (SSL) to train a robust feature extractor on unlabelled data, which is then fine-tuned for a downstream task. The core of this project is the implementation of the Barlow Twins methodology to pre-train a ResNet-15 model on a large, unlabelled high-energy physics jet dataset.

The effectiveness of this approach is validated by comparing the performance of the fine-tuned SSL model against an identical ResNet-15 model trained from scratch on a small, labelled dataset. The results show a significant 7.35% improvement in accuracy, proving the value of SSL for creating powerful, generalizable features, especially in scenarios where labelled data is scarce.

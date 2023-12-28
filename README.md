# Computer Vision GANs

## Introduction

Welcome to the Computer Vision GANs repository! This project is dedicated to exploring the innovative realm of Generative Adversarial Networks (GANs), as introduced by Ian J. Goodfellow and collaborators in their groundbreaking paper "[Generative Adversarial Networks](https://proceedings.neurips.cc/paper_files/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html)" presented at NeurIPS 2014.

### Research Paper Reference

- **Title:** Generative Adversarial Networks
- **Authors:** Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio
- **Link:** [Generative Adversarial Networks (NeurIPS, 2014)](https://proceedings.neurips.cc/paper_files/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html)

## GAN Architecture Overview

### Two-Sided Dynamics

GANs lies in the dynamic interplay between two core components: the Generative Network and the Discriminative Network. These networks engage in an adversarial dance, continually evolving and challenging each other to enhance their capabilities.

### Generative Network

The Generative Network endeavors to synthesize data that closely resembles real-world examples. Its goal is to generate content exhibiting patterns and structures inherent in the training dataset, fostering creativity and diversity.

### Discriminative Network

the Discriminative Network acts as a discerning critic, distinguishing between genuine and generated data. Through this process, it refines its ability to provide feedback to the Generative Network, driving continuous improvement in the generated outputs. In other word, it will classify if the generated data are good or no!

## Generative Model vs. Discriminative Model

### Generative Model

- **Objective:** Model the underlying probability distribution of training data to generate realistic samples.
- **Applications:** Image synthesis, data augmentation, creative content generation.

### Discriminative Model

- **Objective:** Discriminate between different classes or categories, achieving accurate classification.
- **Applications:** Image classification, object detection, pattern recognition.

### Training:
- the GAN training reaches an equilibrium where the generator produces realistic data and the discriminator cannot reliably distinguish between real and generated data.

[check](https://poloclub.github.io/ganlab/)

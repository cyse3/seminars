---
title: "Using Data while Protecting Privacy in the Digital Era"
date: 2021-08-11
time: 2PM
presenter: "yves-alexandre-de-montjoye"
youtube: "-EWHECuzxqc"
zoom-link: "https://imperial-ac-uk.zoom.us/j/98149690180?pwd=V0lwVEc0dXlNM2dsYnR6SkNaUlFXdz09"
zoom-id: "981 4969 0180"
zoom-password: "DG&.2b"
---

End-to-end encryption (E2EE) in messaging platforms enable people to securely and privately communicate with one another. Its widespread adoption has however raised concerns that illegal content might now be shared undetected. Following the global pushback against key escrow systems, client-side scanning based on perceptual hashing has been recently proposed by governments and researchers to detect illegal content in E2EE communications.

Last week, Apple [announced](https://www.apple.com/child-safety/) that it will use client-side scanning to detect child sexual abuse material in iCloud photos, users’ personal photo libraries. The announcement has triggered concerns among experts about the trade-off achieved by client-side scanning mechanisms and the risk of them being misused.

In this talk, we will present what is to the best of our knowledge the first framework to evaluate the robustness of perceptual hashing-based client-side scanning which we proposed two months ago. We will present a general black-box attack against any perceptual hashing algorithm and two white-box attacks for discrete cosine-based algorithms. Using these, we will show in a large-scale evaluation that more than 99.9% of images can be successfully attacked in a black-box setting while preserving the content of the image. We will then show our attack to generate diverse perturbations, suggesting that straightforward mitigation strategies would be ineffective. Taken together, our results raise concerns on the robustness of perceptual hashing-based client-side scanning mechanisms to black-box adversarial machine learning attacks.

This talk is based on “Adversarial Detection Avoidance Attacks: Evaluating the robustness of perceptual hashing-based client-side scanning” by Shubham Jain*, Ana-Maria Cretu*, Yves-Alexandre de Montjoye and available as preprint [here](https://arxiv.org/abs/2106.09820).

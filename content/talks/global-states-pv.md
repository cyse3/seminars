---
title: "A little more conversation, a little less action, a lot more satisfaction: Global states in ProVerif."
date: 2022-06-29
time: 3PM
presenter: "vincent-cheval"
youtube: "hmJ72Y5wjOM"
zoom-link: "https://surrey-ac.zoom.us/j/94250630968?pwd%3DSFFUUVNHWkNuYjlQVCtOTjBLTFk4QT09"
zoom-id: "942 5063 0968"
zoom-password: "061660"
---

ProVerif is a popular tool for the fully automatic analysis of security protocols, offering very good support to detect flaws or prove security. One exception is the case of protocols with global states such as counters, tables, or more generally, memory cells. ProVerif fails to analyse such protocols, due to its internal abstraction.

In the original paper of GSVerif, our key idea was to devise a generic transformation of the security properties queried to ProVerif. We proved the soundness of our transformation and implemented it into a front-end GSVerif. Our experiments showed that our front-end (combined with ProVerif) outperforms the few existing tools, both in terms of efficiency and protocol coverage. We successfully applied our tool to a dozen of protocols of the literature, yielding the first fully automatic proof of a security API and a payment protocol of the literature. 

In the newest version of ProVerif, the generic transformations of GSVerif can be fully described in term of axioms, thus taking advantage of this new ProVerif feature. 

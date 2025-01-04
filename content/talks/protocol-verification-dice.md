---
title: "Symbolic protocol verification with dice: process equivalences in the presence of probabilities"
date: 2022-09-21
time: 2PM
presenter: "steve-kremer"
collaboration: FM-SEC
youtube: "55SrlKRUqBc"
zoom-link: "https://york-ac-uk.zoom.us/j/93097043118?pwd%3DTTJqeDZsT1pxWTFmZ1VYNWFDdnY3UT09"
zoom-id: "930 9704 3118"
zoom-password: "493163"
---

Symbolic protocol verification generally abstracts probabilities away, considering computations that succeed only with negligible probability, such as guessing random numbers or breaking an encryption scheme, as impossible. This abstraction, sometimes referred to as the perfect cryptography assumption, has shown very useful as it simplifies automation of the analysis. However, probabilities may also appear in the control flow where they are generally not negligible. In this paper we consider a framework for symbolic protocol analysis with a probabilistic choice operator: the probabilistic applied pi calculus. We define and explore the relationships between several behavioral equivalences. In particular we show the need for randomized schedulers and exhibit a counter-example to a result in a previous work that relied on non-randomized ones. As in other frameworks that mix both non-deterministic and probabilistic choices, schedulers may sometimes be unrealistically powerful. We therefore consider two subclasses of processes that avoid this problem. In particular, when considering purely non-deterministic protocols, as is done in classical symbolic verification, we show that a probabilistic adversary has-maybe surprisingly-a strictly superior distinguishing power for may testing, which, when the number of sessions is bounded, we show to coincide with purely possibilistic similarity.

This is joint work with Vincent Cheval and Raphaëlle Crubillé.

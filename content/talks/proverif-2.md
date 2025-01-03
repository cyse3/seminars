---
title: "The security protocol verifier ProVerif and its recent improvements: lemmas, induction, fast subsumption, and much more"
date: 2022-05-18
time: 3PM
presenter: "bruno-blanchet"
collaboration: FM-SEC
youtube: "IYOl3AKXdkA"
zoom-link: 
zoom-id: 
zoom-password: 
---

ProVerif is a widely used automatic security protocol verifier that relies on symbolic model of cryptography.
It can prove various security properties (secrecy, correspondences, some equivalences) for an unbounded number of sessions, as well as find attacks.

In this talk, we will present an overview of ProVerif and its recent improvements.
These improvements are twofold.

First, we extended ProVerif with lemmas, axioms, proofs by induction, natural numbers, and temporal queries.
These features not only extend the scope of ProVerif, but can also be used to improve its precision (that is, avoid false attacks) and make it terminate more often.

Second, we reworked and optimized many of the algorithms used in ProVerif (generation of clauses, resolution, subsumption, ...), resulting in impressive speed-ups on large examples.

These improvements are joint work with Vincent Cheval and Véronique Cortier, to appear at IEEE Security and Privacy 2022.


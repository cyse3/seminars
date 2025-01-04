---
title: "Resilient Machine Learning: A Systems-Security Perspective"
date: 2021-10-13
time: 2PM
presenter: "roei-schuster"
youtube: "DM_t-SVCS8E"
zoom-link: "https://york-ac-uk.zoom.us/j/95442585241?pwd%3DbG83L2pQK3J1TllMYmhJcnBWUUxlQT09"
zoom-id: "954 4258 5241"
zoom-password: "121217"
---

The security and privacy of ML-based systems are becoming increasingly difficult to understand and control, as subtle information-flow dependencies unintentionally introduced by the use of ML expose new attack surfaces in software. We will first present select case studies on data leakage and poisoning in NLP models that demonstrate this problem. We will then conclude by arguing that current defenses are insufficient, and that this calls for novel, interdisciplinary approaches that combine foundational tools of information security with algorithmic ML-based solutions.

We will discuss leakage in common implementations of nucleus sampling --- a popular approach for generating text, used for applications such as text autocompletion. We show that the series of nucleus sizes produced by an autocompletion language model uniquely identifies its natural-language input. Unwittingly, common implementations leak nucleus sizes through a side channel, thus leaking what text was typed, and allowing an attacker to de-anonymize it.

Next, we will present data-poisoning attacks on language-processing models that must train on "open" corpora originating in many untrusted sources (e.g. Common Crawl). We will show how an attacker can modify training data to "change word meanings" in pretrained word embeddings thus controlling outputs of downstream task solvers (e.g. NER or word-to-word translation), or poison a neural code-autocompletion system, so that it starts making attacker-chosen insecure suggestions to programmers (e.g. to use insecure encryption modes). This code-autocompletion attack can even target specific developers or organizations, while leaving others unaffected.

Finally, we will briefly survey existing classes of defenses against such attacks, and explain that they are critically insufficient: they provide only partial protection, and real-world ML practitioners lack the tools to tell whether and how to deploy them. This calls for new approaches, guided by fundamental information-security principles, that analyze security of ML-based systems in an end-to-end fashion, and facilitate practicability of the existing defense arsenal.

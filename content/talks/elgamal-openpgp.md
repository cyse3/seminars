---
title: "On the (in)security of ElGamal in OpenPGP"
date: 2022-01-26
time: 3PM
presenter: "luca-de-feo"
youtube: "ncCKpxPJcdw"
zoom-link: "https://newcastleuniversity.zoom.us/j/87494431621?pwd%3DeHhVZm1iS1NRd1FRbHhsTVI0N3NXdz09"
zoom-id: "874 9443 1621"
zoom-password: "145917"
---

Do you think you know ElGamal encryption? Think twice.

We uncover vulnerabilities in the OpenPGP ecosystem stemming from confusion about the definition of ElGamal encryption (and the lack of an unequivocable standard). The first vulnerability leads to practical plaintext recovery in a limited number of cases. The second one, combined with side-channel leakage we found in some popular OpenPGP libraries, leads to feasible key recovery, in relatively rare cases.

We hope that these attacks, that we dub "cross-configuration", serve as a cautionary tale for standards designers. Cryptographic algorithms, even when they may appear very simple, hide a great deal of complexity in the choices of parameters and data representation. While an instantiation may appear to be safe in isolation, the interaction of two incompatible instantiations may lead to a security disaster, which can only be avoided by a carefully written standard.

Joint work with Bertram Poettering and Alessandro Sorniotti.

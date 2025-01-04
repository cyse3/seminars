---
title: "Towards a High-Assurance and Specification-Compliant X.509 PKI Implementation"
date: 2022-02-02
time: 3PM
presenter: "omar-haider-chowdhury"
youtube: "MHzK_EKCQiY"
zoom-link: "https://newcastleuniversity.zoom.us/j/88036980317?pwd%3DQ2xkbkxhLzFYOTRVZGNSR2NucHJmQT09"
zoom-id: "880 3698 0317"
zoom-password: "293746"
---

The X.509 Public-Key Infrastructure (PKI) is one of the most prominent and widely used authentication mechanisms, which plays a crucial role in different applications such as secure communication (e.g., SSL/TLS, IPSec), software updates, and emails. Flaws in an X.509 PKI implementation can make an application relying on X.509 PKI susceptible to impersonation attacks or interoperability issues. In this talk, I will discuss my group’s effort in developing a high-assurance and specification-compliant implementation of X.509 PKI.

First, I will discuss the Symcerts system that uses domain-specific optimizations, symbolic execution, and differential analysis to automatically identify specification non-compliance in open-source SSL/TLS libraries. Second, I will discuss Morpheus, a black-box analysis engine, that automatically checks the logical correctness of RSA signature verification implementations in open-source SSL/TLS libraries through a formally verified oracle. Third, I will discuss my group’s effort to formalize and re-engineer the specification of the X.509 certificate chain validation using an executable specification. I will conclude my talk with a sneak peek of our ongoing work on developing a formally verified implementation of the X.509 PKI.


---
title: "Blackbox and Grey-box Approaches to Protocol State Machine Learning (With Lots of Attacks Against TLS and WPA)"
date: 2023-01-11
time: 3PM
presenter: "tom-chothia"
youtube: "qPwTdOyzUYg"
zoom-link: "https://york-ac-uk.zoom.us/j/95382587132?pwd%3DZ3I5UzQrUnMzVzZIM2lYZmxWWUdUdz09"
zoom-id: "953 8258 7132"
zoom-password: "785967"
---

Protocol state machine learning has been used to analyse many cryptographic protocols. Unlike fuzzing it can find logical flaws in protocols and unlike formal modelling it can find vulnerabilities in implementations. I will outline how black box state machine methods work, and describe how we have applied them to WPA to find two downgrade attacks. I will then describe a grey box learning method we have developed that uses memory snapshots and symbolic execution of the binary, combined with observations of run-time memory and a protocol's inputs and outputs to learn its state machine. We show that this grey box method is much more efficient than black box learning, allowing us to test protocols in much more detail and leading to the discovery of new attacks against implementations of TLS and WPA.
This is joint work with: Chris McMahon Stone, Sam L. Thomas, Joeri de Ruiter, Mathy Vanhoef, James Henderson and Nicolas Bailluet

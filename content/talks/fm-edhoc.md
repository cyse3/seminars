---
title: "Not so AdHoc testing: formal methods in the standardization of the EDHOC protocol"
date: 2022-07-20
time: 3PM
presenter: "charlie-jacomme"
youtube: ""
zoom-link: "https://surrey-ac.zoom.us/j/96178759011?pwd=UXBrOUc4SGt1Q2pnTUpoMEpvOXVzQT09"
zoom-id: "96178759011"
zoom-password: "095565"
---

We believe that formal methods in security should be leveraged in all the standardisation’s of security protocols in order to strengthen their guarantees. To be effective, such analyses should be:
- maintainable: the security analysis should be performed on every step of the way, i.e. each iteration of the draft;
- pessimistic: all possible threat models, notably all sort of compromise should be considered;
- precise: the analysis should notably include as many real life weaknesses of the concrete cryptographic primitives specified.

In this talk, we illustrate how such a goal may be approached by detailing our analysis of the current IETF draft standard of the EDHOC protocol, as well as our subsequent interactions with its LAKE working group.
We will proceed in three steps, first introducing the Sapic+ platform that allows from a single modeling of a protocol to benefit from all the capabilities of multiple automated verification tools (ProVerif,Tamarin,DeepSec). We will then introduce multiple recent advances on how to better model the cryptographic primitives and their real life weaknesses. We will finally show how we leveraged Sapic+ along with the advanced primitive models to analyze the EDHOC protocol and provide feedback to the LAKE working group that has been integrated in latter drafts.

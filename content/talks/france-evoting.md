---
title: "Reversing, Breaking, and Fixing the French Legislative Election E-Voting Protocol"
date: 2022-11-30
time: 3PM
presenter: "alexandre-debant"
collaboration: FM-SEC
youtube: "W4PA0oH9mFE"
zoom-link: "https://york-ac-uk.zoom.us/j/95310261776?pwd%3DOTlzb1lUNWN4bWlsN2dkK3prSFdEZz09"
zoom-id: "953 1026 1776"
zoom-password: "929160"
---

In June 2022, French citizens abroad voted online during the French legislatives election to chose the new members of Parliament. In this work, we conducted a security analysis of the system under use. Due to a lack of system and threat model specifications, we first built and contributed such specifications by studying the French legal framework and by reverse-engineering the code base accessible to the voters. Our analysis reveals that this protocol is affected by two design-level and implementation-level vulnerabilities. We show how those allow a standard voting server attacker and even more so a channel attacker to defeat the election integrity and ballot privacy. We propose and discuss fixes to prevent those attacks. Our specifications, the attacks, and the fixes were acknowledged by the relevant stakeholders during our responsible disclosure. Beyond this specific protocol, we draw general conclusions and lessons from this instructive experience where an e-voting protocol meets the real-world constraints of a large-scale and political election.

---
title: "Formal methodologies to secure cyber-physical systems: from static analysis to runtime enforcement"
date: 2023-11-15
time: 3PM
presenter: "massimo-merro"
collaboration: FM-SEC
youtube: "tzwewzOM7yA"
zoom-link: "https://york-ac-uk.zoom.us/j/96917567239?pwd=WnFsNC9JNXYzVVY4REZSZEVmYTROUT09"
zoom-id: "969 1756 7239"
zoom-password: "254994"
---

We present some research works over the past nine years on applying formal methods to secure cyber-physical systems (CPSs). The presentation will take place at a sufficiently high level of detail and will essentially be divided into three parts.

In the first part, we highlight an hybrid process calculus to model both CPSs and physics-based attacks. We formalize a threat model that specifies MITM attacks that can manipulate sensor readings and/or control commands in order to drive a CPS into an undesired state, and we provide the means to assess attack tolerance/vulnerability with respect to a given attack.  We then formalize how to estimate the impact of a successful attack on a CPS and investigate possible quantifications of the success chances of an attack.

In the second part, we report a line of work that uses model checking tools and statistical model checking techniques to perform static security analysis of CPSs that are increasingly complex and therefore exposed to more complex cyber-physical attacks that attempt to bypass different IDSs.

In the third and final part, we move to runtime enforcement techniques to ensure specification compliance in networks of controllers, possibly compromised by colluding malware. We define a synthesis algorithm that, given a set of observable actions and a timed correctness property, returns a monitor that enforces the property during the execution of any (potentially corrupted) controller. Our enforcement enjoys a number of classical properties together with attack mitigation by correcting and suppressing incorrect actions of corrupted controllers and by generating safe actions in full autonomy when the controller under scrutiny is not able to do so in a correct manner.

---
title: "Estimating the nonlinearity of cryptographic Boolean functions"
date: 2021-12-01
time: 3PM
presenter: "ana-salagean"
youtube: "R2FZrDKXlxI"
zoom-link: "https://newcastleuniversity.zoom.us/j/89023249759?pwd%3DdVd1bzJSU3VDOVpKMUdYN3dtMWhuZz09"
zoom-id: "890 2324 9759"
zoom-password: "636264"
---

Boolean functions are used as one component in the design of symmetric ciphers, e.g. the Sbox in AES, or the filtering function in stream ciphers. If these functions are linear, it opens the way to certain types of attacks (linear and differential cryptanalysis). These attacks also work if the function is not linear but can be approximated well by a linear function. This has led to the notion of nonlinearity, a parameter of the function which measures its distance to the closest linear/affine function. The nonlinearity can be computed by a {{< math >}}\(O(n 2^n)\){{< /math >}} algorithm, where n is the number of variables. When n is large, this computation is unfeasible. Therefore, we investigate the possibility of probabilistic estimation of the nonlinearity. To do so, we use the notion of nonhomomorphicity (introduced by Zhang and Zheng), which can be estimated efficiently even for large n. We generalise several techniques developed by Bellare et al, to obtain upper and lower bounds for the honhomomorphicity in terms of the nonlinearity. These bounds then allow us to estimate the nonlinearity once a good estimate of the nonhomomorphicity was obtained. This is joint work with Pante Stanica and was first presented at the SETA 2020 conference.

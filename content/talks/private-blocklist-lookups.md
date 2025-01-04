---
title: "Private Blocklist Lookups with Checklist"
date: 2021-09-08
time: 2PM
presenter: "dmitry-kogan"
youtube: "4083RmIr67g"
zoom-link: "https://newcastleuniversity.zoom.us/j/82566523499?pwd=UmdlVUkvWTl6a0w4bEFTRFlla0VyZz09"
zoom-id: "825 6652 3499"
zoom-password: "621016"
---

In this talk, I will present Checklist, a system for private blocklist lookups. In Checklist, a client can determine whether a particular string appears on a server-held blocklist of strings, without leaking its string to the server. Checklist is the first blocklist-lookup system that (1) leaks no information about the client’s string to the server, (2) does not require the client to store the blocklist in its entirety, and (3) allows the server to respond to the client’s query in time sublinear in the blocklist size. To make this possible, Checklist uses a new two-server private-information-retrieval protocol that is both asymptotically and concretely faster, in terms of server-side time, than those of prior work. We will discuss the evaluation of Checklist in the context of the “Safe Browsing” blocklist, which all major browsers use to prevent web clients from visiting malware-hosting URLs. Joint work with Henry Corrigan-Gibbs.

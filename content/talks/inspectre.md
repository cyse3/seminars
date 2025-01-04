---
title: "InSpectre: Breaking and Fixing Microarchitectural Vulnerabilities by Formal Analysis"
date: 2021-07-28
time: 3PM
presenter: "roberto-guanciale"
youtube: "Gl9eJ-33duI"
zoom-link: "https://newcastleuniversity.zoom.us/j/81925495891?pwd=OGJkRnNWOEEwaXVkNUJUdUNTem9oQT09"
zoom-id: "819 2549 5891"
zoom-password: "495287"
---

The Spectre attacks have demonstrated the fundamental insecurity of current computer microarchitecture. The attacks use features like pipelining, out-of-order and speculation to extract arbitrary information about the memory contents of a process. A comprehensive formal microarchitectural model capable of representing the forms of out-of-order and speculative behavior that can meaningfully be implemented in a high performance pipelined architecture has not yet emerged. Such a model would be very useful, as it would allow the existence and non-existence of vulnerabilities, and soundness of countermeasures to be formally established. We present such a model targeting single core processors. The model is intentionally very general and provides an infrastructure to define models of real CPUs. It incorporates microarchitectural features that underpin all known Spectre vulnerabilities. We use the model to elucidate the security of existing and new vulnerabilities, as well as to formally analyze the effectiveness of proposed countermeasures. Specifically,we discover three new (potential) vulnerabilities, including a new variant of Spectre v4, a vulnerability on speculative fetching, and a vulnerability on out-of-order execution, and analyze the effectiveness of existing countermeasures including constant time and serializing instructions.

---
title: "A Unified Symbolic Analysis of WireGuard"
date: 2023-10-25
time: 2PM
presenter: "sylvain-ruhault"
collaboration: FM-SEC
youtube: "HhJhp5xKB8g"
zoom-link: "https://ed-ac-uk.zoom.us/j/83750166253"
zoom-id: "837 5016 6253"
zoom-password: "6qEu1k0Z"
---

WireGuard is a Virtual Private Network (VPN), presented at NDSS 2017, recently integrated into the Linux Kernel and paid commercial VPNs such as NordVPN, Mullvad and ProtonVPN. It proposes a different approach from other classical VPN such as IPsec or OpenVPN because it does not let users configure cryptographic algorithms. The protocol inside WireGuard is a dedicated extension of IKpsk2 protocol from Noise Framework. Different analyses of WireGuard and IKpsk2 protocols have been proposed, in both the symbolic and the computational model, with or without computer-aided proof assistants. These analyses however consider different adversarial models or refer to incomplete versions of the protocols. In this work, we propose a unified formal model of WireGuard protocol in the symbolic model. Our model uses the automatic cryptographic protocol verifiers Sapic+, ProVerif and Tamarin. We consider a complete protocol execution, including cookie messages used for resistance against denial of service attacks. We model a precise adversary that can read or set static, ephemeral or pre-shared keys, read or set ecdh pre-computations, control key distribution. Eventually, we present our results in a unified and interpretable way, allowing comparisons with previous analyses. Finally thanks to our model, we confirm a flaw on the anonymity of the communications and point an implementation choice which considerably weakens its security. We propose a remediation that we prove secure using our models.
 
This is joint work with Dhekra Mahmoud and Pascal Lafourcade.

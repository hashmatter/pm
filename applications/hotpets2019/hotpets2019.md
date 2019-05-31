---
title: "Applied Privacy Enhancing Technology for P2P Networks with p3lib"
author: "Gonçalo Pestana (goncalo@hashmatter.com)"
---

**Abstract**: In this lightning talk, we discuss the importance of bridging the
gap between research on Privacy Enhancing Technologies (PETs) for P2P networks
and the current decentralized web industry. In addition, we discuss how to 
design and implement practical software that can be used by system engineers to 
enhance privacy of current P2P systems, while focusing on current open
challenges in production systems such as IPFS and Dat.

## Talk motivation and goals

As P2P networks and decentralized systems (re)gain popularity among researchers
and industry alike, it is important to design and implement
decentralized systems that not only preserve users’ privacy but also deliver
on scalability, performance and usability. Failing to deliver on those
properties will render decentralized systems unusable and unattractive for
mass adoption or as a viable alternative to centralized systems.

It has been demonstrated that naive implementation of decentralized
systems potentially harm user privacy more than centralized systems [@systematizingdweb], 
[@crawlingdht], [@pcdn]. However, while the user base and number of
applications built on top of large scale
decentralized networks such as IPFS [@ipfs] and Dat [@dat] has been increasing, 
there hasn't been enough research and development efforts to design and implement
primitives and protocols that allow users to leverage those systems in a secure
way.

**p3lib** In this lightning talk, we discuss the importance of bridging the
gap between research on PETs for P2P networks
and the current decentralized web industry. We also introduce p3lib [@p3lib], 
a modular toolbox for system engineers to
build secure and privacy preserving P2P systems. p3lib implements a set of primitives and
protocols derived from academia work (onion routing, ShadowWalker [1], Octopus
DHT lookup [2], plausible deniability for DHT lookups, onion routing on top of
DHTs [@sphinx], [@sphinx-or] and others) that can be
used by system developers to enhance privacy of P2P networks build on Dat, IPFS
and, more generally, libp2p [@libp2p] and other P2P networking stacks.

In addition, we outline the current industry needs in terms of privacy engineering, 
introduce the roadmap p3lib and show how the research community can actively
contribute with suggestions, research and implementation work.

**hashmatter** At hashmatter [@hashmatter] we believe that P2P and decentralised
networks will play an important role in the future of connected services. Our
goal is to research, design and implement primitives and protocols that enhance
privacy in P2P networks for application developers to use out of the box. We aim
at creating a research-to-industry pipeline that brings the most recent privacy
and security primitives to the hands of system P2P engineers.



## References



# hashmatter 

*Draft - to be locked by end of June*

[**hashmatter**](https://hashmatter.com) is a research and development lab focused on improving distributed and P2P protocols towards better privacy and metadata resistance. Our long term vision is to build software that enables the privacy preserving and metadata resistant decentralised web.


### Background

The ethos of the P2P community and the decentralized web is characterized by allowing people and communities to interoperate and collaborate without the need for external stewardship. This new paradigm opens doors for user self-sovereignty, personal data ownership and freedom from central authorities which incentives tend to lock-in their users and to hold and monetize private data in order to maximize their profits. However, P2P and decentralized protocols are complex and collaboration between multiple independent parties often leaks metadata that can be used to target individuals and communities. While centralized client-server designs disclose user’s behaviour and social graph to one centralized entity (the service owner), naive decentralized systems potentially disclose that information to everyone in the network. **While it is clear that current P2P systems are not focusing on metadata privacy, failing to deliver it will render decentralized systems unusable and unattractive for mass adoption or as a viable alternative to centralized services.**

It is hard to design and implement collaboration networks (read P2P and decentralised) without leaking considerable amount of informations about user behavior, her intersts and social graph: Peer collaboration requires, by definition, to . In addition, mentail models, concepts and primitives that enable privacy preserving decentralized and P2P systems are lacking. There is also a large gap between academic research on privacy preserving P2P networking and currently deployed  P2P projects. At hashmatter we are commited to:

- close the gap between academia and industry: bring the of the art on research of privacy preserving networks to the industry as soon as possible;
- building modular and easy to use primitives and protocols for enhacing privacy in P2P networks;
- improve developer and system designer awareness about privacy enhancing technologies;
- measure and assess privacy in current P2P networks and understand how to improve privacy of current P2P networks and services.

## Roadmap (Q3, Q4)

Currently, we are focusing on three fronts: [research](https://github.com/gpestana/p2psec), 
[development](https://github.com/hashmatter/p3lib) and 
[community outreach](https://github.com/hashmatter/outreach). 

**WIP** The roadmap for the remaining of 2019 is being defined in issue
[#4](https://github.com/hashmatter/pm/issues/4). Once it is completed, this
document will be updated.

### A. Research 
The high level research goals are understand what are the current

- [ ] Paper: Study metadata leak vectors of current decentralized networks.
- [ ] Paper: Privacy Preserving Distributed Hash Tables - Reality and Future [open source research (github)](https://github.com/gpestana/p2psec/tree/master/papers/privacy_preserving_dht)
- [ ] Article: Comparison of DHT over Tor vs Onion routing over DHT;

### B. p3lib development
The high level development goal for 2019 is to develop the first iteration
(v0.1) building blocks that enable decentralized application developers to
use with libp2p. We should also aim at steering the development and future work based on what current projects need.

**0) Documentations and specs**
- [ ] Webpage with p3lib modules documentation and specs; 

**1) Onion routing on top of DHT**
- [ ] Implement secure path discovery;
- [ ] 2 project using or experimenting with the protocol;
- [ ] study and measure entropy and performance in the DHT context. 
    
 **2) Octopus DHT lookup protocol**
- [ ] Define specs for first interations of an adapted Octopus lookup protocol;
- [ ] 2 project using or experimenting with the protocol;

 **3) Multiple plausible deniability protocols for libp2p**
 - [ ] specs and implementation of 1 plausible deniability proocols for libp2p

### C.  Community outreach
The high level community outreach goal consists on documenting and raise awareness about the
the privacy leaks of DHTs and P2P routing networks. In addition, we aims at raching out to project owners and community to discuss and understand which problems need to be addressed first.

**Understanding the current community needs**
- [ ] Reach out to 5 projects in the space using DHTs to undestand how

**Talks, workshops, demos**

- [x] Talk at DTN 2019
- [ ] Developer workshop at Web3Summit
- [ ] Talk at HotPETs 2019
- [ ] ... (more)

- [ ] Screencast (p3lib-sphinx) demonstrate how to use p3lib-sphinx with libp2p
- [ ] Screencast (p3lib-fullrt) demonstrate how to use p3lib-fulltr protocol with libp2p

**note** *if you are interested in hosting a talk/workshop about p3lib or privacy preserving P2P networks, [let us know](mailto:gpestana@hashmatter.com?subject=hashmatter%20community)!*

---
[hashmatter.com](https://hashmatter.com)

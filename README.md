# hashmatter 

[**hashmatter**](https://hashmatter.com) is a research and development lab focused on improving distributed and P2P protocols towards better privacy and metadata resistance. Our mission is to build software that enables developers to build a privacy preserving and metadata resistant decentralized web.

### Background

The ethos of the P2P community and the decentralized web is characterized by allowing people and communities to interoperate and collaborate without the need for external stewardship. This new paradigm opens doors for user self-sovereignty, personal data ownership and freedom from central authorities which incentives tend to lock-in their users and to use and monetize private data in order to maximize their profits. However, P2P and decentralized protocols are complex and collaboration between multiple untrusted parties often leaks metadata that can be used to target individuals and communities. While centralized client-server designs disclose user’s behavior and social graph to one centralized entity (the service owner), naive decentralized systems potentially disclose that information to everyone in the network. **Current P2P and dweb projects are not focusing on privacy. Failing to deliver on privacy and security will render decentralized application unusable and unattractive for mass adoption or as a viable alternative to centralized services.**

It is hard to design and implement collaboration networks (read P2P and decentralized) without leaking considerable amount of informations about user behavior, her interests and social graph. In addition, the community lacks the mental models, concepts and primitives necessary to build privacy preserving decentralized and P2P systems. There is a large gap between academic research on privacy and production systems. At hashmatter we are committed to:

- Close the gap between academia and industry: To bring the state the art on research of privacy preserving networks to the industry as soon as possible;
- To build modular and easy to use primitives and protocols for enhancing privacy in P2P networks;
- To improve developer and system designer awareness about privacy enhancing technologies;
- To measure and assess privacy in current P2P networks and understand how to improve privacy of current P2P networks and services.

## Roadmap (Q3, Q4)

Currently, we are focusing on three fronts: [research](https://github.com/gpestana/p2psec), 
[development](https://github.com/hashmatter/p3lib) and 
[community outreach](https://github.com/hashmatter/outreach). 

### A. Research 
The high level research goals are to define and articulate the problem space of privacy leaks of DHTs, both abstractly and in current projects in the space.

- [ ] Paper: Study metadata leak vectors of current decentralized networks.
- [ ] Paper: Privacy Preserving Distributed Hash Tables - Reality and Future [open source research (github)](https://github.com/gpestana/p2psec/tree/master/papers/privacy_preserving_dht)
- [ ] Article: Comparison of DHT over Tor vs Onion routing over DHT;

### B. p3lib development
The high level development goal for 2019 is to develop the first iteration
(v0.1) building blocks that enable decentralized application developers to
use with libp2p.

**0) Documentations and specs**
- [ ] Webpage with p3lib modules documentation and specs; 

**1) Onion routing for enhancing privacy of DHT lookups**
- [ ] Implement secure path discovery;
- [ ] 2 project using or experimenting with the protocol;
- [ ] study and measure entropy and performance of DHT lookups using p3lib-sphinx

 **3) Sinkhole protocol**
 - [ ] Specs of Sinkhole protocol (using cPIR scheme)
 - [ ] Implement server library v0.1
 - [ ] Implement client library v0.1
 - [ ] Deploy "Pinata"-like service for private DHT lookups in IPFS

### C.  Community outreach
The high level community outreach goal consists on documenting and raise awareness about the privacy leaks of DHTs and P2P network protocols. In addition, we aims at reaching out to project owners and community to discuss and understand which problems need to be prioritized.

**Understanding the current community needs**
- [ ] Reach out to 5 projects in the space using DHTs to understand how p3lib can be used in the wild and what are the project needs.

**Talks, workshops, demos**

- [ ] Privacy Preserving P2P networks screencast sessions
	- [ ] How does Kademlia DHT work and its privacy attack vector?
	- [ ] Peer assisted CDNs and its privacy attack vector?
	- [ ] Techniques to improve privacy of P2P networks
	- [ ] p3lib-sinkhole: demonstrate how to use p3lib-sinkhole with IPFS
	- [ ] p3lib-sphinx: demonstrate how to use p3lib-sphinx with libp2p
	- [ ] p3lib-fullrt: demonstrate how to use p3lib-fulltr protocol with libp2p
	- more ...

- [x] Talk at DTN 2019
- [ ] Developer workshop at Web3Summit

**note** *if you are interested in hosting a talk/workshop about p3lib or privacy preserving P2P networks, [let us know](mailto:gpestana@hashmatter.com?subject=hashmatter%20community)!*

## How to contribute

There are several way you can help:

- Open an issue with general suggestions and comments (https://github.com/hashmatter/pm/issues)
- Contribute for p3lib with specs design and development (https://github.com/hashmatter/p3lib)
- Contribute on the research efforts (https://github.com/hashmatter/research)
- Reach our with any suggestions and comments (mx _at_ hashmatter.com or gpestana _at_ hashmatter.com)
- Invite us over for a workshop or talk to your event :)


---
[hashmatter.com](https://hashmatter.com)

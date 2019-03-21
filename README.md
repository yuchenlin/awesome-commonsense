# Awesome Machine Common-Sense (MCS)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of papers and resources about common-sense knowledge graphs (CSKG) and reasoning (CSR). 

<p align="center">
  <img src="https://www.darpa.mil/DDM_Gallery/teaching-machines-619-316.jpg">
  <br><span>Research in MCS aims to create machine common sense services that can help break down the barrier between the narrowly focused AI applications of today and the more general AI applications of the future. <br> https://www.darpa.mil/news-events/2018-10-11</span>
</p>

##### Contents  

1. [Common-Sense Knoweldge Graphs](#cskgs)  
2. [Tasks & Datasets](#datasets)
3. [Papers](#papers)
4. [Tutorials](#tutorials)



## Common-Sense Knoweldge Graphs
- **ConceptNet**
  - Introduction: ConceptNet is a general, human-annotated commonsense knowledge graph, representing common **concepts** (words and phrases) that people use and the [common-sense **relationships**](https://github.com/commonsense/conceptnet5/wiki/Relations) between them. The knowledge in ConceptNet is collected from a variety of resources, including crowd-sourced resources (such as [Wiktionary](https://www.wiktionary.org/) and Open Mind Common Sense), games with a purpose (such as Verbosity and nadya.jp), and expert-created resources (such as [WordNet](https://wordnet.princeton.edu/) and JMDict). ConceptNet is the most widely-used general commonsense knowledge graph, although it is still somewhat noisy and highly incomplete. 
  - Authors: MIT Media Lab and Luminoso Technologies, Inc.
  - Paper: [[ConceptNet 5.5: An Open Multilingual Graph of General Knowledge]](https://arxiv.org/abs/1612.03975) in AAAI 2017
  - Website: [[http://conceptnet.io/]](http://conceptnet.io/)


- **WebChild**
  - Introduction: WebChild is a large collection of commonsense knowledge, **automatically extracted** and disambiguated from Web contents. WebChild contains _triples that connect nouns with adjectives via fine-grained relations_ like hasShape, hasTaste, evokesEmotion, etc. The arguments of these assertions, nouns and adjectives, are disambiguated by mapping them onto their proper WordNet senses.
  - Authors: Niket Tandon, Gerard de Melo, and Gerhard Weikum
  - Paper: [[WebChild 2.0: Fine-Grained Commonsense Knowledge Distillation]](http://people.mpi-inf.mpg.de/~ntandon/papers/tandon-acl2017-demo.pdf) in ACL 2017 (demo)
  - [[Website @ MPI-INF]](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/webchild/)
  
  
- **ATOMIC**
  - Introduction: ATOMIC, extended from [Event2Mind](https://uwnlp.github.io/event2mind/), is a commonsense knowledge base that focuses on inferential knowledge organized as typed **if-then** relations with variables (e.g., “if X pays Y a compliment, then Y will likely return the compliment”). It has nine if-then relation types to distinguish causes vs. effects, agents vs. themes, voluntary vs. involuntary events, and actions vs. mental states. Most assertions are about human social behaviors. 
  - Authors: Maarten Sap et al. (AI2 & UW)
  - Paper: [[ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning]](https://arxiv.org/pdf/1811.00146.pdf)  in AAAI 2019
  - Website: [[https://homes.cs.washington.edu/~msap/atomic/]](https://homes.cs.washington.edu/~msap/atomic/)
  
## Tasks and Datasets

- **Script-based Commonsense Knowledge Reasonig**

  - ***SemEval-2018 Task 11***

- **Storytelling Commonsense **

- **Situition Commonsense Inference**

- **General Commonsense Reasoning**


- **Visual Commonsense Reasoning**



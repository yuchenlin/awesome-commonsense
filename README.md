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
4. [Tutorials/Workshops/Blogs](#tutorials)



## Common-Sense Knoweldge Graphs
- **ConceptNet**
  - Intro: ConceptNet is a general, human-annotated commonsense knowledge graph, representing common **concepts** (words and phrases) that people use and the [common-sense **relationships**](https://github.com/commonsense/conceptnet5/wiki/Relations) between them. The knowledge in ConceptNet is collected from a variety of resources, including crowd-sourced resources (such as [Wiktionary](https://www.wiktionary.org/) and Open Mind Common Sense), games with a purpose (such as Verbosity and nadya.jp), and expert-created resources (such as [WordNet](https://wordnet.princeton.edu/) and JMDict). ConceptNet is the most widely-used general commonsense knowledge graph. 
  - Authors: MIT Media Lab and Luminoso Technologies, Inc.
  - Paper: [[ConceptNet 5.5: An Open Multilingual Graph of General Knowledge]](https://arxiv.org/abs/1612.03975) in AAAI 2017
  - Website: [[http://conceptnet.io/]](http://conceptnet.io/)


- **WebChild**
  - Intro: WebChild is a large collection of commonsense knowledge, **automatically extracted** and disambiguated from Web contents. WebChild contains _triples that connect nouns with adjectives via fine-grained relations_ like hasShape, hasTaste, evokesEmotion, etc. The arguments of these assertions, nouns and adjectives, are disambiguated by mapping them onto their proper WordNet senses.
  - Authors: Niket Tandon, Gerard de Melo, and Gerhard Weikum
  - Paper: [[WebChild 2.0: Fine-Grained Commonsense Knowledge Distillation]](http://people.mpi-inf.mpg.de/~ntandon/papers/tandon-acl2017-demo.pdf) in ACL 2017 (demo)
  - [[Website @ MPI-INF]](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/webchild/)
  
  
- **ATOMIC**
  - Intro: ATOMIC, extended from [Event2Mind](https://uwnlp.github.io/event2mind/), is a commonsense knowledge base that focuses on inferential knowledge organized as typed **if-then** relations with variables (e.g., “if X pays Y a compliment, then Y will likely return the compliment”). It has nine if-then relation types to distinguish causes vs. effects, agents vs. themes, voluntary vs. involuntary events, and actions vs. mental states. Most assertions are about human social behaviors. 
  - Authors: Maarten Sap et al. (AI2 & UW)
  - Paper: [[ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning]](https://arxiv.org/pdf/1811.00146.pdf)  in AAAI 2019
  - Website: [[https://homes.cs.washington.edu/~msap/atomic/]](https://homes.cs.washington.edu/~msap/atomic/)
  
## Tasks and Datasets

- **Script-based Commonsense Reasonig**

  - Description: The seting is similar to multi-choice passage-based question asnwering. Given passages are usually script-based stroies, the correct ansqwer cannot be inferred by literally matching. Answering the questions correctly requires common knowledge that are not obvious in the given script.
  - Example: 
  - Dataset: [SemEval-2018 Task 11](https://competitions.codalab.org/competitions/17184) (an incoming extended shared task will be at EMNLP2019 workshop [COIN](http://www.coli.uni-saarland.de/~mroth/COIN/)).
  - The Dataset Paper: [[SemEval-2018 Task 11: Machine Comprehension Using Commonsense Knowledge]](http://www.aclweb.org/anthology/S18-1119)  (ACL 2018 SemEval)
  

- **Situition Commonsense Reasonig**

  - Description: The (evaluation) seting is given a situition (a single sentence or a four-sentence story) as input, we need to anticipate which situition (out of multiple choices) will happen next ("story-end prediction" or "story cloze test" or "situition inference"). 
  - Example: 
  - Dataset: [ROCStories](http://cs.rochester.edu/nlp/rocstories/), [SWAG](https://rowanzellers.com/swag/).
  - The Dataset Papers: 
    - [SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference](https://arxiv.org/abs/1808.05326) (EMNLP 2018) 
    - [A Corpus and Evaluation Framework for Deeper Understanding of Commonsense Stories](https://arxiv.org/abs/1604.01696) (NAACL-HLT 2016)
    - [LSDSem 2017 Shared Task: The Story Cloze Test](http://cs.rochester.edu/~nasrinm/files/Papers/lsdsem17-shared-task.pdf)

- **General Commonsense Reasoning**
 
  - Description: Given a natural language question (without any passage as context) and multiple answers, we are asked to choose one (extensively) based on cmmonsense knowledge. The main difference is that we have no script as context here. 
  - Example: 
  - Dataset: [CommonsenseQA](https://www.tau-nlp.org/commonsenseqa)
  - The Dataset Paper: [[CommonsenseQA: A Question Answering Challenge Targeting Commonsense Knowledge]](https://arxiv.org/abs/1811.00937) (NAACL-HLT 2019)

- **Unsupervised Commonsense Reasoning**

  - 

- **Visual Commonsense Reasoning**

- **Commonsense Knowledge Graph Representation**

- **Commonsense Knowledge Graph Construction**

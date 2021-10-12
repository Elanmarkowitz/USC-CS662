---
title: Schedule of Classes
---


{% assign filedir = site.baseurl | append: page.subpath %} 
{% assign notes_path = filedir | append: "notes/" %} 
{% assign project = filedir | append: "project_proposal.pdf" %}

<!--  
Instructions:

INDENTATION COUNTS

Each day should be formatted exactly as follows

Date
: Lessons Covered
  : Reading List
    : In Class Presentations
: **Assignment/Announcement**{: .label}


To add a hyperlink for readings, due it as follows
  : [Example Paper](http://linktopaper.edu)

To make the hyperlink open in a new tab by default
  : [Example Paper](http://linktopaper.edu){:target=_"blank"}

The announcement can be made red for due dates as follows
: **Assignment Due**{: .label .label-red }

-->

Aug 23
: intro, applications
  : Eisenstein 1
: **project assignment out (due 9/1)**{: .label}

Aug 25
: end of intro
  : 

Aug 30
: probability basics, ethics, text processing
  : [Goldwater probability tutorial](http://homepages.inf.ed.ac.uk/sgwater/teaching/general/probability.pdf), 
  [Nathan Schneider's unix notes](https://github.com/nschneid/unix-text-commands), 
  [Unix for poets](https://www.cs.upc.edu/~padro/Unixforpoets.pdf), 
  [sculpting text](http://matt.might.net/articles/sculpting-text/)

Sep 1
: Naive Bayes, Perceptron, Logistic Regression
  : Eisenstein 2.2, 2.3, 2.4, Charniak 1.
    : Jon -- [Preregistering NLP research](https://aclanthology.org/2021.naacl-main.51.pdf)
: **project proposal due**{: .label .label-red }


Sep 6
: LABOR DAY NO CLASS
  : 

Sep 8
: Perceptron, Logistic Regression, Nonlinear classifiers
  : Eisenstein 3
    : Julie -- [Adversarial Learning for Zero-Shot Stance Detection on Social Media](https://aclanthology.org/2021.naacl-main.379.pdf){:target="_blank"}
: **HW1 out (due 9/29)**{: .label}

Sep 13
: Nonlinear classifiers, backpropagation, gradient descent
  : Eisenstein 6, 18.1
    :  Jiageng -- [A Disentangled Adversarial Neural Topic Model for Separating Opinions from Plots in User Reviews](https://aclanthology.org/2021.naacl-main.228/)
  
Sep 15
: YOM KIPPUR NO CLASS
  : 

Sep 20
: language models: ngram, feed-forward
  : Eisenstein 18.2, 18.3, 19.1, 19.2
    : Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/)
  
Sep 22
: recurrent LM, MT history 
  : [Attention is all you need](https://arxiv.org/abs/1706.03762), [Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
    : Anirudh -- [End-to-end ASR to jointly predict transcriptions and linguistic annotations](https://aclanthology.org/2021.naacl-main.149/)

Sep 27
: MT evaluation, Statistical MT
  : [Illustrated BERT, ElMo, and co.](http://jalammar.github.io/illustrated-bert/)
    : Taufeq -- [Smoothing and Shrinking the Sparse Seq2Seq Search Space](https://aclanthology.org/2021.naacl-main.210/)
  
Sep 29
: Neural Machine Translation, Transformers
  : Eisenstein 7
    : Zhuochen -- [Continual Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.310/)
: **HW1 due**{: .label .label-red}

Oct 4
: Large Contextualized Language Models (ElMo, BERT, GPT-N, etc.), POS tags, HMMs, constituencies, cky, treebank
  : Eisenstein 9.2, 10
    : Fei -- [Counterfactual Data Augmentation for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.18/)
: **HW2 out (due 10/25)**{: .label}

Oct 6
: restructuring, dependencies, shift-reduce
  : Eisenstein 11
    : Josh -- [A Survey on Recent Approaches for Natural Language Processing in Low-Resource Scenarios](https://aclanthology.org/2021.naacl-main.201/)

Oct 11
: arc-eager, evaluation, human annotation
  : Fiona -- [Causal Effects of Linguistic Properties](https://aclanthology.org/2021.naacl-main.323/) OR
  : Adam -- [D2S: Document-to-Slide Generation Via Query-Based Text Summarization](https://aclanthology.org/2021.naacl-main.111/)

Oct 13
: semantics: word sense, propbank, amr, distributional
  : Eisenstein 13, 14.
    : Kartik -- [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58/)
  
Oct 18
: Blade Runner NLP/Bertology
  :  
    : Hanchen -- [Noisy Self-Knowledge Distillation for Text Summarization](https://aclanthology.org/2021.naacl-main.56/)

Oct 20
: Information Extraction: Entity/Relation, CRF
  : Eisenstein 17.1, 17.2
    : Souvik -- [Model Extraction and Adversarial Transferability, Your BERT is Vulnerable!](https://aclanthology.org/2021.naacl-main.161/)


Oct 25
: Information Extraction: Events, Zero-shot
  : Eisenstein 17.3
    : Zhaoxu -- [Better Feature Integration for Named Entity Recognition](https://aclanthology.org/2021.naacl-main.271/)
: **HW2 due**{: .label .label-red}

Oct 27
: Question Answering and Asking
  : Eisenstein 17.5
    : Jincheng -- [Abstract Meaning Representation Guided Graph Encoding and Decoding for Joint Information Extraction](https://aclanthology.org/2021.naacl-main.4/)
: **HW3 out (due 11/17)**{: .label}

Nov 1
: Dialogue
  : Eisenstein 19.3
    : Hassan -- [A Frustratingly Easy Approach for Entity and Relation Extraction](https://aclanthology.org/2021.naacl-main.5)
: [**Project Report Version 1 due**{: .label .label-red}](({{project}}){:target="_blank"})

Nov 3
: Power and Ethics
  : 
    : Pithayuth -- [Action-Based Conversations Dataset: A Corpus for Building More In-Depth Task-Oriented Dialogue Systems](https://aclanthology.org/2021.naacl-main.239)

Nov 8
: Knowledge Graphs (Guest Lecture Elan Markowitz)
  : 
    : Liqiu -- [Structure-Aware Abstractive Conversation Summarization via Discourse and Action Graphs](https://aclanthology.org/2021.naacl-main.109)

Nov 10
: Text Games and Reinforcement Learning (Guest Lecture [Jesse Thomason](https://jessethomason.com/))
  :  
    : Aleksei -- [How to Motivate Your Dragon: Teaching Goal-Driven Agents to Speak and Act in Fantasy Worlds](https://aclanthology.org/2021.naacl-main.64/)

Nov 15
: How to write a paper
  : Neubig slides on Piazza
    : Haoming -- [Revisiting the Weaknesses of Reinforcement Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.133/)

Nov 17
: Generalization and Robustness (Guest Lecture [Robin Jia](https://robinjia.github.io/))
  : 
    : Yi -- [Generating An Optimal Interview Question Plan Using A Knowledge Graph And Integer Linear Programming](https://aclanthology.org/2021.naacl-main.160/)
: **HW3 due**{: .label .label-red}

Nov 22
: TBD
  : 
    : Jayanth -- [Knowledge Router: Learning Disentangled Representations for Knowledge Graphs](https://aclanthology.org/2021.naacl-main.1)
    : Hitesh -- [Dynamically Disentangling Social Bias from Task-Oriented Representations with Adversarial Attack](https://aclanthology.org/2021.naacl-main.293/)

Nov 24
: THANKSGIVING BREAK; NO CLASS
  : 

Nov 29
: Project presentations
  : 
    : James -- [QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering](https://aclanthology.org/2021.naacl-main.45/)

Dec 1
: Project presentations
  : 
    : Abhinav -- [Robust Question Answering Through Sub-part Alignment](https://aclanthology.org/2021.naacl-main.98)

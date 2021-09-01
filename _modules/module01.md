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
    : Jon -- [Preregistering NLP research](https://urldefense.com/v3/__https://aclanthology.org/2021.naacl-main.51.pdf__;!!LIr3w8kk_Xxm!7IHnc2yrXOYRMf16ULiIu7L_OnNq0Bi05vwoghJcCoWmqMQi0sLcotZFuISGebs$){:target="_blank"}
: **project proposal due**{: .label .label-red }


Sep 6
: LABOR DAY NO CLASS
  : 

Sep 8
: Nonlinear classifiers, backpropagation, gradient descent
  : Eisenstein 3
    : Julie -- [Adversarial Learning for Zero-Shot Stance Detection on Social Media](https://urldefense.com/v3/__https://aclanthology.org/2021.naacl-main.379.pdf__;!!LIr3w8kk_Xxm!7IHnc2yrXOYRMf16ULiIu7L_OnNq0Bi05vwoghJcCoWmqMQi0sLcotZFqnDAFNk$){:target="_blank"}
: **HW1 out (due 9/29)**{: .label}

Sep 13
: language models: ngram, feed-forward, recurrent Machine Translation history, evaluation
  : Eisenstein 6, 18.1
    : Jiageng -- [A Disentangled Adversarial Neural Topic Model for Separating Opinions from Plots in User Reviews](https://aclanthology.org/2021.naacl-main.228/)
  
Sep 15
: YOM KIPPUR NO CLASS
  : 

Sep 20
: Statistical, Neural Machine Translation, summarization, generation
  : Eisenstein 18.2, 18.3, 19.1, 19.2
    : Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/)
  
Sep 22
: Transformers
  : [Attention is all you need](https://arxiv.org/abs/1706.03762), [Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
    : Anirudh -- [](https://aclanthology.org/2021.naacl-main.149/)

Sep 27
: Large Contextualized Language Models (ElMo, BERT, GPT-N, etc.)
  : [Illustrated BERT, ElMo, and co.](http://jalammar.github.io/illustrated-bert/)
    : Taufeq -- [](https://aclanthology.org/2021.naacl-main.210/)

  
Sep 29
: POS tags, HMMs
  : Eisenstein 7
    : Zhuochen -- [](https://aclanthology.org/2021.naacl-main.310/)
: **HW1 due**{: .label .label-red}

Oct 4
: constituencies, cky, treebank
  : Eisenstein 9.2, 10
    : Fei -- [](https://aclanthology.org/2021.naacl-main.18/)
: **HW2 out (due 10/25)**{: .label}

Oct 6
: restructuring, dependencies, shift-reduce
  : Eisenstein 11
    : Josh -- [](https://aclanthology.org/2021.naacl-main.201/)
    
Oct 11
: arc-eager, evaluation, human annotation
  : 
    : Fiona -- [](https://aclanthology.org/2021.naacl-main.323/)
    
Oct 13
: semantics: word sense, propbank, amr, distributional
  : Eisenstein 13, 14.
    : Kartik -- [](https://aclanthology.org/2021.naacl-main.58/)
    
Oct 18
: Blade Runner NLP/Bertology
  : 
    : Hanchen -- [](https://aclanthology.org/2021.naacl-main.56/)
Oct 20
: Information Extraction: Entity/Relation, CRF
  : Eisenstein 17.1, 17.2
    : Souvik -- [](https://aclanthology.org/2021.naacl-main.161/)

Oct 25
: Information Extraction: Events, Zero-shot
  : Eisenstein 17.3
    : Zhaoxu -- [](https://aclanthology.org/2021.naacl-main.271/)
: **HW2 due**{: .label .label-red}

Oct 27
: Dialogue
  : Eisenstein 19.3
    : Jincheng -- [](https://aclanthology.org/2021.naacl-main.4/)
: **HW3 out (due 11/17)**{: .label}

Nov 1
: Text Games and Reinforcement Learning
  : 
    : Sophie -- [](https://aclanthology.org/2021.naacl-main.306/)
: [**Project Report Version 1 due**{: .label .label-red}](({{project}}){:target="_blank"})

Nov 3
: Power and Ethics
  : 
    : Pithayuth -- [](https://aclanthology.org/2021.naacl-main.239/)

Nov 8
: Knowledge Graphs (Guest Lecture Elan Markowitz)
  : 
    : Liqiu -- [](https://aclanthology.org/2021.naacl-main.109/)

Nov 10
: Guest Lecture TBD
  :  
    : Aleksei -- [](https://aclanthology.org/2021.naacl-main.64/)

Nov 15
: How to write a paper
  : Neubig slides on Piazza
    : Haoming -- [Revisiting the Weaknesses of Reinforcement Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.133/)

Nov 17
: TBD
  :
    : Yi -- [Generating An Optimal Interview Question Plan Using A Knowledge Graph And Integer Linear Programming](https://aclanthology.org/2021.naacl-main.160/)
: **HW3 due**{: .label .label-red}

Nov 22
: TBD
  : 
    : Jayanth -- [Knowledge Router: Learning Disentangled Representations for Knowledge Graphs](https://aclanthology.org/2021.naacl-main.1/)

Nov 24
: THANKSGIVING BREAK; NO CLASS
  : 

Nov 29
: Project presentations
  : 
    : James -- [QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering
](https://aclanthology.org/2021.naacl-main.45/)

Dec 1
: Project presentations
  : 
    : Abhinav -- [Robust Question Answering Through Sub-part Alignment](https://aclanthology.org/2021.naacl-main.98/)

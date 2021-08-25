---
layout: home
title: CSCI 662
nav_exclude: true
seo:
  type: Course
  name: Advanced Natural Language Processing
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

### Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} 
{% for staffer in instructors %} 
{{ staffer }}
{% endfor %}

{% assign TAs = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in TAs %}
{{ staffer }}
{% endfor %}

### Lectures 
Monday and Wednesday 3:30–5:20 pm, KAP 166

### Textbook
Required: [Natural Language Processing - Eisenstein](https://mitpress.mit.edu/books/introduction-natural-language-processing)
-- or [free version](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)

Required: Selected papers from NLP literature, see (evolving) schedule

Optional: [Introduction to Deep Learning - Charniak](https://mitpress.mit.edu/books/introduction-deep-learning)
-- first three chapters [here](https://cs.brown.edu/courses/csci1460/assets/files/deep-learning.pdf)

Optional: [Speech and Language Processing 3rd edition - Jurafsky, Martin](https://web.stanford.edu/~jurafsky/slp3/)

### Grading

10% - In class participation \
10% - Posted questions before each in-class selected paper presentation \
10% - In-class selected paper presentation \
30% - Three Homeworks (10% each) \
40% - Project, comprising proposal (5%), first version of report (5%), in-class presentation (10%), and final report (20%). Done in small groups. \
Final report is due December 13, 2021, 4:00 PM PST

### Contact us

On Piazza, Slack, or in class/office hours. Please do not email (unless notified otherwise).

### Topics 
(subject to change per instructor/class whim) (will not be presented in this order):

  : Linguistic Stack (graphemes/phones - words - syntax - semantics - pragmatics - discourse)
  : Tools\:
    : Corpora, Corpus statistics, Data cleaning and munging
    : Annotation and crowdwork
    : Evaluation
    : Models/approaches: rule-based, automata/grammars, perceptron, logistic regression, neural network models
    : Effective written and oral communication
    : Components/Tasks/Subtasks:
    : Language Models
  : Syntax: POS tags, constituency tree, dependency tree, parsing
    : Semantics: lexical, formal, inference tasks
    : Information Extraction: Named Entities, Relations, Events
    : Generation: Machine Translation, Summarization, Dialogue, Creative Generation


{% for module in site.modules %}
{{ module }}
{% endfor %}

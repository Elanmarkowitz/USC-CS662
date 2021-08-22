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

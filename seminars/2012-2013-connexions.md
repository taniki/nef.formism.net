---
title: "connexion et relation"

seminar: "connexion et relation"

layout: default
---

<ul class="dates">
  <li><span>23.10</span> Introduction : plan du séminaire, bibliographie générale</li>
  <li><span>08.11</span> Exposé de Mathieu Marion (UQAM) : logique des jeux dans l’antiquité</li>
</ul>

## enjeux de la survenance humienne et sa critique

<ul class="dates">
{% for p in site.posts reversed %}
  {% if p.seminar == "2012-2013-connexions" and p.part == 1 %}
    <li><span>{{ p.date | date: "%d.%m" }}</span> <a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

## types de connexion et ordres d’unite

<ul class="dates">
{% for p in site.posts reversed %}
  {% if p.seminar == "2012-2013-connexions" and p.part == 2 %}
    <li><span>{{ p.date | date: "%d.%m" }}</span> <a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

<ul class="dates">
  <li><span>25.04</span> Conclusions</li>
</ul>


## Bibliographie additionnelle

- Garcia et Nef éds.  Métaphysique contemporaine, Vrin
- Glock Qu’est-ce que la philosophie analytique ?, trad. F. Nef Gallimard, Folio Essais
- Kévorkian éd. Metaphysique, Vrin [à paraître]
- Lowe A Survey of Metaphysics, Oxford University Press
- Loux Metaphysics, Routledge
- Loux et Zimmerman  The Oxford Handbook of Metaphysics, Oxford University Press
- Monnoyer éd. La structure du monde, Vrin
- Nef Qu’est-ce que la métaphysique ?, Gallimard, Folio Essais
- Nef Traité d’ontologie, Gallimard, Folio Essais
- Nef, Schmitt et Schneider éds. Ontologie, Vrin [à paraître]
- Tiercelin Le ciment des choses, Ithaque
- Tooley éds. Analytic Metaphysics, 4 vols, Routledge
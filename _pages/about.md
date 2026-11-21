---
layout: about
title: about
permalink: /
subtitle: Postdoctoral researcher · <a href='https://portal.if.usp.br/' target='_blank'>Institute of Physics, University of São Paulo</a>

profile:
  align: right
  image: osvaldo_profile.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Instituto de Física, USP</p>
    <p>Rua do Matão, 1371</p>
    <p>São Paulo, SP, Brazil</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items

latest_posts:
  enabled: false
---

<p class="text-right"><a href="{{ '/pt/' | relative_url }}">🇧🇷 Versão em português</a></p>

I am a postdoctoral researcher at the [Institute of Physics of the University of São Paulo](https://portal.if.usp.br/) (IF-USP), supported by FAPESP as a member of the thematic project _Multidisciplinary data analysis in Big Data: from high-energy physics to astrophysics and medical sciences_. I received my PhD in Physics from the Federal University of Rio de Janeiro (UFRJ) in 2026, advised by [Eduardo Fraga](https://inspirehep.net/authors/1009599), including a CAPES-PrInt sandwich period at Goethe University Frankfurt with [Jürgen Schaffner-Bielich](https://inspirehep.net/authors/990034). Before that I obtained my MSc in Physics at UFRJ and my BSc in Physics of Materials at the Federal University of Uberlândia (UFU).

My research sits at the interface of nuclear physics, astrophysics and cosmology. I study **strongly interacting matter under extreme conditions, and how to observe it**. In the early Universe, I investigate the QCD transition (including pion condensation driven by large lepton asymmetries) and its signatures in the cosmological gravitational-wave background. In astrophysics, I use compact stars as probes of matter at very high densities. I also compute properties of hot and dense matter, such as its response to electromagnetic fields, using perturbative QCD.

More recently, I have been applying Bayesian inference to the phenomenology of heavy-ion collisions, contributing to the ExTrEMe (EXperiment and TheoRy in Extreme MattEr) collaboration. You can read more on the [research]({{ '/research/' | relative_url }}) page or download my [CV]({{ '/cv/' | relative_url }}).

#### Interests

- QCD phase diagram and the QCD epoch of the early Universe
- Cosmological gravitational-wave background
- Compact stars, dense matter and dark matter
- Hot and dense QCD with perturbative methods
- Bayesian inference for heavy-ion collisions

#### Education

- **PhD in Physics**, 2026, Federal University of Rio de Janeiro (with a sandwich period at Goethe University Frankfurt)
- **MSc in Physics**, 2022, Federal University of Rio de Janeiro
- **BSc in Physics of Materials**, 2019, Federal University of Uberlândia

#### Recent talks

<ul>
{%- for t in site.data.talks limit: 5 -%}
<li><strong>{{ t.title }}</strong>, {{ t.event }}{% if t.location %} ({{ t.location }}){% endif %}, {{ t.year }}{% if t.award %} <i class="fa-solid fa-trophy" title="{{ t.award }}"></i> <em>{{ t.award }}</em>{% endif %}</li>
{%- endfor -%}
</ul>
<p><a href="{{ '/talks/' | relative_url }}">See all talks →</a></p>

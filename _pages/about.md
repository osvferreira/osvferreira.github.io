---
layout: about
title: about
permalink: /
profile:
  align: left
  image: osvaldo_profile.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <div style="text-align: center; margin-top: 0.75rem; font-family: Roboto, sans-serif;">
    <p style="font-size: 1.2rem; font-weight: 600; margin: 0 0 0.25rem;">Osvaldo Ferreira</p>
    <p style="margin: 0 0 0.6rem; line-height: 1.4;">Postdoctoral researcher · <a href="https://portal.if.usp.br/" target="_blank" rel="noopener noreferrer">Institute of Physics, University of São Paulo</a></p>
    <p style="font-size: 1.35rem; margin: 0; word-spacing: 0.35rem;">
    <a href="mailto:osvaldof@if.usp.br" title="Email" aria-label="Email"><i class="fa-solid fa-envelope"></i></a>
    <a href="https://inspirehep.net/authors/2698690" title="INSPIRE-HEP" aria-label="INSPIRE-HEP" target="_blank" rel="noopener noreferrer"><i class="ai ai-inspire"></i></a>
    <a href="https://orcid.org/0000-0002-6711-8308" title="ORCID" aria-label="ORCID" target="_blank" rel="noopener noreferrer"><i class="ai ai-orcid"></i></a>
    <a href="https://scholar.google.com/citations?user=LchBo5kAAAAJ" title="Google Scholar" aria-label="Google Scholar" target="_blank" rel="noopener noreferrer"><i class="ai ai-google-scholar"></i></a>
    <a href="http://lattes.cnpq.br/6790966492250263" title="Currículo Lattes" aria-label="Currículo Lattes" target="_blank" rel="noopener noreferrer"><i class="ai ai-lattes"></i></a>
    <a href="https://github.com/osvferreira" title="GitHub" aria-label="GitHub" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-github"></i></a>
    <a href="/assets/rendercv/rendercv_output/Osvaldo_Ferreira_CV.pdf" title="CV (PDF)" aria-label="CV (PDF)" target="_blank" rel="noopener noreferrer"><i class="ai ai-cv"></i></a>
    </p>
    </div>

selected_papers: false # selected papers are included in the page body (above recent talks)
social: false # contact icons are shown under the profile picture instead

announcements:
  enabled: false # includes a list of news items

latest_posts:
  enabled: false
---

<!-- Wrapper keeps all text in a column beside the profile picture (no wrapping under it) -->
<style>
  @media (min-width: 576px) {
    .about-main {
      overflow: hidden;
    }
  }
</style>
<div class="about-main" markdown="1">

<p class="text-right"><a href="{{ '/pt/' | relative_url }}">🇧🇷 Versão em português</a></p>

I am a postdoctoral researcher at the [Institute of Physics of the University of São Paulo](https://portal.if.usp.br/) (IF-USP), supported by FAPESP as a member of the thematic project _Multidisciplinary data analysis in Big Data: from high-energy physics to astrophysics and medical sciences_. I received my PhD in Physics from the Federal University of Rio de Janeiro (UFRJ) in 2026, advised by [Eduardo Fraga](https://inspirehep.net/authors/1009599), including a CAPES-PrInt sandwich period at Goethe University Frankfurt with [Jürgen Schaffner-Bielich](https://inspirehep.net/authors/990034). Before that I obtained my MSc in Physics at UFRJ and my BSc in Physics of Materials at the Federal University of Uberlândia (UFU).

My research sits at the interface of nuclear physics, astrophysics and cosmology. I study **strongly interacting matter under extreme conditions, and how to observe it**. In the early Universe, I investigate the QCD transition and its signatures in the cosmological gravitational-wave background. In astrophysics, I use compact stars as probes of matter at very high densities. I also compute properties of hot and dense matter, such as its response to electromagnetic fields, using perturbative QCD.

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

#### Selected publications

<div class="publications">
{% include selected_papers.liquid %}
</div>
<p><a href="{{ '/publications/' | relative_url }}">See all publications →</a></p>

#### Recent talks

<ul>
{%- for t in site.data.talks limit: 5 -%}
<li><strong>{{ t.title }}</strong>, {{ t.event }}{% if t.location %} ({{ t.location }}){% endif %}, {{ t.year }}{% if t.award %} <i class="fa-solid fa-trophy" title="{{ t.award }}"></i> <em>{{ t.award }}</em>{% endif %}</li>
{%- endfor -%}
</ul>
<p><a href="{{ '/talks/' | relative_url }}">See all talks →</a></p>

</div>

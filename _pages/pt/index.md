---
layout: about
title: português
permalink: /pt/
nav: true
nav_order: 6
description: Osvaldo Ferreira, pesquisador de pós-doutorado no Instituto de Física da Universidade de São Paulo (IF-USP).
profile:
  align: left
  image: osvaldo_profile.jpg
  image_circular: true
  more_info: >
    <div style="text-align: center; margin-top: 0.75rem; font-family: Roboto, sans-serif;">
    <p style="margin: 0 0 0.6rem; line-height: 1.4;">Pesquisador de pós-doutorado · <a href="https://portal.if.usp.br/" target="_blank" rel="noopener noreferrer">Instituto de Física, Universidade de São Paulo</a></p>
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

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<!-- Wrapper keeps all text in a column beside the profile picture (no wrapping under it) -->
<style>
  .profile figure {
    width: 80%;
    margin-left: auto;
    margin-right: auto;
  }
  @media (min-width: 576px) {
    .about-main {
      overflow: hidden;
    }
  }
</style>
<div class="about-main" markdown="1">

<p class="text-right"><a href="{{ '/' | relative_url }}">🇬🇧 English version</a></p>

<p class="text-center">
<a href="{{ '/pt/publicacoes/' | relative_url }}">Publicações</a> ·
<a href="{{ '/pt/palestras/' | relative_url }}">Palestras</a> ·
<a href="{{ '/pt/pesquisa/' | relative_url }}">Pesquisa</a> ·
<a href="{{ '/pt/ensino/' | relative_url }}">Ensino & Divulgação</a> ·
<a href="{{ '/pt/cv/' | relative_url }}">CV</a>
</p>

Sou pesquisador de pós-doutorado no [Instituto de Física da Universidade de São Paulo](https://portal.if.usp.br/) (IF-USP), com bolsa FAPESP, e membro do projeto temático _Análise de dados multidisciplinar em Big Data: de Física de Altas Energias à astrofísica e Ciências Médicas_. Sou doutor em Física pela Universidade Federal do Rio de Janeiro (UFRJ, 2026), sob orientação de [Eduardo Fraga](https://inspirehep.net/authors/1009599), com doutorado-sanduíche na Universidade Goethe de Frankfurt (Alemanha) pelo programa CAPES-PrInt, com [Jürgen Schaffner-Bielich](https://inspirehep.net/authors/990034). Sou mestre em Física pela UFRJ e bacharel em Física de Materiais pela Universidade Federal de Uberlândia (UFU).

Minha pesquisa situa-se na interface entre física nuclear, astrofísica e cosmologia, com foco no **comportamento da matéria fortemente interagente em condições extremas e nas formas de observá-la**. No universo primordial, investigo a transição da QCD e suas assinaturas no fundo cosmológico de ondas gravitacionais. Em astrofísica, estudo estrelas compactas como sondas da matéria em densidades muito altas. Também investigo propriedades da matéria quente e densa, como sua resposta eletromagnética, utilizando métodos de QCD perturbativa.

Mais recentemente, tenho aplicado métodos de inferência bayesiana à fenomenologia de colisões de íons pesados, contribuindo para as atividades da colaboração ExTrEMe (EXperiment and TheoRy in Extreme MattEr).

#### Interesses

- Diagrama de fases da QCD e a época da QCD no universo primordial
- Fundo cosmológico de ondas gravitacionais
- Estrelas compactas, matéria densa e matéria escura
- QCD quente e densa com métodos perturbativos
- Inferência bayesiana em colisões de íons pesados

#### Formação

- **Doutorado em Física**, 2026, Universidade Federal do Rio de Janeiro (com período sanduíche na Universidade Goethe de Frankfurt)
- **Mestrado em Física**, 2022, Universidade Federal do Rio de Janeiro
- **Bacharelado em Física de Materiais**, 2019, Universidade Federal de Uberlândia

#### Publicações selecionadas

<div class="publications">
{% include selected_papers.liquid %}
</div>
<p><a href="{{ '/pt/publicacoes/' | relative_url }}">Ver todas as publicações →</a></p>

#### Palestras recentes

<ul>
{%- for t in site.data.talks limit: 5 -%}
<li><strong>{{ t.title }}</strong>, {{ t.event }}{% if t.location %} ({{ t.location }}){% endif %}, {{ t.year }}{% if t.award_pt %} <i class="fa-solid fa-trophy" title="{{ t.award_pt }}"></i> <em>{{ t.award_pt }}</em>{% endif %}</li>
{%- endfor -%}
</ul>
<p><a href="{{ '/pt/palestras/' | relative_url }}">Ver todas as palestras →</a></p>

</div>

---
layout: default
homepage: true
title: Home
summary: Seyone Chithrananda is a Stanford Bioengineering PhD student working on machine learning for metagenomic discovery and tools to discover and engineer molecular function.
---

<header class="intro">
  <div class="intro-upper{% if site.portrait %} intro-upper--with-portrait{% endif %}">
    <div>
      <h1>Seyone Chithrananda</h1>
      <p class="pronunciation">(say-on)</p>
      <p class="intro-line">I’m a PhD student in Bioengineering at <a href="https://bioengineering.stanford.edu/people/seyone-chithrananda">Stanford</a> (since 2025), co-advised by <a href="https://www.fischbachgroup.org/">Michael Fischbach</a> and <a href="https://evodesign.org/">Brian Hie</a>.</p>
    </div>
    {% if site.portrait %}<img class="intro-portrait" src="{{ site.portrait | relative_url }}" alt="Portrait of Seyone Chithrananda">{% endif %}
  </div>
  <p class="focus-line">I work on machine learning for metagenomic discovery, building tools to discover and engineer molecular function.</p>
  <p class="focus-context">Most recently, I’ve been mining microbial genomes for immunomodulatory factors.</p>
</header>

<section id="research" class="content-section" aria-labelledby="research-heading">
  <h2 id="research-heading">Research</h2>
  <p>Viruses, bacteria, and parasites are a rich source of evolutionary innovation. Their genomes encode molecules that activate, redirect, or evade vertebrate innate and adaptive immunity; many remain uncharacterized. I’m building discovery engines to turn that diversity into testable hypotheses about immune function.</p>
  <p>In bacteria, I’m interested in the molecules that sharpen an immune response and those that blunt it. The Fischbach lab’s work on <a href="https://doi.org/10.1038/s41586-024-08489-4">commensal vaccines</a> and <a href="https://doi.org/10.1038/s41586-023-06431-8">defined gut communities such as hCom2</a> offers ways to study both sides—from adjuvant-like factors to immunoevasins and enzymes that degrade host defenses.</p>
  <ol class="research-list">
    <li><strong>Discover.</strong> I’m mining the genomes of viruses that establish chronic infection for overlooked ORFs that may encode immune modulators, then investigating which host proteins and pathways they affect.</li>
    <li><strong>Design.</strong> I want to engineer proteins that make commensal vaccines more effective and steer the responses they elicit.</li>
    <li><strong>Measure.</strong> I want to develop screens for immune tolerance and immunodominance—what the immune system overlooks and what it responds to most strongly.</li>
  </ol>
</section>

<section id="background" class="content-section" aria-labelledby="background-heading">
  <h2 id="background-heading">Background</h2>
  <p>I came to biology through computational chemistry and open-source work on <a href="https://deepchem.io/">DeepChem</a> and <a href="https://arxiv.org/abs/2010.09885">ChemBERTa</a>, alongside early research with <a href="https://www.matter.toronto.edu/">Alan Aspuru-Guzik</a> in Toronto. At <a href="https://www.berkeley.edu/">Berkeley</a>, I studied computer science and bioengineering and worked in <a href="https://doudnalab.org/">Jennifer Doudna’s lab</a> on RNA and protein design. At Microsoft Research, I worked with Kevin Yang on models connecting odor molecules, receptors, and perception. At Dyno Therapeutics, I worked on structure-guided sequence models to navigate epistatic fitness landscapes for gene therapy vectors.</p>
  <p>Before joining Michael and Brian’s labs, I rotated with <a href="https://profiles.stanford.edu/theodore-roth">Theo Roth</a>, learning to build scalable genetic discovery tools in primary human cells; with <a href="https://www.allenlabstanford.org/">Will Allen</a>, exploring high-throughput perturbation assays and algorithms for choosing which experiments to run next; and with <a href="https://profiles.stanford.edu/tony-wyss-coray">Tony Wyss-Coray</a>, using multiplexed mass spectrometry to map age-related changes in protein N-glycosylation. That last project also drew me toward immunology: glycans can mask antibody-binding sites, and changes in them can expose self-proteins to immune recognition, with implications for autoimmunity.</p>
  <p>I helped lead the research committee at <a href="https://ml.berkeley.edu/">Machine Learning at Berkeley</a> and co-organized the BioML seminar series. I enjoy helping newer researchers find their footing; if you’re getting started in computational biology, feel free to <a href="mailto:seyonec@stanford.edu">email me</a>.</p>
</section>

<section id="publications" class="content-section" aria-labelledby="publications-heading">
  <h2 id="publications-heading">Selected publications</h2>
  <p class="section-note">A few projects that shaped how I think. <a href="https://scholar.google.com/citations?user=ElZ0iNkAAAAJ">Full list on Google Scholar ↗</a></p>
  <ul class="publication-list">
    <li>
      <a class="paper-title" href="https://doi.org/10.64898/2026.08.27.741102">Forecasting viral evolution from phylogenetic trees</a>
      <span class="paper-meta">bioRxiv, 2026</span>
      <span class="paper-description">Learning from evolutionary histories to anticipate future viral mutations.</span>
    </li>
    <li>
      <a class="paper-title" href="https://doi.org/10.1016/j.cels.2026.101711">Mapping the combinatorial coding between olfactory receptors and perception with deep learning</a>
      <span class="paper-meta">Cell Systems, 2026</span>
      <span class="paper-description">A model connecting odor molecules to their receptors and the smells we perceive.</span>
    </li>
    <li>
      <a class="paper-title" href="https://doi.org/10.1039/D5DD00348B">ChemBERTa-3: an open source training framework for chemical foundation models</a>
      <span class="paper-meta">Digital Discovery, 2026</span>
      <span class="paper-description">Open-source tools for training and comparing molecular models, with experiments up to 1.1 billion molecules. Earlier <a href="https://arxiv.org/abs/2010.09885">ChemBERTa (NeurIPS ML4Molecules 2020)</a> tested an early molecular transformer for property prediction; <a href="https://arxiv.org/abs/2209.01712">ChemBERTa-2 (ELLIS 2021; preprint 2022)</a> tested how pretraining scale affects performance.</span>
    </li>
    <li>
      <a class="paper-title" href="https://doi.org/10.1038/s41467-024-55676-y">Functional protein mining with conformal guarantees</a>
      <span class="paper-meta">Nature Communications, 2025</span>
      <span class="paper-description">Searching protein databases efficiently while controlling the risk of missed results.</span>
    </li>
    <li>
      <a class="paper-title" href="https://doi.org/10.1038/s41467-024-54812-y">RNA language models predict mutations that improve RNA function</a>
      <span class="paper-meta">Nature Communications, 2024</span>
      <span class="paper-description">Using sequence models and experiments to find changes that improve RNA function.</span>
    </li>
  </ul>
</section>

<section id="elsewhere" class="content-section elsewhere" aria-labelledby="elsewhere-heading">
  <h2 id="elsewhere-heading">Elsewhere</h2>
  <p><a href="https://scholar.google.com/citations?user=ElZ0iNkAAAAJ">Google Scholar</a> · <a href="https://github.com/seyonechithrananda">GitHub</a> · <a href="https://x.com/SeyoneC">X</a></p>
  <p>Feel free to <a href="mailto:seyonec@stanford.edu">email me</a> about research or anything adjacent.</p>
</section>

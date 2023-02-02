---
layout: default
---
<header>
    <nav>
        <ul>
            <li><a href="/" class="active">Home</a></li>
            <li><a href="/blog.html">Blog</a></li>
            <li><a href="/assets/Seyone_CV_Dec_2022.pdf">CV</a></li>
        </ul>
    </nav>
</header>

<!-- new stuff -->
<!-- Master table -->
<table class="index">
  <tbody>
    <tr style="padding:0px">
      <td style="padding:0px">

        <!-- Introduction -->
        <table class="index" id="intro-table">
          <tbody>
            <tr style="padding:0px">
              <td style="width:63%;vertical-align:middle;">
                <p style="text-align:center">
                  <h1 style="text-align: center;">
                    <span class="tooltip">Seyone Chithrananda<span class="tooltip-text">/say-on/</span></span>
                  </h1>
                </p>
              </td>
              <td>
              </td>
            </tr>
            <tr style="padding:0px">
              <td style="width:63%;vertical-align:top">
                <p>
                  Hi, I'm Seyone, an undergrad student at Berkeley studying computer science & bioengineering. I'm interested in using computation as a mechanism for understanding how biology works — and how we can engineer it to improve human health. My research goal is to build computational tools for the design, engineering & interpretation of biological systems.
                </p>                  
                <p>
                  <highlight>If you'd like to chat, feel free to <a href="mailto:seyonec@berkeley.edu">email me!</a>!</highlight> I'm always excited to talk all things science. You can also find me on <a href="https://twitter.com/SeyoneC" target="_blank" rel="noreferrer noopener">Twitter</a> and <a href="https://github.com/seyonechithrananda" target="_blank" rel="noreferrer noopener">GitHub</a>.
                </p>
              </td>
              <td style="max-width:30%;vertical-align:text-top;padding-left:3%">
                <a href="/assets/images/ny_profile.jpg" id="headshot"><img alt="headshot" title="it's me!" src="/assets/images/ny_profile.jpg"></a>
              </td>
            </tr>
          </tbody>
        </table>

        <!-- newsfeed -->
        <!-- <h2>Newsfeed</h2>
        <p>Placeholder text</p>
        <table>
          <thead>
            <tr>
              <th>date</th>
              <th>description</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>(2022-07-07)</td>
              <td>placeholder text!</td>
            </tr>
          </tbody>
        </table> 
        <br>-->



        <!-- Blog -->
        <h2>Blog</h2>
        <table class="index">
          <tbody>
            <tr>
              <td>
                <p>
                  <a href="/blog.html">I'm starting to write again about</a> science, philosophy, biotech and public policy. Posts to be added below, and check out my <a href="https://seyonec.medium.com" target="_blank" rel="noreferrer noopener">Medium</a> for older ones.
                </p>

                <ul class="posts">
                  {% for post in site.posts limit:5 %}
                      <li>
                      {% if post.external_url %}
                          <a href="{{ post.external_url }}">{{ post.title }} ↗</a> (published at {{post.external_host}}) <span id="post-date">({{ post.date | date: "%-m/%-d/%y" }})</span>
                      {% else %}
                          <a href="{{ post.url }}">{{ post.title }}</a> <span id="post-date">({{ post.date | date: "%-m/%-d/%y" }})</span>
                      {% endif %}    
                      </li>
                  {% endfor %}
                </ul>

                <!-- <ul>
                  {% for post in site.posts limit:5 %}
                    <li>
                      <a href="{{ post.url }}">{{ post.title }}</a> <span id="post-date">({{ post.date | date: "%-Y-%m-%d" }})</span>
                    </li>
                  {% endfor %}
                </ul> -->

              </td>
            </tr>
          </tbody>
        </table>

        <!-- Research interests -->
        <h2>Research</h2>
        <table class="index">
          <tbody>
            <tr>
              <td>
                <p>
                  Presently, I'm interested in the intersection of machine learning for single-cell genomics & protein biology.
                </p>
                <p>
                   I'm a visiting undergrad researcher at the Broad Institute, advised by Eric Lander and Eeshit Dhaival Vashnav. This past summer, I was an research intern at <a href="https://www.dynotx.com" target="_blank" rel="noreferrer noopener">Dyno Therapeutics</a>, working on machine learning for protein engineering. Previously, I worked in the laboratory of Prof. Alan Aspuru-Guzik at the University of Toronto, and hacked on open source software at DeepChem, co-creating the ChemBERTa suite of chemical language models. My publications are viewable on <a href="https://scholar.google.com/citations?user=ElZ0iNkAAAAJ&hl=en&oi=ao" target="_blank" rel="noreferrer noopener">Google Scholar</a>.
                </p>
              </td>
            </tr>
          </tbody>
        </table>

        <!-- Publications and projects -->
        <table class="index">
          <tbody>

            <!-- pub -->
            <!-- <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/screen.jpg" alt="alt" title="title">
              </td>
              <td class="project-info">
                <span class="project-title">A Benchmark Framework for Evaluating Structure-to-Sequence Models for Protein Design</span>
                <br>
                Jeffrey Chan, <highlight>Seyone Chithrananda</highlight>, David Brookes, Sam Sinai
                <br>
                <input type="checkbox" id="trigger3">
                [<label for="trigger3"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  Abstract here.
                </span> /
                [<a href="/" target="_blank" rel="noreferrer noopener">proposal</a>] /
                [<a href="https://newscience.org/2022-summer-fellows/" target="_blank" rel="noreferrer noopener">press release</a>]
                <p></p>
                <p>
                  Blurb.
                </p>
              </td>
            </tr> -->


            <!-- pub -->
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/gb1.jpeg" alt="gb1" title="gb1 design region">
              </td>
              <td class="project-info">
                <span class="project-title">A Benchmark Framework for Evaluating Structure-to-Sequence Models for Protein Design</span>
                <br>
                Jeffrey Chan, <highlight>Seyone Chithrananda</highlight>, David Brookes, Sam Sinai
                <br>
                <i>NeurIPS ML for Structural Biology Workshop</i> (2022)
                <br>
                <input type="checkbox" id="trigger3">
                [<label for="trigger3"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  Abstract here.
                </span> /
                [<a href="https://recorder-v3.slideslive.com/?share=77740&s=6750961a-3f91-459a-9a77-e58ddf5d31aa" target="_blank" rel="noreferrer noopener">Presentation</a>] /
                [<a href="https://nips.cc/media/PosterPDFs/NeurIPS%202022/59042.png?t=1669918914.4617863" title="NeurIPS Poster" target="_blank" rel="noreferrer noopener">Poster</a>]
                <p></p>
                <p>
                  Preprint public soon. I built a benchmark for evaluating autoregressive structure-based protein design models (ESM-IF1, ProteinMPNN) on protein design using the GB1 dataset, by evaluating the log-likelihoods and joint sampling probabilities on highly epistastic regions of the protein. Alongside Jeffrey and David, I developed a model distillation approach for improving the generative capabilities of ESM.
                </p>
              </td>
            </tr>

            <!-- pub -->
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/chemberta.png" alt="schematic" title="training diagram">
              </td>
              <td class="project-info">
                <span class="project-title">ChemBERTa-2: Towards Chemical Foundation Models</span>
                <br>
                Walid Ahmed, Elana Simon, <highlight>Seyone Chithrananda</highlight>, Gabriel Grand, Bharath Ramsundar
                <br>
                <i>ELLIS ML for Molecule Discovery Workshop, arXiv</i> (2021, 2022)
                <br>
                <input type="checkbox" id="trigger2">
                [<label for="trigger2"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  Large pretrained models such as GPT-3 have had tremendous impact on modern natural language processing by leveraging self-supervised learning to learn salient representations that can be used to readily finetune on a wide variety of downstream tasks. We investigate the possibility of transferring such advances to molecular machine learning by building a chemical foundation model, ChemBERTa-2, using the language of SMILES. While labeled data for molecular prediction tasks is typically scarce, libraries of SMILES strings are readily available. In this work, we build upon ChemBERTa by optimizing the pretraining process. We compare multi-task and self-supervised pretraining by varying hyperparameters and pretraining dataset size, up to 77M compounds from PubChem. To our knowledge, the 77M set constitutes one of the largest datasets used for molecular pretraining to date. We find that with these pretraining improvements, we are competitive with existing state-of-the-art architectures on the MoleculeNet benchmark suite. We analyze the degree to which improvements in pretraining translate to improvement on downstream tasks.
                </span> /
                [<a href="https://arxiv.org/pdf/2209.01712.pdf" title="Preprint" target="_blank" rel="noreferrer noopener">preprint</a>]/
                [<a href="https://github.com/seyonechithrananda/bert-loves-chemistry" title="Github" target="_blank" rel="noreferrer noopener">Gtthub</a>]
                <p></p>
                <p>
                  Continuation of ChemBERTa project, working to scale pre-training language models from 10M to 77M molecules, and develop a novel pre-training task, <i>multi-task regression</i>. Worked on open-source integration of tokenizers, models within DeepChem library.
                </p>
              </td>
            </tr>
          

            <!-- pub -->
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/uncertainty.png" alt="schematic" title="training diagram">
              </td>
              <td class="project-info">
                <span class="project-title">Assigning confidence to molecular property prediction</span>
                <br>
                AkshatKumar Nigam, Robert Pollice, Matthew Hurley, Riley Hickman, Matteo Aldeghi, Naruki Yoshikawa, <highlight>Seyone Chithrananda</highlight>, Vincent Voelz, Alan Aspuru-Guzik
                <br>
                <i>Expert Opinions in Drug Discovery</i> (2021)
                <br>
                <input type="checkbox" id="trigger4">
                [<label for="trigger4"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  Introduction: Computational modeling has rapidly advanced over the last decades. Recently, machine learning has emerged as a powerful and cost-effective strategy to learn from existing datasets and perform predictions on unseen molecules. Accordingly, the explosive rise of data-driven techniques raises an important question: What confidence can be assigned to molecular property predictions and what techniques can be used?

                  Areas covered: The authors discuss popular strategies for predicting molecular properties, their corresponding uncertainty sources and methods to quantify uncertainty. First, the authors’ considerations for assessing confidence begin with dataset bias and size, data-driven property prediction and feature design. Next, the authors discuss property simulation via computations of binding affinity in detail. Lastly, they investigate how these uncertainties propagate to generative models, as they are usually coupled with property predictors.

                  Expert opinion: Computational techniques are paramount to reduce the prohibitive cost of brute-force experimentation during exploration. The authors believe that assessing uncertainty in property prediction models is essential whenever closed-loop drug design campaigns relying on high-throughput virtual screening are deployed. Accordingly, considering sources of uncertainty leads to better-informed validations, more reliable predictions and more realistic expectations of the entire workflow. Overall, this increases confidence in the predictions and, ultimately, accelerates drug design.
                </span> /
                [<a href="https://www.tandfonline.com/doi/abs/10.1080/17460441.2021.1925247?journalCode=iedc20" target="_blank" rel="noreferrer noopener">publication</a>]/
                [<a href="https://arxiv.org/abs/2102.11439" target="_blank" rel="noreferrer noopener">preprint</a>]

                <p></p>
                <p>
                  Part of team contributing a review encompassing the various sources of uncertainty in molecular property prediction. My contribution focused on detailing the various sources of uncertainty in data inputs, such as sources of experimental noise, docking errors, or various errors with forms of molecular representations like SMILES. 
                </p>
              </td>
            </tr>


            
            <!-- pub -->
            <!--
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/screen.jpg" alt="screen" title="there was a lot of TC work">
              </td>
              <td class="project-info">
                <span class="project-title">Deep learning and CRISPR-Cas13d ortholog discovery for optimized RNA targeting</span>
                <br>
                <a href="https://twitter.com/JingyiWei4" target="_blank" rel="noreferrer noopener">Jingyi Wei</a>, <a href="https://www.linkedin.com/in/peter-lotfy-ba045684/" target="_blank" rel="noreferrer noopener">Peter Lotfy</a>, <highlight>Kian Faizi</highlight>, <a href="https://twitter.com/EleanorWang" target="_blank" rel="noreferrer noopener">Eleanor Wang</a>, <a href="https://www.linkedin.com/in/slabodkin/" target="_blank" rel="noreferrer noopener">Hannah Slabodkin</a>, Emily Kinnaman, <a href="https://www.linkedin.com/in/sita-c-990a40171/" target="_blank" rel="noreferrer noopener">Sita Chandrasekaran</a>, Hugo Kitano, <a href="https://scholar.google.com/citations?user=hUi_OqkAAAAJ" target="_blank" rel="noreferrer noopener">Matthew G. Durrant</a>, <a href="https://scholar.google.com/citations?user=0vx-lmkAAAAJ&hl=en&oi=ao" target="_blank" rel="noreferrer noopener">Connor V. Duffy</a>, <a href="https://bioeng.berkeley.edu/faculty/patrick-hsu" target="_blank" rel="noreferrer noopener">Patrick D. Hsu</a>, <a href="https://biochemistry.stanford.edu/silvana-konermann" target="_blank" rel="noreferrer noopener">Silvana Konermann</a>
                <br>
                <i>bioRxiv.</i> (2021)
                <br>
                <input type="checkbox" id="trigger2">
                [<label for="trigger2"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  Transcriptome engineering technologies that can effectively and precisely perturb mammalian RNAs are needed to accelerate biological discovery and RNA therapeutics. However, the broad utility of programmable CRISPR-Cas13 ribonucleases has been hampered by an incomplete understanding of the design rules governing guide RNA activity as well as cellular toxicity resulting from off-target or collateral RNA cleavage. Here, we sought to characterize and develop Cas13d systems for efficient and specific RNA knockdown with low cellular toxicity in human cells. We first quantified the performance of over 127,000 RfxCas13d (CasRx) guide RNAs in the largest-scale screen to date and systematically evaluated three linear, two ensemble, and two deep learning models to build a guide efficiency prediction algorithm validated across multiple human cell types in orthogonal secondary screens (<a href="http://RNAtargeting.org">http://RNAtargeting.org</a>). Deep learning model interpretation revealed specific sequence motifs at spacer position 15-24 along with favored secondary features for highly efficient guides. We next identified 46 novel Cas13d orthologs through metagenomic mining for activity screening, discovering that the metagenome-derived DjCas13d ortholog achieves low cellular toxicity and high transcriptome-wide specificity when deployed against high abundance transcripts or in sensitive cell types, including hESCs. Finally, our Cas13d guide efficiency model successfully generalized to DjCas13d, highlighting the utility of a comprehensive approach combining machine learning with ortholog discovery to advance RNA targeting in human cells.
                </span> /
                [<a href="https://doi.org/10.1101/2021.09.14.460134" target="_blank" rel="noreferrer noopener">preprint</a>]
                <p></p>
                <p>
                  I helped conduct a 127,000-guide CRISPR-Cas13d screen to identify guide RNA design rules and optimize transcriptome editing efficiency.
                </p>
              </td>
            </tr>
            -->


            <!-- pub -->
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/scaling_law.png" alt="data scaling law" title="scaling law">
              </td>
              <td class="project-info">
                <span class="project-title">ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction</span>
                <br>
                <highlight>Seyone Chithrananda</highlight>, Gabriel Grand, Bharath Ramsundar
                <br>
                <i>NeurIPS ML for Molecules Workshop</i>, 2020
                <br>
                <input type="checkbox" id="trigger5">
                [<label for="trigger5"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  GNNs and chemical fingerprints are the predominant approaches to representing molecules for property prediction. However, in NLP, transformers have become the de-facto standard for representation learning thanks to their strong downstream task transfer. In parallel, the software ecosystem around transformers is maturing rapidly, with libraries like HuggingFace and BertViz enabling streamlined training and introspection. In this work, we make one of the first attempts to systematically evaluate transformers on molecular property prediction tasks via our ChemBERTa model. ChemBERTa scales well with pretraining dataset size, offering competitive downstream performance on MoleculeNet and useful attention-based visualization modalities. Our results suggest that transformers offer a promising avenue of future work for molecular representation learning and property prediction. To facilitate these efforts, we release a curated dataset of 77M SMILES from PubChem suitable for large-scale self-supervised pretraining.
                </span> /
                [<a href="https://ml4molecules.github.io/papers2020/ML4Molecules_2020_paper_67.pdf" title="workshop" target="_blank" rel="noreferrer noopener">workshop paper</a>]/
                [<a href="https://www.youtube.com/watch?v=b3AMBZsgvug&t=2497s" title="talk" target="_blank" rel="noreferrer noopener">Talk</a>]
                <p></p>
                <p>
                  Lead author on ChemBERTa, the first language model for molecular property prediction. Developed open-source project, amassing ~1M model downloads and ~110 citations to date.
                </p>
              </td>
            </tr>



            <!-- pub -->
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/bioe190.png" alt="dynamo" title="dynamo cell-fate transition">
              </td>
              <td class="project-info">
                <span class="project-title">Analysis of human hematopoietic cells using Scanpy and Dynamo</span>
                <br>
                [<a href="https://docs.google.com/document/d/1oe9BXBw_lpwiHd0QVEPzW0YsFhKXTdXc2dGkUtijjDQ/edit?usp=sharing" title="boolean-lac on GitHub" target="_blank" rel="noreferrer noopener">Report</a>]
                <p></p>
                <p>
                  I analyzed raw hematopoiesis data from the Cell paper, <i>‘Mapping transcriptomic vector fields of single cells’</i>. First, I used clustering tools such as the Leiden algorithm in Scanpy to find marker genes by analyzing the most differentially expressed genes in specific clusters with regards to their respective cell type. I then used dynamo’s ability to compute RNA velocity for sc-RNA seq data to better understand cell fate transition in the dataset, and compute in-silico perturbation tests to investigate cell fate outcomes after perturbing key regulators like GAT1. Class project for <a href="https://www.coursicle.com/berkeley/courses/BIOENG/190/" target="_blank" rel="noreferrer noopener">BIOENG 190/290 (cross-listed graduate course)</a>.
                 </p>
              </td>
            </tr>
          </tbody>
        </table>

        <!-- Acknowledgements -->
        <h2>Acknowledgements</h2>
        <p>
          My homepage layout uses <a href="https://www.kianfaizi.com" target="_blank" rel="noreferrer noopener">Kian Fazi's</a> wonderful website template (also inspired by Jon Barron).
        </p>

        <!-- Mentors -->
        <h2>Acknowledgements</h2>
        <p>
          I've been very priviledged to learn from some incredible mentors over the years, both from research and other experience. Many of them took me on when I had nothing to offer them, and I can't thank them enough. In no particular order:
          
          - Dr. Bharath Ramsundar ~ Deep Forest Sciences
          - Dr. Angelica Parente ~ Sutter Hill Ventures
          - Prof. Tyler Cowen ~ Mercatus Centre/Emergent Ventures
          - Prof. Alan Aspuru-Guzik ~ University of Toronto
          - Prof. Eric Lander ~ Broad Institute of MIT & Harvard
          - Dr. Jeffrey Chan & Dr. David Brookes ~ Dyno Therapeutics
          - Navid Nathoo & Nadeem Nathoo ~ The Knowledge Society
        </p>


      </td>
    </tr>
  </tbody>
</table>



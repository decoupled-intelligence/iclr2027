---
layout: default2
permalink: /
title: 'Coupled or Decoupled? Drawing the Boundaries of Foundation Models'
nav_order: 1
---

<!--  <div class="button-container"> -->
<!--      <a href="https://forms.office.com/e/HK2YV14gSi" class="custom-button">Register for Workshop</a> -->
<!--  <a href="https://forms.office.com/e/LDj3QMiAYZ" class="custom-button">Give a talk and/or present poster of your work</a> -->
<!--  </div> -->

<!-- <br> -->

### Workshop Description

**Proposed workshop at ICLR 2027.** The program, submission dates, and participation are subject to workshop acceptance.

Foundation models (FMs) bundle many functions, including reasoning, knowledge, memory, preferences, identity, and control, within a single model or tightly coupled system. This workshop asks: **which functions should remain coupled, and which should be separated by explicit, controllable interfaces?** We use *decoupled intelligence* as an umbrella term for systems that deliberately separate functions commonly entangled in monolithic FMs. We remain agnostic about whether stronger or weaker decoupling is preferable: suitable systems may span a spectrum of coupling levels based on practical needs.

Examples include separating contextual from parametric memory through [memory modules](https://arxiv.org/abs/1410.5401), retrieval, and tools; externalizing knowledge through [limited memory language models](https://openreview.net/forum?id=cvztBvlglK); separating local data from centralized computation through [decoupled embeddings](https://arxiv.org/abs/2410.05021); separating identity from usage through [private or pseudonymous inference](https://openanonymity.ai/); and separating intention from intelligence through [Scientist AI](https://arxiv.org/abs/2502.15657). Additional interfaces can also introduce failure modes, coordination costs, security risks, or losses in end-to-end performance.

These choices raise fundamental questions: what is the irreducible core of a generally capable model? Which capabilities can be externalized without sacrificing performance or generalization? When does modularity improve adaptability, controllability, privacy, or auditability, and when does it create brittle interfaces or new attack surfaces? Multimodal systems sharpen these questions because reasoning, memory, knowledge, and representations interact across visual, auditory, textual, and sensor modalities.

Data ownership, copyright and licensing, privacy, personalization, and differing user values also affect where data, memory, preferences, and control should reside. Foundation models increasingly operate within systems involving retrieval, memory, tools, and application-specific harnesses; see [Li et al., Agent Harness Engineering: A Survey](https://openreview.net/pdf?id=eONq7FdiHa). Architectural boundaries therefore matter for data governance, provider dependence, and user sovereignty as well as model performance.

Our intended outputs are shared taxonomies, empirical evaluation criteria, and architectural principles that clarify trade-offs among adaptability, reliability, efficiency, safety, and user sovereignty. We plan to summarize the discussions in a post-workshop report.

### Problems We Aim to Advance

1. **Characterizing coupling:** develop a shared vocabulary and candidate metrics for entanglement among reasoning, knowledge, memory, and control.
2. **When separation helps or hurts:** compare coupled and decoupled designs under controlled conditions.
3. **Reliability and control:** evaluate both the benefits of explicit interfaces and the failure modes and attack surfaces they introduce.
4. **Limits of decomposition:** identify interactions that cannot be separated without loss.

### Importance, Novelty, and Audience

The placement of architectural boundaries is itself our object of study. Evidence that a capability should remain tightly coupled is as relevant as evidence that it should be externalized.

We bring together researchers in foundation models, representation learning, modular and compositional learning, continual learning, retrieval and memory, multimodal learning, AI safety, privacy, personalization, agent systems, human-centered AI, and ML systems. These communities often study related boundary-setting problems with different terminology and evaluation criteria. Comparing their findings can help establish a common language and reveal trade-offs across fields.

### [Call for Papers]({{ '/call/' | relative_url }}) and [Competition]({{ '/competition/' | relative_url }})

The proposed program combines full and tiny papers with a competition, invited and contributed talks, a panel, and two extended poster sessions. All accepted papers will receive a poster presentation. The panel asks **What Should or Should Not Be Decoupled?** and will bring together contrasting perspectives. Audience questions will be collected in advance and live.

Accepted papers, posters, and slides will be linked from this website. Subject to speaker consent and ICLR recording arrangements, talks and the panel will also be shared. Competition artifacts and a post-workshop report will remain available after the event.

### Invited Speakers

Participation statuses below follow the current proposal. Travel arrangements may change; talk times are TBD.

<div class="team-container speaker-container">
    <div class="sponsor">
        <img src="{{ '/assets/img/speakers/yoshua_bengio.jpg' | relative_url }}" alt="Yoshua Bengio">
        <p><a href="https://yoshuabengio.org/">Yoshua Bengio</a><br>Mila / Universit&eacute; de Montr&eacute;al<br>Confirmed<br>Talk at TBD</p>
        <p>Can Intentions Be Separated from Capabilities? Lessons from Scientist AI</p>
    </div>
    <div class="sponsor">
        <img src="{{ '/assets/img/speakers/jennifer_sun.jpg' | relative_url }}" alt="Jennifer Sun">
        <p><a href="https://jenjsun.com/">Jennifer Sun</a><br>Cornell University<br>Confirmed<br>Talk at TBD</p>
        <p>What Knowledge Belongs in Parameters? LMLM and Knowledge Externalization</p>
    </div>
    <div class="sponsor">
        <img src="{{ '/assets/img/speakers/karl_friston.jpg' | relative_url }}" alt="Karl Friston">
        <p><a href="https://profiles.ucl.ac.uk/2747-karl-friston">Karl Friston</a><br>University College London<br>Confirmed<br>Talk at TBD</p>
        <p>What Must Stay Coupled for Adaptation? An Active-Inference View</p>
    </div>
    <div class="sponsor">
        <!-- Replace the placeholder with /assets/img/speakers/shengran_hu.jpg when ready. -->
        <img src="{{ '/assets/img/speakers/placeholder.svg' | relative_url }}" alt="Shengran Hu">
        <p>Shengran Hu<br>Recursive Superintelligence<br>Confirmed<br>Talk title and time TBD</p>
    </div>
    <div class="sponsor">
        <img src="{{ '/assets/img/speakers/philip_isola.jpg' | relative_url }}" alt="Philip Isola">
        <p><a href="https://web.mit.edu/phillipi/">Philip Isola</a><br>MIT<br>Tentative<br>Talk at TBD</p>
        <p>Which Representations Should Be Shared Across Modalities, and Which Should Stay Specialized?</p>
    </div>
    <div class="sponsor">
        <!-- Replace the placeholder with /assets/img/speakers/ruihan_wu.jpg when ready. -->
        <img src="{{ '/assets/img/speakers/placeholder.svg' | relative_url }}" alt="Ruihan Wu">
        <p>Ruihan Wu<br>OpenAI<br>Invited<br>Talk at TBD</p>
        <p>What User Data Should Stay Out of Model Weights? Privacy-Preserving LLMs</p>
    </div>
</div>

Patrick Lewis (Cohere) is a proposed additional speaker; participation is not yet confirmed. Proposed focus: Can Instructions Do the Decoupling? Retrieval Grounding as Behavior-Level Separation.

<br>


<!-- ## Organization Chairs -->
<!-- <html> -->
<!--     <div class="team-container"> -->
<!--         <div class="team-member">
<!--             <img src="/assets/img/organizers/luo_mai.jpg" alt="Name 7"> -->
<!--             <p><a href="https://luomai.github.io/">Luo Mai</a> -->
<!--             <br>University of Edinburgh</p> -->
<!--         </div> -->
<!--         <div class="team-member"> -->
<!--             <img src="/assets/img/organizers/edoardo_ponti.jpg" alt="Name 8"> -->
<!--             <p><a href="https://ducdauge.github.io/">Edoardo Ponti</a> -->
<!--             <br>University of Edinburgh</p> -->
<!--         </div> -->
<!--     </div> --> 
<!-- </html> -->

<br>

### Organizers

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/yihong_chen.jpg' | relative_url }}" alt="Yihong Chen">
            <p><a href="https://oatml.cs.ox.ac.uk/members/yihong_chen/">Yihong Chen</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/yi_joshua_ren.jpg' | relative_url }}" alt="Yi Joshua Ren">
            <p><a href="https://oatml.cs.ox.ac.uk/members/yi_ren/">Yi (Joshua) Ren</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/pierre_luc_st_charles.jpg' | relative_url }}" alt="Pierre-Luc St-Charles">
            <p><a href="https://www.linkedin.com/in/plstcharles/">Pierre-Luc St-Charles</a>
            <br>LawZero</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/gael_gendron.jpg' | relative_url }}" alt="Gael Gendron">
            <p><a href="https://ggendro.github.io/">Gaël Gendron</a>
            <br>LawZero</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/kevin_kasa.jpg' | relative_url }}" alt="Kevin Kasa">
            <p><a href="https://kevinkasa.github.io/">Kevin Kasa</a>
            <br>LawZero</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/sebastien_bratieres.jpg' | relative_url }}" alt="Sebastien Bratieres">
            <p><a href="https://it.linkedin.com/in/sebastien-bratieres">Sébastien Bratières</a>
            <br>Translated <br> DVPS</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/yarin_gal.jpg' | relative_url }}" alt="Yarin Gal">
            <p><a href="https://oatml.cs.ox.ac.uk/members/yarin/">Yarin Gal</a>
            <br>University of Oxford <br> AISI</p>
        </div>
    </div>
</html>

<!--
### Scientific Committee

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/olivier_pietquin.jpg" alt="Name 9">
            <p><a href="https://www.linkedin.com/in/opietquin/">Olivier Pietquin</a>
            <br>Cohere</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/kenny_smith.jpeg" alt="Name 9">
            <p><a href="http://www.lel.ed.ac.uk/~kenny/">Kenny Smith</a>
            <br>University of Edinburgh</p>
        </div>
    </div>
</html>
-->

<br>

### Program Committee

Confirmed members listed in the current proposal:

- **University of Oxford:** Anushka Nair, Yonatan Gideoni, Daniella Ye, Lin Li, Hao Fei, Shengqiong Wu, Luckeciano Carvalho Melo, Yug Oswal, Hao Zha, Guanzhe Hong, Dilan Yang
- **University of Rochester:** Xiangxiang Xu
- **Ant Group:** Zhenduo Zhang
- **City University of Hong Kong:** Fengji Zhang
- **Tsinghua University:** Yingrong Qin
- **University College London:** Jiayi Wang, Keyue Jiang, Chunan Liu
- **University of Cambridge:** Alex Iacob
- **Meta:** Shalini Malti
- **The University of Manchester:** Haripriya Harikumar
- **University of Edinburgh:** Christina Xiaotang Du, Ivan Vegner
- **Technical University Berlin:** Wolf Siegfried Rieder
- **Independent Researcher:** Luca Franceschi
- **Canopy Labs:** Eric Passawis
- **Cohere / University of Pennsylvania:** Keenan Samway
- **Metamorphic:** Shell Hu
- **Mila:** Jacob Lavoie, Bruce Wen
- **LawZero:** Ali Harakeh, Vincent Mai, Damiano Fornasiere, Andy Huang, Aissatou Diallo, Dmitri Carpov
- **University of Auckland:** Qiming Bao, Tim Pistotti, Yuchen Su
- **Shanghai AI Lab:** Yang Chen

### Sponsors

<html>
    <div class="sponsors-container">
        <a class="sponsor-logo" href="https://www.ox.ac.uk/" aria-label="University of Oxford">
            <img src="{{ '/assets/img/sponsors/oxford.png' | relative_url }}" alt="University of Oxford">
        </a>
        <a class="sponsor-logo" href="https://lawzero.org/" aria-label="LawZero">
            <img src="{{ '/assets/img/sponsors/lawzero.png' | relative_url }}" alt="LawZero">
        </a>
        <a class="sponsor-logo" href="https://www.translated.com/research" aria-label="DVPS">
            <img src="{{ '/assets/img/sponsors/dvps.png' | relative_url }}" alt="DVPS">
        </a>
    </div>
</html>

<style>
.button-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 16px;
    margin: 24px 0;
    flex-wrap: wrap;
}

.custom-button {
    background-color: var(--global-theme-color);
    border: none;
    color: white;
    padding: 12px 24px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    cursor: pointer;
    border-radius: 6px;
}

.team-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 28px 24px;
    max-width: 1024px;
    padding: 18px 0 28px;
    margin: 0 auto;
}

.speaker-container {
    grid-template-columns: repeat(3, minmax(0, 1fr));
}

.team-member,
.sponsor {
    text-align: center;
    min-width: 0;
}

.team-member img {
    object-fit: cover;
    border: 4px solid rgba(0, 118, 223, 0.12);
    border-radius: 50%;
    box-shadow: 0 10px 24px rgba(0, 61, 115, 0.1);
    height: 180px;
    margin-bottom: 12px;
    width: 180px;
}

.team-member p,
.sponsor p {
    line-height: 1.45;
    margin: 0;
}

.team-member p a,
.sponsor p a {
    color: var(--global-theme-color);
    display: inline-block;
    font-size: 18px;
    font-weight: bold;
    text-decoration: none;
}

.team-member p a:hover,
.sponsor p a:hover {
    text-decoration: underline;
}

.sponsor {
    font-size: 18px;
    font-weight: bold;
}

.sponsor img {
    aspect-ratio: 1 / 1;
    border-radius: 6px;
    box-shadow: 0 12px 28px rgba(0, 61, 115, 0.12);
    margin-bottom: 12px;
    object-fit: cover;
    width: 100%;
}

.sponsors-container {
    align-items: center;
    display: grid;
    gap: 28px;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    margin: 18px auto 36px;
    max-width: 860px;
}

.sponsor-logo {
    align-items: center;
    border-radius: 6px;
    display: flex;
    justify-content: center;
    min-height: 96px;
    padding: 18px 22px;
}

.sponsor-logo img {
    max-height: 88px;
    max-width: 100%;
    object-fit: contain;
}

.caption {
    margin-top: 12px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
}

.right-half {
    flex: 1;
    height: 500px;
}

.news-box {
    border: 1px solid rgba(0, 118, 223, 0.16);
    padding: 16px;
    max-width: 680px;
    margin: 0 auto;
    background-color: rgba(0, 118, 223, 0.04);
}

@media (max-width: 768px) {
    .speaker-container {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

@media (max-width: 600px) {
    .news-box {
        width: 100%;
    }

    .team-container {
        grid-template-columns: 1fr;
    }

    .speaker-container {
        grid-template-columns: 1fr;
    }

    .team-member img {
        height: 160px;
        width: 160px;
    }

    .sponsors-container {
        grid-template-columns: 1fr;
    }
}
</style>

<br><br>

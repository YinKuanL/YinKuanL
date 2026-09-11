<div align="center">

<a href="https://github.com/YinKuanL">
  <img src="./assets/galaxy-hero.png" width="100%" alt="Yin-Kuan Liang — Selective Communication for Distributed Learning" />
</a>

<br/><br/>

## Selective Communication for Distributed Learning

<sub>Learning systems should decide <b>when</b>, <b>what</b>, and <b>with whom</b> to communicate.</sub>

<br/><br/>

<a href="#research"><img src="./assets/nav-research.svg" height="36" alt="Research"/></a>
&nbsp;
<a href="#direction"><img src="./assets/nav-direction.svg" height="36" alt="Direction"/></a>
&nbsp;
<a href="https://github.com/YinKuanL?tab=repositories"><img src="./assets/nav-repositories.svg" height="36" alt="Repositories"/></a>

</div>

<br/>

---

<a id="direction"></a>

## Research Direction

My research studies **communication as a learnable decision** in distributed and collaborative machine learning.

Rather than assuming fixed synchronization or fixed peers, I am interested in systems that learn:

**when** communication is useful · **what** information is worth exchanging · **with whom** collaboration creates value

<br/>

`adaptive topology` · `communication efficiency` · `causal collaboration` · `continual learning` · `distributed foundation models`

```text
                         distributed learning
                                │
                  ┌─────────────┼─────────────┐
                  ▼             ▼             ▼
                WHEN          WHAT           WHOM
                  │             │             │
                  └─────────────┼─────────────┘
                                ▼
                    communication as a decision
                                │
                                ▼
                    efficient collective learning
```

<details>
<summary><b>Long-term research thread</b></summary>

<br/>

My current work connects four directions:

- **Adaptive collaboration** — learning sparse or dynamic communication structures instead of assuming full connectivity.
- **Communication-efficient learning** — reducing communication while preserving useful information flow and convergence.
- **Continual & causal collaboration** — estimating whether collaboration creates future value as tasks and data distributions evolve.
- **Distributed foundation models** — extending selective synchronization and adaptive communication to modern neural networks and language-model training.

</details>

---

<a id="research"></a>

## Selected Research

### 01 / [LFHE](https://github.com/YinKuanL/LFHE)

**Local topology adaptation for fully decentralized learning.**

`DECENTRALIZED LEARNING` · `TOPOLOGY ADAPTATION` · `NON-IID`

Local learners evolve sparse communication neighborhoods using only locally available signals under bounded communication.

[Repository →](https://github.com/YinKuanL/LFHE)

<br/>

### 02 / [Dynamics & Scaling of Local Topology Evolution](https://github.com/YinKuanL/LFHE_workshop2026)

**When does local topology evolution continue to scale?**

`SCALING` · `NETWORK MIXING` · `COMMUNICATION`

Studies how population size, data allocation, graph structure, and communication capacity shape decentralized learning at scale.

[Repository →](https://github.com/YinKuanL/LFHE_workshop2026)

<br/>

### 03 / [TA-DVFG](https://github.com/YinKuanL/TA-DVFG)

**Sparse collaboration without representation alignment.**

`GRAPH LEARNING` · `SPARSE COLLABORATION` · `PREDICTION SPACE`

Heterogeneous graph predictors collaborate through prediction space over a learned sparse topology.

[Repository →](https://github.com/YinKuanL/TA-DVFG)

<details>
<summary><b>How the projects connect</b></summary>

<br/>

**LFHE** studies *who should communicate* in fully decentralized learning.

**TA-DVFG** studies *which collaborators remain useful* when predictors are heterogeneous.

My current continual and causal work studies *when collaboration creates future value*.

Together, these projects move toward learning communication policies rather than treating communication as a fixed systems assumption.

</details>

<!--
Future research can be added without redesigning the page:

### 04 / [Project Name](REPOSITORY_URL)

**One-line contribution.**

`TAG` · `TAG` · `TAG`

One short sentence.

[Repository →](REPOSITORY_URL)
-->

---

## Engineering

### [I/We](https://github.com/YinKuanL/durhackx_2025)
Multi-agent AI collaboration platform · **3rd Place, DurHack 2025**

### [Taiwan Stock Farm](https://github.com/YinKuanL/Taiwan-Stock-Farm)
Full-stack Taiwan equities visualization product.

<details>
<summary><b>Technical stack</b></summary>

<br/>

`Python` · `PyTorch` · `NumPy` · `SciPy` · `NetworkX` · `Linux`  
`TypeScript` · `React` · `Next.js` · `Cloudflare Workers` · `Swift`

</details>

---

## Current Frontier

Exploring **distributed training for modern neural networks and language models** through:

`selective synchronization` · `communication-efficient training` · `adaptive collaboration`

<!--
This section can later expand into:
- Publications
- Selected Results
- Current Work
without changing the overall layout.
-->

---

<div align="center">

<sub><b>Communication should be a learned decision, not a fixed assumption.</b></sub>

</div>

<div align="center">

<a href="https://github.com/YinKuanL">
  <img src="./assets/galaxy-hero.png" width="100%" alt="Yin-Kuan Liang — Distributed Learning · Collaborative Intelligence · ML Systems" />
</a>

<br/><br/>

### Distributed Learning · Collaborative Intelligence · ML Systems

I study how learning systems decide **when, what, and with whom to communicate** under resource constraints.

<br/>

<a href="#research"><img src="./assets/btn-research.svg" height="38" alt="Research"/></a>
&nbsp;
<a href="#research-direction"><img src="./assets/btn-direction.svg" height="38" alt="Research Direction"/></a>
&nbsp;
<a href="#engineering"><img src="./assets/btn-engineering.svg" height="38" alt="Engineering"/></a>
&nbsp;
<a href="https://github.com/YinKuanL?tab=repositories"><img src="./assets/btn-repositories.svg" height="38" alt="All Repositories"/></a>

</div>

<br/>

---

<a id="research-direction"></a>

## Research Direction

My research is centered on **selective communication in distributed learning**:

> **How can learning systems decide when to communicate, what to exchange, and with whom to collaborate?**

I am especially interested in four connected directions:

**Adaptive collaboration**  
Learning sparse or dynamic communication structures instead of assuming fixed neighbors or full connectivity.

**Communication-efficient learning**  
Reducing communication while preserving useful information flow, convergence, and coordination.

**Continual & causal collaboration**  
Estimating whether collaboration actually creates future value under distribution shift and evolving tasks.

**Distributed foundation models**  
Extending selective synchronization and adaptive communication to modern neural networks and language-model training.

```text
                    distributed learning
                           │
            ┌──────────────┼──────────────┐
            ▼              ▼              ▼
          WHEN           WHAT            WHOM
            │              │              │
            └──────────────┼──────────────┘
                           ▼
               communication as a decision
                           │
                           ▼
               efficient collective learning
```

---

<a id="research"></a>

## Research

### 01 · [LFHE](https://github.com/YinKuanL/LFHE)
**Local topology adaptation for fully decentralized learning.**  
Sparse communication neighborhoods evolve from local signals under heterogeneous data and bounded communication.

### 02 · [Dynamics & Scaling of Local Topology Evolution](https://github.com/YinKuanL/LFHE_workshop2026)
**Understanding when local topology evolution continues to scale.**  
Studies population size, data allocation, graph mixing, degree, and communication capacity.

### 03 · [TA-DVFG](https://github.com/YinKuanL/TA-DVFG)
**Sparse collaboration without representation alignment.**  
Heterogeneous graph predictors collaborate through prediction space over a learned sparse topology.

<details>
<summary><b>How these projects connect</b></summary>

<br/>

`LFHE` asks **who should communicate** in fully decentralized learning.

`TA-DVFG` asks **which collaborators are useful** when predictors are heterogeneous.

My current causal/continual work asks **when collaboration creates future value**.

Together, these projects move toward learning communication policies rather than treating communication as a fixed system assumption.

</details>

<!--
Future research:
### 04 · [Project Name](REPOSITORY_URL)
**One-line contribution.**
One short sentence.
-->

---

<a id="engineering"></a>

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

<div align="center">

<sub>Communication should be a learned decision, not a fixed assumption.</sub>

</div>

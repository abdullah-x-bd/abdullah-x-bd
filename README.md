<p align="center">
  <img src="./assets/hero.svg" alt="Abdullah X. | AI safety, learning systems and institutional design" width="100%" />
</p>

<p align="center">
  <a href="https://www.projectawareai.org/research/">Research</a>
  &nbsp;·&nbsp;
  <a href="#selected-preprints">Preprints</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/abdullah-x-bd?tab=repositories">Open-source work</a>
  &nbsp;·&nbsp;
  <a href="https://www.projectawareai.org/">Project AWARE</a>
</p>

<br/>

### About

I study the safety of AI systems at three levels: **what models represent**, **how agents act**, and **which rules hold when those agents operate inside institutions**.

My work combines controlled experiments, mechanistic interpretability, reproducible systems research, and questions from economics and governance. I am especially interested in the gap between *a system appearing safe* and *having evidence that explains when and why it is safe*.

I founded [**Project AWARE**](https://www.projectawareai.org/), a New Delhi-based think tank working on institutional AI safety through research, diplomacy, and capacity building.

<br/>

### Research directions

| 01 / MODEL INTERNALS | 02 / AGENT BEHAVIOUR | 03 / INSTITUTIONAL DESIGN |
| :--- | :--- | :--- |
| State abstractions, causal interventions, machine unlearning | Controlled evaluations, failure modes, behavioural robustness | Multi-agent governance, authority, oversight and incentives |

<br/>

### Selected work

<sub>RESEARCH ARTIFACTS · EXPERIMENTAL SYSTEMS · REPRODUCIBILITY</sub>

<table>
  <tr>
    <td width="50%" valign="top">
      <sub>01 / MECHANISTIC INTERPRETABILITY</sub>
      <h3><a href="https://github.com/abdullah-x-bd/markovian-circuit-tracing">Markovian Circuit Tracing</a></h3>
      <p>When can transformer activations be understood as a system of latent states and transitions? A ground-truth HMM benchmark tests state recovery and causal interventions, including where the abstraction fails.</p>
      <p><a href="https://github.com/abdullah-x-bd/markovian-circuit-tracing">Code &amp; results ↗</a> · <a href="https://arxiv.org/abs/2605.20824">Preprint ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <sub>02 / MACHINE UNLEARNING</sub>
      <h3><a href="https://github.com/abdullah-x-bd/unlearning">Unlearning at Scale</a></h3>
      <p>Reconstructing data-deletion counterfactuals through deterministic, trace-preserving training replay. Experiments separate exact model-state reconstruction from behavioural forgetting.</p>
      <p><a href="https://github.com/abdullah-x-bd/unlearning">Code &amp; results ↗</a> · <a href="https://arxiv.org/abs/2508.12220">Preprint ↗</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub>03 / MULTI-AGENT SAFETY</sub>
      <h3><a href="https://github.com/abdullah-x-bd/polis">POLIS</a></h3>
      <p>An experimental testbed for algorithmic institutions. Studies how delegated authority, executable guards, provenance and shared-resource rules change agent outcomes.</p>
      <p><a href="https://github.com/abdullah-x-bd/polis">Code &amp; evidence ↗</a> · <a href="https://arxiv.org/abs/2608.09828">Preprint ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <sub>04 / AGENT EVALUATION</sub>
      <h3><a href="https://github.com/abdullah-x-bd/SafeguardShift">SafeguardShift</a></h3>
      <p>Evaluates agent behaviour when verification, review, monitoring, authority or other institutional safeguards are removed. Separates what agents attempt from what environments permit.</p>
      <p><a href="https://github.com/abdullah-x-bd/SafeguardShift">Benchmark &amp; findings ↗</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub>05 / RELIABLE ML SYSTEMS</sub>
      <h3><a href="https://github.com/abdullah-x-bd/PipelineProof">PipelineProof</a></h3>
      <p>An execution-based benchmark for detecting and repairing silent failures in ML pipelines, from leakage to incorrect evaluation, with held-back verification.</p>
      <p><a href="https://github.com/abdullah-x-bd/PipelineProof">Benchmark &amp; verifier ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <sub>06 / AI &amp; SOCIAL MEASUREMENT</sub>
      <h3><a href="https://github.com/abdullah-x-bd/LLM_Persona">Synthetic Individuals, Synthetic Populations</a></h3>
      <p>Tests whether improvements in LLM-based individual simulation translate into better population estimates. Individual accuracy and population fidelity need not move together.</p>
      <p><a href="https://github.com/abdullah-x-bd/LLM_Persona">Study &amp; analysis ↗</a></p>
    </td>
  </tr>
</table>

**Other applied systems** &nbsp; [OpenVQ](https://github.com/abdullah-x-bd/openvq), an interpretable speech-quality research engine · [ICR-OPT](https://github.com/abdullah-x-bd/icr-sim), a geospatial and economic model of mobile network sharing.

<br/>

### Selected preprints

| Year | Manuscript | Links |
| :--- | :--- | :--- |
| 2026 | **Markovian Circuit Tracing for Transformer State Dynamics** | [arXiv](https://arxiv.org/abs/2605.20824) · [Artifact](https://github.com/abdullah-x-bd/markovian-circuit-tracing) |
| 2026 | **Multi-Agent AI Safety as an Institutional Design Problem** | [arXiv](https://arxiv.org/abs/2608.09828) · [Artifact](https://github.com/abdullah-x-bd/polis) |
| 2025 | **Unlearning at Scale: Implementing the Right to be Forgotten in Large Language Models** | [arXiv](https://arxiv.org/abs/2508.12220) · [Artifact](https://github.com/abdullah-x-bd/unlearning) |

<sub>These are research preprints. Repository documentation records the methods, results and limits of the corresponding experimental artifacts.</sub>

<br/>

### Research practice

**Ground truth when possible. Counterfactuals when useful. Negative results when warranted.**

I aim to make evaluation protocols, code, assumptions and claim boundaries inspectable. Several repositories deliberately retain failed controls and limitations alongside positive findings.

---

<p align="center">
  <sub>NEW DELHI, INDIA &nbsp;·&nbsp; AI SAFETY RESEARCH &nbsp;·&nbsp; <a href="https://www.projectawareai.org/">PROJECT AWARE</a></sub>
</p>

---
title: "Research"
permalink: /research/
layout: single
toc: true
toc_label: "Research Areas"
toc_icon: "book"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/research-banner.png
excerpt: "Our methodologies and key findings in narrative dynamics research"
---

# Narrative Dynamics Research

## Theoretical Framework

Our research builds on decades of work in cognitive science, social psychology, and network science to develop new models of how narratives propagate through social networks. We conceptualize narratives as networks of causally connected elements, where the strength of these causal connections influences how readily people incorporate new information.

## Experimental Approach

To test our theories, we've designed innovative experimental paradigms that allow us to observe narrative diffusion in controlled settings:

- Participants are arranged in social network structures (typically lattice networks of ~30 individuals)
- Each person initially receives fragments of a larger narrative (2 out of 13 total story elements)
- Participants can share story elements with network neighbors
- We incentivize participants to adopt elements that fit coherently with their existing narrative understanding

This approach allows us to track precisely how narrative elements spread, which elements are adopted more readily, and how social structures interact with narrative coherence to shape diffusion patterns.

## Mathematical Modeling

A key contribution of our work is the development of formal models that quantify narrative influence. Our current model represents the narrative influence of a new element (n<sub>a</sub>) on an agent with existing narrative elements N<sub>i,t</sub> as:

$$\nu_i(n_a, t) = \sum_{n_b \in N_{i,t}} \frac{1}{d(n_a, n_b)^\phi}$$

Where:
- N<sub>i,t</sub> is the set of narrative elements already adopted by the agent
- d(n<sub>a</sub>, n<sub>b</sub>) is the shortest path length in the causal graph connecting narrative elements
- φ is a parameter determining how rapidly influence decays with distance

This model allows us to predict which narrative elements are more likely to be adopted based on their causal relationships to existing knowledge.

## Key Findings

Our research has revealed several important insights:

1. **Narrative structure strongly influences adoption patterns** - People are significantly more likely to adopt information that connects causally to their existing narrative understanding.

2. **Individual differences in adoption strategies** - We've identified distinct patterns in how people approach new information, with some individuals being more aggressive adopters than others.

3. **Complex interactions between social proof and narrative coherence** - For some individuals, social signals (how many neighbors have adopted an element) can counterintuitively decrease adoption likelihood for narrative elements that are difficult to integrate.

4. **Time-dependent adoption patterns** - The propensity to adopt new narrative elements follows predictable temporal patterns, with relevance decaying over time.

Our ongoing work continues to refine these models and explore their implications for broader information ecosystems.

## Applications

Understanding narrative dynamics has implications for numerous domains:

- **Public health communication** - Designing more effective ways to communicate complex health information
- **Science communication** - Improving how scientific findings are shared with broader audiences
- **Community resilience** - Helping communities develop shared understanding during crises
- **Digital media literacy** - Developing tools to help people navigate complex information landscapes

---

[Explore our publications](/publications/){: .btn .btn--primary} [Learn about our data & resources](/resources/){: .btn .btn--info}

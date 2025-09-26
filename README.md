# How to Generate False Detections of Group Polarization: Participant 
**Tech Thursday Tutorial Repository** • September 25, 2025

This repository accompanies the **Tech Thursday** tutorial:
**“How to Generate False Detections of Group Polarization.”**  

We focus on a single case study: the influential Schkade, Sunstein & Hastie (2010) experiment, and demonstrate how basic statistical fragilities can produce results that appear to confirm group polarization—even when no actual opinion change occurs.

---

## 🌍 Purpose

This tutorial introduces a simple adversarial simulation framework for social science. We show how to:

- Simulate the the Schkade et al. experimental design.
- Simulate "simple consensus" in latent opinions, where the mean group opinion does not change, only the opinion variance.
- Show how standard statistical practices can make simple consensus look like  **false positive detections** of group polarization.

We call this formal approach **Δo modeling**—focusing on directional opinion change, not just surface-level outcomes. These simulations offer a scalable, transparent way to test the reliability of published inferences.

---

## 💻 How to use

1. Clone this repository or [download the .zip file](https://github.com/SocSci-for-Sustainability/tech-thursday-2025-09-25/archive/refs/heads/main.zip).
2. Open `notebooks/simulation_walkthrough.qmd` in RStudio.
3. Run through the notebook to:
   - Load the original data.
   - Generate no-change counterfactuals.
   - Evaluate how often the original test design falsely detects polarization.
4. Modify parameters to design your own adversarial simulations.

---

## 📦 What's in this repo?

- `data/schkade_raw.csv` — digitized data from Schkade et al. (2010)  
- `R/model.R` — adversarial simulation model in R  
- `R/helpers.R` — helper functions for sampling, reshaping, and plotting  
- `notebooks/simulation_walkthrough.qmd` — Quarto tutorial notebook walking through key results  
- `figures/` — output figures from simulation runs  
- `results/` — results from main parameter sweeps (false positive rates across design variants)

---

## 🧠 Why this matters

Group polarization research has shaped how policymakers think about deliberation, extremism, and institutional resilience. But what if the foundational results were statistical mirages?

By publishing only positive findings, the field has overfit to a fragile signal. This tutorial demonstrates how easily **false detections** can arise when sample sizes are small, variance is unmodeled, and null results are discarded.

> If we can't reliably detect whether opinions have shifted, we can't build effective, evidence-based policy to mitigate polarization.

This isn't just about one experiment—it’s about building the next phase of social science:  
**Rigorous. Replicable. Useful.**

---

## 👉 Who this is for 👩🏽‍🔬🧑🏻‍💻🧕🏿👨🏼‍🏫👨🏾‍🔬🧑🏿‍💻 🇺🇳

This tutorial is built for:

- Students learning how to model social influence using real data.  
- Researchers interested in replicability and publication bias.  
- Scientists designing more robust, transparent experimental frameworks.  
- Anyone suspicious of easy conclusions drawn from ambiguous opinion data.


---

## 📬 Stay connected

**Tech Thursday** is a weekly series unpacking the technical, theoretical, and political underpinnings of social change modeling.

Subscribe to **Social Science for Sustainability by Matt Turner:**
- [Substack](https://matphd.substack.com)
- [Spotify](https://open.spotify.com/show/5qOFsK1ilbOnTA719uKacr?si=yNC3_eQWSYy3yz9g199ZDg)
- Matt on Instagram: [@matthewadamturnerphd](https://www.instagram.com/matthewadamturnerphd?igsh=ZGUzMzM3NWJiOQ==&utm_source=ig_contact_invite)

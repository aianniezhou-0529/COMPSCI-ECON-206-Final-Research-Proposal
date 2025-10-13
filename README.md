# COMPSCI-ECON-206-Final-Research-Proposal
# Quota-Plus: A Computational Voting Mechanism for Fair Refugee Allocation

**Abstract**  
This project explores how computational mechanism design can improve fairness, efficiency, and legitimacy in collective decision-making.  
Building upon insights from **Problem Set 1** (strategic reasoning in game theory), **Problem Set 2** (mechanism design for institutional coordination), and the **Week 6 Reflection** (Arrow’s impossibility theorem and social choice), this proposal introduces **Quota-Plus** — a hybrid system for refugee allocation in the European Union.  
Quota-Plus integrates algorithmic quota computation, flexible compliance options, and transparent monitoring to align incentives with the **Sustainable Development Goals (SDG 10, 16, 17)**.  


---

## Authors
- **Ai Zhou** — Duke Kunshan University, COMPSCI/ECON 206 Final Proposal
- **Economist**  
  Developed the *theoretical foundations* of strategic interaction and welfare analysis.  
  Applied **game theory** frameworks from **Osborne & Rubinstein (1994)** and **Shoham & Leyton-Brown (2009)** to formalize equilibrium concepts such as **Nash** and **Subgame Perfect Nash Equilibrium (SPNE)**.  
  Evaluated fairness and efficiency using **Arrow’s Impossibility Theorem (1972)** and **Buchanan’s constitutional economics (1986)** to connect equilibrium outcomes with normative institutional design.

- **Computational Scientist**  
  Implemented and visualized models using **NashPy**, **Game Theory Explorer (Savani & von Stengel, 2015)**, and **oTree (Chen, Schonger & Wickens, 2016)**.  
  Leveraged **algorithmic game theory** and **computational equilibrium analysis** to test theoretical predictions.  
  Drew on insights from **QuantEcon** and **Knight (2021)** to ensure computational reproducibility and transparency in solving for Nash and SPNE equilibria.

- **Behavioral Scientist**  
  Designed and conducted behavioral experiments using **oTree** and **LLM-based agents (GPT-4)** to compare human and AI strategic reasoning.  
  Grounded in **Behavioral Game Theory (Camerer, 2003)** and **Social Preference Models (Fehr & Schmidt, 1999; Rabin, 1993)**, analyzing deviations from rational SPNE due to fairness, reciprocity, and bounded rationality.  
  Contributed to emerging discussions of **AI behavior as strategic agents (Horton, 2023; Bubeck et al., 2023)**.

- **Mechanism Designer**  
  Proposed the **Quota-Plus Hybrid Mechanism** inspired by **Hurwicz–Maskin–Myerson’s (2007)** Nobel framework in mechanism design.  
  Integrated **algorithmic allocation**, **incentive compatibility**, and **transparency mechanisms** to address EU refugee burden-sharing.  
  Built on **Kerschbamer, Sutter & Dulleck (2017)** to incorporate fairness and credibility into institutional reform.

---

---

## Disclaimer
This repository supports the final research proposal submitted to  
**COMPSCI/ECON 206: Computational Microeconomics** (Fall 2025, Prof. Luyao Zhang).  

---

## Acknowledgments
This project was made possible through the guidance, inspiration, and collaboration of many individuals and communities.  

First and foremost, I express my deepest gratitude to **Professor Luyao Zhang**, whose insightful lectures, mentorship, and encouragement shaped the direction and intellectual rigor of this project. Her interdisciplinary approach—combining **computational modeling, behavioral insights, and institutional design**—greatly influenced my understanding of how economic theory can inform real-world innovation.  

I am also sincerely thankful to **Professor Luyao Zhang** and **Peilin Wu**, whose constructive discussions and feedback throughout **Problem Sets 1 and 2** contributed immensely to refining my theoretical framework, coding practice, and presentation structure. Additionally, **Yihan Chen** and **Ji Wu** also helped a lot during the preparation of **Problem Set 1&2**. The spirit of teamwork in COMPSCI/ECON 206 fostered an environment of curiosity and mutual learning that I will carry forward in future research.  

Special appreciation is extended to the **open-source software communities**, whose transparent, collaborative ethos embodies the values of reproducible computational research:
- [**NashPy**](https://nashpy.readthedocs.io) — for enabling fast and accurate equilibrium computation.  
- [**Game Theory Explorer (GTE)**](http://www.gametheoryexplorer.org) — for providing intuitive tools for visualizing extensive-form games.  
- [**oTree**](https://otree.readthedocs.io) — for bridging theory and behavior through human and AI experimental frameworks.  
- [**Google Colab**](https://colab.research.google.com/) — for supporting reproducible, cloud-based Python experimentation and visualization.    

I am grateful for the advancements in **AI and Large Language Models (LLMs)** that made it possible to explore the intersection of human and artificial reasoning:
- [**OpenAI GPT-4**](https://openai.com/research/gpt-4) — for enabling comparative behavioral experiments that tested theoretical robustness under algorithmic decision-making.  

---

## Statement of Intellectual and Professional Growth
Across **Problem Set 1**, **Problem Set 2**, and this **Final Proposal**, I developed the ability to bridge **theoretical rigor**, **computational modeling**, and **behavioral insight**.  
From mastering **backward induction** and **SPNE** computation, to designing **AI-human experiments** and conceptualizing **institutional mechanisms**, this project enhanced both technical fluency and interdisciplinary reasoning. The field trip and classroom collaboration further deepened my awareness of how abstract economic theory can inform actionable, ethical, and transparent designs for collective decision-making in real-world contexts.

---
## Table of Contents

**Play-to-Innovate/**  
**economist/**  
trust_game_theory.md  
welfare_fairness_analysis.md  

**computational_scientist/**  
trust_game_nashpy.ipynb  
auction_llm_simulation.ipynb  

**behavioral_scientist/**  
otree_trust_simple zip/  
human_vs_llm_results.zip  

**mechanism_design/**  
quota_plus_design.md  
voting_simulation.ipynb  

**visualizations/**  
payoff_matrices.png  
equilibrium_diagrams.png  
voting_flowchart.pdf  

**docs/**  
Final Research Proposal.pdf  
Poster.pdf  
FieldTripReflection.md  

**README.md**


---
## Navigation Instructions
- **Equilibria Computation:** See `computational_scientist/` for NashPy, GTE & Colab results.  
- **Mechanism Design:** See `mechanism_design/` for Quota-Plus voting system.  
- **Behavioral Data:** See `behavioral_scientist/` for oTree and LLM transcripts.  
- **Visual Outputs:** All diagrams and charts in `visualizations/`.  
- **Documentation:** Full proposal, poster, and reflection in `docs/`.
  
---
## Embedded Media

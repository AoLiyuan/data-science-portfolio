# My Data Science Portfolio

*Last updated: October 2026*

## About Me

Hi, I'm a graduate student studying data science and computing. This
portfolio presents end-to-end data-science projects I have built, from
problem framing and data sourcing to modelling, visualization, and
reproducible documentation.

**Technical skills:** Python (pandas, NumPy, Matplotlib, NetworkX), Jupyter
Notebook, graph/network analysis, queuing simulation, scenario and
sensitivity analysis, Git, GitHub, and GitHub Pages.

---

## Featured Project

### Pinglu Canal River–Sea Intermodal Logistics Efficiency Analysis
*A simulation of port coordination and freight network reconfiguration*

**Research question.** The Pinglu Canal (opened 16 September 2026; 134.2 km;
5,000-tonne vessels) creates a southward river-to-sea route from Guangxi's
inland ports to Qinzhou Port on the Beibu Gulf. How much does the canal, and
how much do *operational* coordination measures (joint lock scheduling,
river–sea direct vessels, shared berths), improve logistics efficiency and
reconfigure the gateway network between Guangzhou and Qinzhou?

**What I did.** I built a directed freight network (waterway, canal, coastal
and ocean links) with NetworkX, assigned deterministic illustrative OD
flows using generalized-cost shortest paths, modelled the three locks and
port berths as M/M/c queues, and compared three scenarios: baseline (S0),
canal open (S1), and canal plus coordination (S2).

**Key finding.** The canal reduces weighted door-to-door logistics cost by
**23.5%** and the full coordination package by **27.7%**, reproducing the
officially reported 18–30% range. The inland leg from Nanning shortens by
about 536 km, and weighted betweenness centrality shifts sharply from
Guangzhou (0.337 → 0.026) to Qinzhou (0.005 → 0.447).

**Figure 1 — Freight network before and after the canal:**

![Figure 1 Network Map](https://raw.githubusercontent.com/AoLiyuan/data-science-project/main/fig1_network_maps.png)

**Figure 2 — Port throughput, berth utilization, lock queuing and hub
centrality:**

![Figure 2 OD Cost Distance](fig2_od_cost_distance.png)

**Figure 3 — Infrastructure versus coordination gains:**

![Figure 3 Port and Lock](fig3_port_and_lock.png)

**Project repository:**
https://github.com/AoLiyuan/data-science-project

**Current status:** Completed (future iteration: replace the synthetic OD
matrix with customs/port-authority data and move to a discrete-event
simulation).

---

## Projects

| Project | Repository | Status |
|---|---|---|
| Pinglu Canal River–Sea Intermodal Logistics Efficiency Analysis | [data-science-project](https://github.com/AoLiyuan/data-science-project) | Completed |

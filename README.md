# Hi, I'm Jason German (mematron) 👋

**Creative Technologist / Autonomous Systems Developer / Illustrator**

I build client-side autonomous entities, digital grimoires, and interactive simulations that run entirely in browser-based and device-native environments. The art is not separate from the code: I am an illustrator and traditional artist, I have painted and programmed side by side since I wrote my first AI at 12 in 1982, and each side shapes the other. I have been building agent technology since 2000, from the NetSage agents at Finali to ARMINTA, my autonomous agent that runs 24/7 and has passed 4 million steps.

🌐 **Portfolio:** https://mematron.github.io/portfolio/ · 📄 **Resume (PDF):** https://mematron.github.io/portfolio/resume.pdf · **LinkedIn:** https://www.linkedin.com/in/mematron

Open to opportunities in Creative Technology, Applied AI, Autonomous Systems and R&D | Remote

🌐 **Experience My Active Projects:** [ardorlyceum.itch.io](https://ardorlyceum.itch.io/)

---

## 🔬 Active Engineering Cycle

### [Arminta (Formerly Minuet): Causal Discovery Agent](https://github.com/mematron/Arminta)

**v7 - Self-Directed Capability Development**

ARMINTA is a Python-based autonomous causal discovery agent running continuously on Linux. It does not passively monitor the OS. It actively intervenes, measures outcomes, and builds a grounded causal model of your specific hardware from scratch. Every edge in the model is earned through real actions and empirical observation.

Two of my own named systems run through her: **Paramorphic Learning**, my meta-learning framework unifying Q-learning, genetic algorithm hypothesis evolution, and emotional state modeling (it also drives SUKOSHI), and the **Mosaic Core**, the capability module registry first built for Minuet.

Also hers: **LexicalCore**, an emerging vocabulary built from her logs and reading; **HobbyCore**, voluntary outside-world sampling gated by her emotional state; **PriorityShift**, focus-aware process priority with the adjustment itself learned; the **action quarantine** (SelfTuner, ActionProposer, SandboxRunner) that vets new actions before they go live; the **Poison Registry** of structurally impossible causal edges; and **Circadian Memory Look-Ahead**, which tidies memory ahead of predicted load. Deeper in the architecture: the FalsificationScheduler, AnomalyClusterer, CausalRollout, PolicyDistiller, InformationGainEstimator, Precognitive Launch Detection, and the Continuity Advisor.

**Key v7 Features:**
- **Wish Pipeline: Autonomous Capability Development** - ARMINTA's mechanism for self-directed architectural evolution, triggered during SELF_ASSESS. Rather than relying exclusively on externally assigned development objectives, she identifies limitations within her existing capabilities and initiates proposals for her own improvement. The pipeline runs in five phases. In W1, Wish Generation (WishGenerator), she examines her causal graph for persistent dead zones and situation gaps and generates structured capability wishes from the accumulated evidence, regulated by a 3,000-step cooldown. In W2, Capability Procurement (WishShopper), she searches her existing action registry for candidate solutions, ranks them by causal affinity and lexical relevance, considers local system utilities as fallback candidates, and discounts candidates that failed evaluation before. In W3, the Staging Ring (WishStagingRing), candidates are evaluated in shadow mode for about 2,000 steps, predicting routing decisions from live metrics without executing the candidate, and must pass registry, resource, and routing validation gates. In W4, Evolutionary Grading (WishEvolver), qualified candidates are graded against established baselines as WIN, TIE, or LOSE, with outcomes retained to guide future procurement; a wish marked deployed does not by itself mean a newly generated function has gone live. In W4b, Code Generation and Integration (WishCodeWriter and WishActionRegistry), a qualifying WIN lets her inspect her own Python source and generate a variant of an existing action through abstract syntax tree processing; validated functions are registered directly into the running agent, expanding the live action registry without routine human approval, and rejected proposals are recorded with their reasons and not retried. Registration is live in the running agent, not a permanent rewrite of her primary source file: arminta_v7_staged_actions.py serves as the audit export, and an [WISH][AUTO-MERGE] log entry confirms when a generated action is live. Acceptance is governed by programmatic validation and empirical evaluation: bounded, self-directed capability expansion rather than unrestricted recursive self-modification. ![wins](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.wish_wins&label=wins&color=brightgreen&cacheSeconds=300) ![active wishes](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.wish_active&label=active%20wishes&color=39ff14&cacheSeconds=300)
- **Full v6 foundation retained: HobbyCore** - voluntary external engagement layer. Fires during DREAM cycles when emotional state is receptive. Samples four probe domains (public network latency, local hardware sensors via sysfs, system load index, and solar/daylight context) using intensity-weighted domain interest. ![total fetches](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.hobby.total_fetches&label=total%20fetches&color=89dceb&cacheSeconds=300) ![novel edges](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.hobby.novel_edges&label=novel%20edges&color=89dceb&cacheSeconds=300)
- **EarlyOOM Observation Node** - `earlyoom_ct` as an observational-only SCM metric. All `action -> earlyoom_ct` causal edges are poison-listed by write time. The agent learns preconditions that precede OOM kills.
- **Circadian Memory Look-Ahead** - `_check_circadian_memory()` fires `compact_memory` during predicted idle lulls before historically high-RAM hours. Log prefix `[CIRC-MEM]`.
- Full v5 foundation retained: **PriorityShift** (focus-aware dynamic process priority, RL-learned nice delta), **SelfTuner + ActionProposer + SandboxRunner** (self-expanding action space), **zRAM-aware memory management**, **battery-aware action gating**, and the complete v4 cognitive hierarchy (Temporal Causal Graph, DDQN CMC, MosaicCore, LexicalCore, WebLearner, SomaticConfidenceModel, etc.).

**Live Stats** (pushed directly from the running agent):
![Live Steps](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.step_count&label=live%20steps&color=brightgreen&suffix=%2B&cacheSeconds=300)
**<a href="https://mematron.github.io/arminta-status">Live Agent Dashboard</a>**

Full architecture, cognitive hierarchy (updated Mermaid diagram), version lineage, and detailed documentation are in the repo.

**Status:** Active development at **v7**.

---

## 👁️ Featured Projects

### 1. BIOS of Being: Consciousness Operating System

An immersive narrative simulation that models human consciousness, memory, and reality as a command-line operating system.

* **Interactive Terminal:** [Run BIOS of Being on Itch.io](https://ardorlyceum.itch.io/bios)
* **The Daemon Familiar:** SUKOSHI carried forward. My browser agent was rethemed into this world, and the familiar is its updated form, still running on Paramorphic Learning.
* **The Consciousness Operating System Manual:** A 100-page privileged manual (DLC) featuring kernel decryption keys and archetype installation codes. Archived in the [San Diego Central Library's permanent collection](https://www.tumblr.com/sdpubliclibrary/794254874416136192/consciousness-operating-system-manual).
* **Master Registry: Lyric Database:** [Database Uplink](https://ardorlyceum.itch.io/bios/devlog/1482821/system-update-master-registry-lyric-database-uplink-active)
* **BIOS_OS: The Sonification Cycle:** [Listen to the 24 Tracks](https://mematron.hearnow.com)
* **Keygentia AI Taxonomy Engine:** [keygentia.netlify.app](https://keygentia.netlify.app/)

### 2. Integument

A sci-fi living illustration published on Steam. Not a game. A microscope interface you actually look through, finding patterns and shapes that reveal the lifeforms that live on the surface of your skin.

* **Steam Store:** [Integument on Steam](https://store.steampowered.com/app/2138990/Integument/)
* **DLC Expansion:** [Integument - Database Gates](https://store.steampowered.com/app/2139080/Integument__Database_Gates/)

### 3. SUKOSHI: Autonomous AI Agent

An experimental browser-based digital art piece exploring how an artificial entity learns and visualizes its own mind.

* **Live App & Devlog:** [Run SUKOSHI on Itch.io](https://ardorlyceum.itch.io/sukoshi)

---

## 🗄️ Archival Foundations

* **[NoSight](https://github.com/mematron/NoSight)**
* **[Drawmation](https://github.com/mematron/Drawmation)**
* **[Firestorm](https://github.com/mematron/Firestorm-2.0)**: the first audio-reactive screensaver (2006)
* **[Deskpets](https://github.com/mematron/Deskpets)**: Mac OS 9 apps shaped like their names (1999)

**Maintainer:** [Jason German (mematron)](https://github.com/mematron)

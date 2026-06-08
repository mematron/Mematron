# Hi, I'm Jason German (mematron) 👋

**Software Developer, Digital Artist, and Builder of Things That Learn**

I build client-side autonomous entities, digital grimoires, and interactive simulations that run entirely in browser-based and device-native environments.

🌐 **Experience My Active Projects:** [ardorlyceum.itch.io](https://ardorlyceum.itch.io/)

---

## 👁️ Featured Projects

### 1. BIOS of Being: Consciousness Operating System

An immersive narrative simulation that models human consciousness, memory, and reality as a command-line operating system.

* **Interactive Terminal:** [Run BIOS of Being on Itch.io](https://ardorlyceum.itch.io/bios)
* **The Consciousness Operating System Manual:** A 100-page privileged manual (DLC) featuring kernel decryption keys and archetype installation codes. Archived in the San Diego Central Library's permanent collection.
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

## 🔬 Active Engineering Cycle

### [Arminta (Formerly Minuet): Causal Discovery Agent](https://github.com/mematron/Arminta)

**v6 - External Actor Integration & Predictive Memory Management**

ARMINTA is a Python-based autonomous causal discovery agent running continuously on Linux. It does not passively monitor the OS. It actively intervenes, measures outcomes, and builds a grounded causal model of your specific hardware from scratch. Every edge in the model is earned through real actions and empirical observation.

**Key v6 Features:**
- **HobbyCore** - voluntary external engagement layer. Fires during DREAM cycles when emotional state is receptive. Samples four probe domains (public network latency, local hardware sensors via sysfs, system load index, and solar/daylight context) using intensity-weighted domain interest. External observations are correlated against internal system metrics and injected into the causal graph as observable (non-interventional) edges. Domain symbols seed into LexicalCore. Blocked entirely when stressed or apprehensive.
- **EarlyOOM Observation Node** - `earlyoom_ct` added as an observational-only SCM metric: a per-step count of processes killed by the `earlyoom` daemon, parsed from `journalctl`. All `action -> earlyoom_ct` causal edges are poison-listed at write time. The agent learns system preconditions that precede OOM kills and can act before the next one fires.
- **Circadian Memory Look-Ahead** - `_check_circadian_memory()` mirrors the existing CPU governor look-ahead: if the MosaicCore circadian log predicts a high-RAM hour arriving soon, ARMINTA fires `compact_memory` during the current idle lull. Gate conditions enforce safety (history depth, meaningful predicted rise, no zswap, 20-minute cooldown). Log prefix `[CIRC-MEM]`.
- Full v5 foundation retained: **PriorityShift** (focus-aware dynamic process priority, RL-learned nice delta), **SelfTuner + ActionProposer + SandboxRunner** (self-expanding action space), **zRAM-aware memory management**, **battery-aware action gating**, and the complete v4 cognitive hierarchy (Temporal Causal Graph, DDQN CMC, MosaicCore, LexicalCore, WebLearner, SomaticConfidenceModel, etc.).

**Live Stats** (pushed directly from the running agent):
![Live Steps](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.step_count&label=live%20steps&color=brightgreen&suffix=%2B&cacheSeconds=300)
**<a href="https://mematron.github.io/arminta-status">Live Agent Dashboard</a>**

Full architecture, cognitive hierarchy (updated Mermaid diagram), version lineage, and detailed documentation are in the repo.

**Status:** Active development at **v6**.

---

## 🗄️ Archival Foundations

* **[NoSight](https://github.com/mematron/NoSight)**
* **[Drawmation](https://github.com/mematron/Drawmation)**

**Maintainer:** [Jason German (mematron)](https://github.com/mematron)

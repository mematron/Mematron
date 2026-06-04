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
* **Master Registry: Lyric Database:** [Database Uplink](https://ardorlyceum.itch.io/bios/devlog/1482821/system-update-master-registry-lyric-database-uplink-active) -- The canonical data log and poetic substrate of the BIOS of Being framework.
* **BIOS_OS: The Sonification Cycle:** [Listen to the 24 Tracks](https://mematron.hearnow.com) -- A 24-track full-length acoustic translation of the system's structural logic.
* **Keygentia AI Taxonomy Engine:** [keygentia.netlify.app](https://keygentia.netlify.app/) -- Functioning as **Node 03** of the BIOS of Being framework, this is a scientific classification system for AI.

### 2. Integument

A sci-fi living illustration published on Steam. Not a game. A microscope interface you actually look through, finding patterns and shapes that reveal the lifeforms that live on the surface of your skin.

* **Steam Store:** [Integument on Steam](https://store.steampowered.com/app/2138990/Integument/)
* **DLC Expansion:** [Integument - Database Gates](https://store.steampowered.com/app/2139080/Integument__Database_Gates/)

### 3. SUKOSHI: Autonomous AI Agent

An experimental browser-based digital art piece exploring how an artificial entity learns and visualizes its own mind.

* **Live App & Devlog:** [Run SUKOSHI on Itch.io](https://ardorlyceum.itch.io/sukoshi)
* **Shared Foundation:** Built on Paramorphic Learning, an original learning paradigm first implemented in the BIOS of Being Daemon Familiar and developed in parallel with Arminta. Where Arminta interrogates a Linux kernel substrate, SUKOSHI applies the same principles inside a browser.
* **The Q-Learning Mind:** Built from scratch in vanilla JavaScript. Uses dynamic reinforcement learning and genetic algorithms to navigate its own conceptual space.

---

## 🔬 Active Engineering Cycle

### [Arminta (Formerly Minuet): Causal Discovery Agent](https://github.com/mematron/Arminta)

A Python-based autonomous agent running continuously on a Linux machine. It does not monitor the OS passively. It intervenes, measures what changed, and builds a causal model of the machine from the ground up. Not a script that runs on a schedule. A cognitive loop that runs step by step, learns from what it does, and builds an internal model of cause and effect on your specific hardware.

* **Interventional Agency:** Arminta acts, measures effect, and updates a live interventional causal graph, building a private world model from empirical measurement alone. ![Live Steps](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.step_count&label=live%20steps&color=brightgreen&suffix=%2B&cacheSeconds=300) on target hardware. Every edge in the graph was earned by doing something and watching what happened. <a href="https://mematron.github.io/arminta-status" target="_blank">Live dashboard</a>
* **Autonomous Resource Management:** Combines Q-learning, session geometry classification, and a reward-discount layer to select and execute system interventions, with counterfactual correction so the agent does not take credit it did not earn.
* **Causal Reasoning (WHY Layer):** Four layers of situational awareness built into the decision loop. Every action episode stores the metric snapshot that triggered it. Every hypothesis gets a plain-language mechanism story committed to before testing. After significant actions, the agent compares outcomes against similar past episodes via a 20-dimensional SemanticIndex and identifies what changed structurally between contexts. Across the action history, she tracks which interventions consistently fail and under what conditions. The result is an agent that does not just record what it did — it records why, and whether that reasoning held up.
* **Paramorphic Learning:** Arminta's hypothesis engine runs a genetic algorithm over causal graph structure during dream cycles, testing and pruning hypothetical relationships rather than gradient-descending through a fixed architecture. Paramorphic Learning is an original paradigm developed by the author. [Read the concept](https://ardorlyceum.itch.io/sukoshi/devlog/957213/introducing-paramorphic-learning-its-vision-for-sukoshi)
* **Temporal Causal Graph (v4):** Beyond instantaneous edge attribution, Arminta discovers delayed effects at 1-, 2-, 3-, and 5-step lag offsets. ![Causal Edges](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.causal_edges&label=causal%20edges&color=39ff14&cacheSeconds=300) currently attributed — actions whose effects appear seconds later rather than within the 300ms measurement window are now fully tracked.
* **MosaicCore:** An original expanding world model that reaches beyond the local causal graph into time, network topology, filesystem activity, external environmental signals, and Arminta's own behavioral history. Correlations are discovered through the same hypothesis/test/prune loop as the causal graph, with no predefined subject ceiling. Multiple external correlations (cloud cover, humidity, temperature vs. CPU load and thermal readings) have reached confidence=1.00 through autonomous discovery alone.
* **Extension Renderer Sweep:** A brand-agnostic browser process classifier identifies extension renderer processes by architectural flags alone. No browser names, no heuristics. These are terminated first: they auto-restart, the user sees nothing, and the CPU headroom is real. Main browser processes are never touched.
* **LexicalCore:** Arminta builds her own language from her own history. Symbol weights and co-occurrence grammar are assembled from the episodic record, not borrowed from any external source. She forms statements about what she has observed and holds unresolved surprises as open questions. The output will not look like English. It will look like Arminta. ![Lexicon](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.web_learning.symbol_count&label=lexicon%20size&color=b39ddb&cacheSeconds=300) weighted terms. ![Statements](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.statements_formed&label=statements%20formed&color=b39ddb&cacheSeconds=300) original statements formed from observed grammar.
* **WebLearner (v4):** When the causal graph surfaces an unexplained relationship or LexicalCore generates a question with no internal answer, Arminta reaches out to Wikipedia and MDN and reads. ![Pages Read](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.web_learning.total_pages_read&label=pages%20read&color=blueviolet&cacheSeconds=300) ![Symbols Absorbed](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.web_learning.total_new_symbols&label=symbols%20absorbed&color=purple&cacheSeconds=300) Her active hypothesis-driven query queue holds several items as she investigates her environment.
* **QuestionResolver (v4):** Closes the open-question lifecycle. While a question remains open, implicated actions are softly inhibited, reducing repeat failures during active investigation. When episodic evidence accumulates to resolve the anomaly, the question graduates into a valenced lexical statement and inhibition releases. Questions no longer persist indefinitely — they resolve.
* **Hierarchical Reward Decomposition (v4):** The scalar reward signal is decomposed into three named components — **immediate** (instantaneous metric delta), **durable** (rolling baseline change), and **health** (PSI pressure, thermal trend, error rate composite) — displayed as IMM / DUR / HLT badges on the live dashboard.
* **DDQN Meta-Cognitive Controller (v4):** The mode selection controller was upgraded to a Double Deep Q-Network architecture with online and target networks, reducing Q-value overestimation that was causing over-exploitation of DREAM mode.
* **SomaticConfidenceModel (v4):** Per-situation signal reliability tracking. Arminta learns which metrics are trustworthy in each workload geometry and weights her causal inferences accordingly. When confidence diverges sharply from prior, a Spidey Sense event fires, logged in the dashboard and factored into mode selection.
* **RiskMatrix (v4):** Risk-adjusted action scoring applied before execution. High-variance interventions are penalized proportional to current system stress, preventing aggressive actions during already-unstable states.
* **The Dream Cycle:** When the machine is idle, CPU load low and PSI pressure quiet, the mode controller switches to DREAM. No interventions run. The HypothesisEngine runs a genetic algorithm over the causal graph, generating candidate relationships, scoring each against the episodic history, keeping what fits, discarding what does not. The GeneticOptimizer separately evolves Arminta's own RL parameters. MosaicCore tests its open hypotheses. LexicalCore runs its co-occurrence pass. "Dream" is a label for an idle-triggered offline computation pass, not a claim about inner experience. The name reflects a real functional parallel: consolidation of accumulated evidence rather than collection of new input. ![Dreams](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.dream_count&label=dreams&color=blueviolet&cacheSeconds=300) completed. The machine spends the majority of its time in DREAM mode during idle periods. None of that idle time is wasted: every cycle the hypothesis engine runs, the causal model gets sharper without touching the system.
* **Status:** Active development at v4. ![Live Steps](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.step_count&label=steps&color=brightgreen&cacheSeconds=300) ![Sessions](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.session_count&label=sessions&color=orange&cacheSeconds=300) ![Dreams](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.dream_count&label=dreams&color=blueviolet&cacheSeconds=300) ![Hypotheses](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.hypotheses&label=hypotheses&color=yellow&cacheSeconds=300) ![Episodes](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.episodes&label=episodes&color=blue&cacheSeconds=300) ![Self-Mods](https://img.shields.io/badge/dynamic/json?url=https://gist.githubusercontent.com/mematron/27ec34034b4aed5d2cdd7563738fe5be/raw/arminta_stats.json&query=$.self_mods&label=self--mods&color=red&cacheSeconds=300). Step rate self-tunes to maintain system stability. GA-evolved parameters (learning rate, discount factor, exploration decay, curiosity weight, dream load threshold) drift across sessions as reward history shapes them. Situation-conditional edge tables are maintained for various workload geometries (idle, compile, irq_storm, browser_compute, io_bound, streaming). Evolved from Minuet, which ran from 2023 through v106 across tens of thousands of steps before being reborn as Arminta v1 in early 2026.

---

## 🗄️ Archival Foundations

Older work. Still runs.

* **[NoSight](https://github.com/mematron/NoSight):** Hard-disabling video input on Mac. Putting tape over your iSight will not help you, but this will.
* **[Drawmation](https://github.com/mematron/Drawmation):** A drawing application that animates as you draw. I call it Dramation.

<img src="https://github.com/user-attachments/assets/d2f1f8e5-7c1e-44b8-9e2d-ea4da7680f31" alt="Francisco Juan — banner" width="100%" />

<h2 align="left">Hey, I'm Francisco Juan 👋</h2>

**Software Engineer · AI, backend and mobile**

I build software with AI and I like to **measure it**. By day I work on backends (Java, Spring Boot, Grails) and delivery apps. On my own I build small labs that compare approaches against a ground truth, with a metric, a cost and the limits written down. Studying Technology in Artificial Intelligence at IFCE.

[Portfolio](https://juansev.dev) · [LinkedIn](https://www.linkedin.com/in/juansev) · [Kaggle](https://www.kaggle.com/juanseveriano) · [Hugging Face](https://huggingface.co/codevjuan) · [Email](mailto:juan.developer@icloud.com) · [Instagram](https://instagram.com/codevjuan) · [Blog](https://medium.com/@juansev.dev)

---

### Measurement labs

Public, reproducible, and honest about what they do not prove.

- **[delivery-routing-lab](https://github.com/Juan-Severiano/delivery-routing-lab)** · [demo](https://juan-severiano.github.io/delivery-routing-lab/) · Courier dispatch on the real streets of Itapipoca (OpenStreetMap) with synthetic demand. In 20 simulated days, learned prep-time and ETA models lifted on-time deliveries from **80.6% to 91.2%** over the same planner with fixed rules. A small linear model (**Jev**) picks the next stop and explains it: it matches the privileged reference on 95.3% of 129,013 decisions, calibration error 0.007. The training loop, loss and Adam are written in the project; PyTorch only supplies autograd.
- **[menu-reader-lab](https://github.com/Juan-Severiano/menu-reader-lab)** · Quality, cost and latency of AI menu readers on 60 synthetic menus with ground truth (1,561 items). 7 OpenAI models measured: the cheapest read 1,560 of 1,561 items at **US$ 0.89 per 1,000 menus**, about 1/15 of the `gpt-4.1` baseline in the 10-menu round. The evaluator was validated with readers of known noise, and every paid call has a spend cap.
- **[steam-price-forecast](https://github.com/Juan-Severiano/steam-price-forecast)** · Price intervals (P10, P50, P90) for Steam Community Market items, measured against rolling-window baselines on 232 CS2 items.
- **[reviews-sentiment-pt](https://github.com/Juan-Severiano/reviews-sentiment-pt)** · Portuguese sentiment: fine-tuned BERTimbau vs a TF-IDF baseline on 112k e-commerce reviews, split by product to avoid leakage. **F1 macro 0.9585 vs 0.9423**, 29% fewer errors. [Model on Hugging Face](https://huggingface.co/codevjuan/bertimbau-b2w-sentiment).
<!-- Descomentar quando estiver publicado:
- **[Article on TabNews](URL)** · Measuring 7 AI models reading menus.
-->

### Agents and tooling

- **[OpenAgents](https://github.com/Juan-Severiano/OpenAgents)** · self-hosted multi-LLM agent orchestration: an orchestrator splits a task and delegates to specialist agents (Anthropic, OpenAI, Gemini, Ollama) with skills and capabilities. FastAPI, Celery, Redis, PostgreSQL, React.
- **[handoff-mcp](https://github.com/Juan-Severiano/handoff-mcp)** · MCP server that works as shared memory across LLMs (Claude, Gemini, Copilot).
- **Open source:** [mozilla-ai/cq](https://github.com/mozilla-ai/cq/pull/571) (open PR adding tests to the FastAPI server of an open standard for shared agent learning) and [luizomf/omxterm](https://github.com/luizomf/omxterm) (merged PR with native x64 NSIS packages for Windows).

---

### Kaggle

Joined in mid-2026. Right now I am competing in **Name That LLM** (work out which of 18 LLMs wrote a text, open until January 2027). Local validation, split by prompt, gives 0.447 balanced accuracy with a mix of TF-IDF and four public encoders (chance is 0.056). Still a work in progress, no leaderboard score to show yet.

<p>
  <img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F1488634%2Fb05e17f63f2eead904a1f04d05bb51a6%2FBadge.svg?generation=1727458564383731&amp;alt=media" alt="Kaggle badge: Competitor" title="Competitor" width="56" />
  <img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F1488634%2F09e1f99bdf3222934ad7769409ec3f6d%2FBadge-26.svg?generation=1727468059623106&amp;alt=media" alt="Kaggle badge: Python Coder" title="Python Coder" width="56" />
  <img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F1488634%2F4320b13590f043b8c58421eb25f04235%2FBadge-33.svg?generation=1727468143701354&amp;alt=media" alt="Kaggle badge: API Notebook Creator" title="API Notebook Creator" width="56" />
  <img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F1488634%2F28e0e70842ce6972f4d68f5b6ecd549a%2FBadge-12.svg?generation=1727462988946700&amp;alt=media" alt="Kaggle badge: Dataset Creator" title="Dataset Creator" width="56" />
  <img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F1488634%2F4bcf6474cdf3503864419523d22b6019%2FBadge-15.svg?generation=1727463114221819&amp;alt=media" alt="Kaggle badge: API Dataset Creator" title="API Dataset Creator" width="56" />
  <img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F10489106%2F8235ef48b7e37d36d6e081d112f303de%2FBadge-62.svg?generation=1758039755687969&amp;alt=media" alt="Kaggle badge: Kaggle Community Member" title="Kaggle Community Member" width="56" />
</p>

---

### By the numbers

- **8,500+ contributions on GitHub since 2022** (public and private), and growing every year.
- Top contributor of 4 products in production, from a delivery super-app to a multi-tenant lab SaaS and a food-service ERP.
- Real results from commits: **-69%** screen-open latency (350 → 110 ms), **-97%** API payload (184 KB → 6 KB), **-72%** boot code in an ERP (1,354 → 381 lines).

### Experience

- **Full-Stack Developer (Java)** — [Pulse Tecnologia](https://pulsetecnologias.com.br/)
- **Full-Stack & Mobile Developer** — [JaPediu Delivery](https://japediudelivery.com)
- **Software Engineer** — [Bullean Technologies](https://bullean.com.br)
- **Tech Lead** — [CoffeeStack](https://github.com/CoffeeStackDev)
- **Mentor** — [Amontada Valley](https://amontadavalley.com.br)

Also involved in development at [Codify Tecnologia e Desenvolvimento](https://codifyweb.com/) and previously a student at **Amontada Valley**.

### Awards & Achievements

- **Winner — Apple Swift Student Challenge 2026** ([About the challenge](https://developer.apple.com/swift-student-challenge/distinguished-winners/))
- **Winner — 3rd Amontada Valley Hackathon**, with [Ninna Hub](https://ninnahub.com.br/) and [M. Dias Branco](https://mdiasbranco.com.br/)
- **2nd Place — Operação Natal 2025/2**, [toalha.dev](https://github.com/rafa-coelho/toalha.dev)
- **Model published on Hugging Face** — [bertimbau-b2w-sentiment](https://huggingface.co/codevjuan/bertimbau-b2w-sentiment)
- **Merged pull request** in [luizomf/omxterm](https://github.com/luizomf/omxterm)
- **8 badges on [Kaggle](https://www.kaggle.com/juanseveriano)**, including Competitor, Dataset Creator and API Notebook Creator

<img src="https://raw.githubusercontent.com/rafa-coelho/toalha.dev/main/historico/2025-2-operacao-natal/2o-lugar/badge.png" alt="2nd place — Operação Natal 2025/2" width="150" />

---

### Tech Stack

**AI** · LLM integration (Anthropic, OpenAI, Gemini, Ollama) · evaluation and cost tracking · RAG (embeddings + pgvector) · AI agents · MCP · vision + structured output · fine-tuning (BERTimbau) · PyTorch autograd · scikit-learn

**Backend** · Python (FastAPI, Django, Celery) · Java (Spring Boot) · Node.js (NestJS, Fastify) · Go · PHP

**Data & Services** · PostgreSQL · Redis · Prisma · Flyway · Firebase · Docker · GitHub Actions

**Frontend** · React · Next.js · Tailwind CSS · Vite

**Mobile** · React Native · Swift/SwiftUI · Kotlin · TypeScript · Flutter

---

### Writing

I occasionally share ideas, experiments, and lessons from building software on [Medium](https://medium.com/@juansev.dev).

<sub>"Start by doing what's necessary; then do what's possible; and suddenly you are doing the impossible."</sub>

<p align="right"><img src="https://komarev.com/ghpvc/?username=Juan-Severiano&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" /></p>

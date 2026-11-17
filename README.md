# Lin Hong

Computer Science (Co-op) at the University of Waterloo. My three main interests are CI, cloud infrastructure, and AI systems.

Most recently a Software Engineer Intern at **Block (Cash App)**, where I led the Cash App Web team's CI migration from Cypress to Playwright, saving the company $250,000/year. I built and optimized test harnesses using Buildkite and Docker, cutting test startup time from 40s to under 10s. I shipped across the company's repos in TypeScript, React, Java and Terraform, and provisioned AWS with S3, IAM and a PrivateLink path from CI runners to an internal service.

To speed up the migration I built an agent system that runs the tests on every change and compiles the evidence behind it into one place for review, bringing review time from a 10-hour median to 1 hour. The agent was packaged and sent to two other teams for internal use, and it took a project scoped at six months down to two.

I also set up the web's observability, instrumenting user journeys into Datadog, Snowflake and Postgres, which unblocked Cash App Web's move to continuous deployment.

I have been to over 40 hackathons and won ten, including Best Use of Terraform at Hack the North 2024, and am part of the Major League Hacking Top 50.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [**Chess Bot**](https://github.com/LinHong149/chesshacks) | AlphaZero chess engine built from scratch. One network scores the position and ranks the moves, a search uses those rankings to decide where to look, and the engine improves by playing itself. Trained on GPUs through Modal. | PyTorch, Modal, Python |
| [**Sherlock Combs**](https://github.com/LinHong149/cxc) | Turns investigative PDF dumps into an evidence-cited relationship graph. DOJ scrape to Snowflake, pdfplumber parsing, spaCy NER, GPT-4o summarization, Neo4j graph, timeline UI where every edge links to its source snippet. Built in 24 hours. | Python, spaCy, GPT-4o, Neo4j, Snowflake, Next.js |
| [**QuickCart**](https://github.com/nuthanan06/deltahacks) | Grocery checkout that prices a cart from camera video. YOLOv8 detects items, CLIP embeds them, FAISS matches against a product index. Runs live at 12 frames per second. | YOLOv8, CLIP, FAISS, Flask, React Native |
| [**The Badge Knows**](https://github.com/abigail-liang/hack-the-north-2026-badge) | Rewrote the Hack the North 2026 event badge's locked firmware in 36 hours so it acts like Find My for people in the venue. Distance comes from timing WiFi signals; direction from spinning in a circle while the badge reads the dip your body makes in the signal. Semi-finalist. | C, ESP-IDF, FreeRTOS, ESP32-C3 |
| [**Navi**](https://github.com/dan-the-man639/Navi) | Gamified platform collecting supervised computer-use data for training Computer Use Agents, built after seeing how hard CUA training data is to source. | Next.js, TypeScript, React |
| [**job-ops**](https://github.com/LinHong149/job-ops) | Chrome extension and MCP server that fills application forms, classifies inbound job mail from Gmail, and writes status back to a Notion database. | MCP, Node.js, Gmail API, Notion API |
| [**Muffle Bubble**](https://github.com/LinHong149/noiseCancel) | Room-scale active noise cancellation. Adaptive filtering with secondary-path identification; cut end-to-end latency from ~200ms to ~10ms, the threshold where cancellation starts working. Hardware Track winner, TechNova 2025. | Python, NumPy, SciPy, DSP |
| [**Lofied**](https://github.com/LinHong149/Lofied) | Converts Spotify playlists into lo-fi tracks through a source-separation and DSP pipeline, and transcribes them to sheet music. Best Solo Hack and Top 6 Overall, JamHacks 2025. | Python, torchaudio, Pedalboard, Basic Pitch |
| [**HomeLab**](https://github.com/LinHong149/linhong) | Self-hosted Linux server running Dockerized Node apps behind Nginx and Cloudflare, with PM2 process management and HTTPS reverse proxying. | Linux, Docker, Nginx, Cloudflare, PM2 |

## What I work with

**Infrastructure** Terraform, AWS (S3, IAM, PrivateLink, Secrets Manager), Docker, Buildkite, GitHub Actions, Nginx, Linux

**Backend** Python, Go, Java, TypeScript, C++, FastAPI, Flask, Node.js, PostgreSQL, Redis, MongoDB, SQS

**Testing and observability** Playwright, Cypress, Vitest, Argos CI, Datadog, Snowflake, time-matched A/B benchmarking

**AI and ML** PyTorch, YOLOv8, CLIP, FAISS, spaCy, Modal, LLM agent skills and workflows, multi-agent review automation, MCP servers

## Reach me

[LinkedIn](https://linkedin.com/in/linhongdev) · linlin.hong1@gmail.com

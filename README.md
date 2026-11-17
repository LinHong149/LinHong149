# Lin Hong

Computer Science (Co-op) at the University of Waterloo. I work on build and test infrastructure, backend services, and the agents that run on top of them.

Most recently a Software Engineer Intern at **Block (Cash App)**, where I led Cash App Web's org-wide migration from Cypress to Playwright: 729 spec files audited, 16 suites taken to 1:1 parity, $250,000/yr in subscription cost removed. I built the shared test harness and the CI pipelines every migrated suite runs on, cut CI machine time 33% per build (9,719 to 6,499 job-seconds), and dropped test startup from 16-40s to 0.8s. When I measured that review, not authoring, was the bottleneck (2-4 hours to write a suite against a 41-hour median to merge), I built a 12-lens AI review pack that confirmed 176 findings and cut reviews to minutes, then encoded the method into an agent skill two other teams took for their own repos.

Ten hackathon wins. MLH Top 50.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [**Chess Bot**](https://github.com/LinHong149/chesshacks) | AlphaZero-style engine. Policy-value network trained by self-play, neural priors guiding MCTS, distributed training on A100/H100 via Modal. ~1600 Elo against classical engines. | PyTorch, Modal, Python |
| [**Sherlock Combs**](https://github.com/LinHong149/cxc) | Turns investigative PDF dumps into an evidence-cited relationship graph. DOJ scrape to Snowflake, pdfplumber parsing, spaCy NER, GPT-4o summarization, Neo4j graph, timeline UI where every edge links to its source snippet. Built in 24 hours. | Python, spaCy, GPT-4o, Neo4j, Snowflake, Next.js |
| [**QuickCart**](https://github.com/nuthanan06/deltahacks) | Camera-based grocery checkout with no barcodes. YOLOv8 detection into CLIP (ViT-B-32) embeddings into FAISS retrieval, running on live video at 12 FPS. | YOLOv8, CLIP, FAISS, Flask, React Native |
| [**The Badge Knows**](https://github.com/abigail-liang/hack-the-north-2026-badge) | Replaced the Hack the North 2026 badge firmware in 36 hours so it points you to a teammate. Range by 802.11mc Fine Timing Measurement, bearing recovered with no compass by fitting the body-shadow RSSI dip from a 360 spin. Semi-finalist. | C, ESP-IDF, FreeRTOS, ESP32-C3 |
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

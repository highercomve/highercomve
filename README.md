# Sergio Marin

**Senior Software Engineer | Solution Architecture, Distributed Systems & Cloud Orchestration | MCP & AI Workflow Automation**

Santiago, Chile · Remote

Senior software engineer with 18 years turning complex distributed systems into reliable products, from Linux edge devices to Kubernetes clouds. Top individual contributor to [Pantacor](https://pantacor.com)'s open-source over-the-air update platform (3,500+ commits since 2019), used in production by large manufacturers whose engineering teams I work with directly. I'm always on call for the platform I build.

## What I build

- **Remote build platform**: a multi-tenant build service (Go, MongoDB) with atomic job claims, heartbeat recovery and sandboxed Docker BuildKit runners. It turns a container image or Git repository (Dockerfile, Yocto/kas, Buildroot) into signed packages and flashable images for 5 CPU architectures.
- **AI workflow automation**: the Pantacor Hub MCP server (34 tools, Streamable HTTP) with its own OAuth 2.1 authorization server (Dynamic Client Registration, PKCE), so claude.ai and Claude Code connect directly. Plus the pantavisor-apps Agent Skill, which lets AI assistants build and deploy device apps with human approval.
- **Pantacor Fleet**: the release and fleet-management platform one customer runs 15,000+ Linux devices on (Go/React). It has phased rollouts, rule-based channels, a lease-based worker engine and event-driven sync. Authorization has three layers (JWT, OPA, SpiceDB/ReBAC), and tracing runs on OpenTelemetry.
- **Security**: passkeys and 2FA, OAuth 2.1 / OIDC / PKCE and SSO, TPM device identity and certificate revocation, a certificate authority for OEM code signing, and AES-GCM encrypted secrets.
- **Production platform**: bare-metal Kubernetes (Helm, Kafka, AWS S3), observability with Prometheus, Grafana, OpenTelemetry and EFK, a webhook pipeline on Kafka CDC with outbox, dead-letter queue and replay, and Stripe subscription billing.
- **Device tooling**: [pvflasher](https://github.com/pantavisor/pvflasher) (an image flasher 2.7× faster than the balenaEtcher engine, with read-back verification), Wi-Fi onboarding over D-Bus and BLE, and [pantavisor-mocker](https://github.com/pantavisor/pantavisor-mocker), a fleet simulator in Zig.

## forEach developer

[foreachdeveloper.com](https://foreachdeveloper.com/) is my open-source studio of apps that run on your own machine, AI included:

- [**Oriel**](https://github.com/highercomve/Oriel): a Zig framework for desktop and mobile apps with built-in local AI (llama.cpp, whisper.cpp, Kokoro TTS, sqlite-vec).
- [**GhostReel**](https://github.com/highercomve/GhostReel) (Rust): local video search and AI-assisted editing, with hybrid full-text and vector search, an LLM-as-judge with replay evals, and an MCP server.
- [**GhostPen**](https://github.com/highercomve/GhostPen): offline AI writing, dictation, live captions and meeting transcription.
- [**HollerShare**](https://github.com/highercomve/hollershare): Quick Share-compatible file transfer with Android.
- [**highllama**](https://github.com/highercomve/highllama) (Python): local LLM serving with a contamination-free coding benchmark.

## Tech

Go · Python · Rust · Zig · TypeScript · Model Context Protocol (MCP) · Agent Skills · llama.cpp / whisper.cpp · RAG · LLM evals · Kubernetes · Helm · Docker · AWS · MQTT · Apache Kafka · OpenTelemetry · Prometheus · Grafana · OAuth 2.1 · SpiceDB / OPA · Stripe · Linux / Yocto · React · PostgreSQL · MongoDB

## Find me

- CV: [highercomve.github.io](https://highercomve.github.io/) ([plain text](https://highercomve.github.io/cv.md))
- LinkedIn: [linkedin.com/in/highercomve](https://www.linkedin.com/in/highercomve)
- Blog: [medium.com/@highercomve](https://medium.com/@highercomve)
- Talks: Open Source Summit North America 2022 (workshops), La Plata JS, Noders JS
- Email: [sergio.alejandro.mz@gmail.com](mailto:sergio.alejandro.mz@gmail.com)

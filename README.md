# TrustYourAgent.github  (TYA)

**Runtime behavioural trust for agentic AI**

Local-first behavioural observability + cryptographic attestations for CrewAI, LangGraph, MCP, and LlamaIndex agents.  
Debug drift, loops, and non-determinism for free in Docker/air-gapped mode.  
Production-grade patented scoring and advanced trust ratings in the cloud.

Built on the foundation of **BASTYN** — the AI Agent Certification & Trust Ratings platform.

---

## ✨ Why TrustYourAgent?

Agentic workflows are powerful — until they drift, loop, or behave unpredictably in production.  
TYA gives you **immediate visibility** into agent behaviour without changing your code much.

- **Local tier (free forever)**: Unlimited debugging with basic reliability signals — zero cost, fully air-gapped.
- **Cloud tier**: Patented knowledge-base scoring, predictive drift detection, cross-agent reputation, and full EU AI Act evidence.

Perfect for developers who want to ship reliable agents today and scale trust tomorrow.

---

## 🚀 Quick Start (under 2 minutes)

```bash
# 1. Install the SDK
pip install tya

# 2. Run the local Docker engine (recommended for full local mode)
docker run -d --name tya-local -p 8080:8080 rootedlogic/tya-local:latest


# Naveen Gali 👋

## About Me

I'm a founding engineer and IEEE-published researcher building AI-native infrastructure. I designed and shipped **D-GIX**, a production geospatial indexing engine over 3.55M places with 19ms latency (24x faster than Google Places API) and a 98.7% infra-cost reduction, and I architected the **Polyhistor Location Intelligence API** that powers it. I care about systems that are fast, cheap to run, and built for AI agents, not just human UIs.

- 🔭 Currently building: [Polyhistor](https://thepolyhistor.com) — Location Intelligence API for AI Agents
- 📄 Co-Author: D-GIX: Dynamic Geospatial Indexing (IEEE-published)
- 🌍 Based in Washington, DC · Open to founding engineer roles (SF/NYC, in-person)
- 📫 naveengali80@gmail.com · [LinkedIn](https://www.linkedin.com/in/naveen-gali/)

## Featured Work

### 🌐 D-GIX — Dynamic Geospatial Indexing
IEEE-published, 3-layer geospatial intelligence stack (semantic embeddings, temporal state machines, H3-based differential privacy) over 3.55M POIs.
- **Recall@10 = 0.97**, up from 0.20 baseline, via sequential ablation across V/T/Tribe layers
- **19ms warm-cache latency** (P95 = 23ms) vs. 464–697ms for Google Places API, 0% failure rate under 4,400+ concurrent requests
- Solved HNSW build-memory constraints for a 10.4GB vector graph via Docker/Postgres tuning
- Implemented Laplace-mechanism differential privacy (ε = 1.0) over H3 hex cells for crowd-density signals

### 📍 Polyhistor — Location Intelligence API for AI Agents
Production contextual search engine for autonomous AI agents combining semantic vibe search, real-time temporal routing, and privacy-preserving crowd data.
- **98.7% lower infra cost** vs. Google Places API ($297/mo vs. $22,880/mo at 1M requests) via self-hosted Postgres + pgvector + PostGIS
- Designed the Opportunity Cost Engine — a unified scoring function combining routing cost, crowd density, and temporal state
- Built demo/heatmap UI with Leaflet + CARTO across 8 cities and 7 "tribe" profiles

### ✈️ LLM-Driven Itinerary Planner (React Native)
- Cut user trip-planning time by **40%** using LLM-generated itineraries
- Scaled to 2,000+ concurrent users on AWS (Lambda, S3, DynamoDB)
- Built WatermelonDB offline-first sync with 100% data integrity in zero-connectivity environments

## Skills

**Geospatial & Vector:** PostgreSQL · PostGIS · pgvector · HNSW · DuckDB · H3 Hexagonal Indexing · Overture Maps · Leaflet · CARTO
**AI/ML Infra:** Sentence-Transformers · PyTorch · Redis embedding cache · Differential Privacy (Laplace) · Semantic Search · RAG pipelines
**Backend & Cloud:** Node.js · Python · Express · AWS (Lambda, S3, DynamoDB, EC2) · Docker · Kubernetes · Gunicorn · Kafka · Supabase · Redis
**Frontend & Mobile:** React Native (Fabric/CLI/Expo) · React.js · TypeScript · Redux Toolkit · Tailwind CSS
**DevOps & Data:** GitHub Actions CI/CD · Locust load testing · pgbench · Parquet · DuckDB streaming · WebSocket

## Experience

**Founding Engineer — Polyhistor Inc.** · *Oct 2025 – Present*
Architected and shipped a location intelligence API purpose-built for autonomous AI agents; reduced infra cost by 98.7% and achieved 19ms latency at scale.

**Software Engineer, React Native — Mutual Mobile** · *Dec 2022 – Sept 2023*
Led JS → TypeScript migration on a Fortune 500 client app (+25% performance, eliminated a class of runtime errors); reduced crash rates 15% via profiling and Redux optimization.

**Application Developer — Inventgrid** · *Jul 2021 – Dec 2022*
Built core auth and dashboard modules that drove a 50% increase in user retention; cut initial load times 40% via async data-bridging patterns.

## Education

- **M.S., Computer Science** — Illinois Institute of Technology, Chicago, IL
- **B.S., Computer Science** — Bharath Institute of Higher Education and Research, Chennai, India

## Let's Connect

[LinkedIn](https://www.linkedin.com/in/naveen-gali/) · [Polyhistor](https://thepolyhistor.com)

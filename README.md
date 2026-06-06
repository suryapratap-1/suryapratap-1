<h1 align="center">Surya Pratap Das</h1>
<p align="center"><strong>Backend &amp; DevOps Engineer</strong> &nbsp;·&nbsp; Bhubaneswar, India</p>
<p align="center">
  <a href="https://linkedin.com/in/suryapratapdas">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:suryapratap0765@gmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://surya-porfolio.vercel.app">Portfolio</a>
</p>

---

## About

I build backend systems and cloud infrastructure that scale. I like taking end-to-end ownership of hard problems — event-driven pipelines, infrastructure-as-code, CI/CD, observability, and incident response. Currently at **Gravitones**, where I own the backend and infrastructure for a live-streaming platform on AWS.

## Featured Work

### Live-Streaming Platform · Gravitones
One of four engineers owning backend and infrastructure for a live-streaming platform built on the Hike app.
- Scaled to **60–70K concurrent users** in load testing using CDN, ECS auto-scaling, multi-AZ deployments, and read replicas.
- Replaced a self-managed FFmpeg/HLS transcoding setup with **AWS MediaConvert**, removing the bottleneck on the path to 1M users.
- Integrated **Widevine + FairPlay DRM** with license/token flows to secure the pipeline end-to-end.
- Provisioned the full AWS stack (ECS, VPC, RDS, CloudFront) in **Terraform** — the org's first IaC — and set up **GitHub Actions CI/CD** across six services.

### POS + Delivery Middleware · Quotus
Event-driven Node.js middleware connecting POS and delivery platforms for a Bahrain F&B pilot.
- Built **Kafka** topics with retries and dead-letter queues linking Square POS to DoorDash and Deliveroo.
- Designed an **LLM-assisted normalization layer** mapping four vendor payloads into a single internal schema.
- Stood up a **Grafana + Prometheus + Loki** observability stack from scratch for throughput, error rates, and queue lag.

### OTA Travel Platform · Quotus
Full-stack travel and hotel booking platform.
- Integrated **Amadeus GDS** for inventory and **Wincloud PMS** for property management.
- Cut full-text search latency **30–40%** by moving property search to **Elasticsearch**; cached hot read paths with **Redis**.

## Tech Stack

| | |
|---|---|
| **Languages** | TypeScript · JavaScript · SQL |
| **Backend** | Node.js · Express · Kafka · REST APIs · Microservices |
| **Cloud & DevOps** | AWS · Terraform · Docker · GitHub Actions · Nginx |
| **Databases** | PostgreSQL · Redis · MongoDB · Elasticsearch |
| **Observability** | Grafana · Prometheus · Loki |
| **Frontend** | React · Next.js · Tailwind CSS |

---

<p align="center"><sub>Open to backend / DevOps roles at product companies.</sub></p>

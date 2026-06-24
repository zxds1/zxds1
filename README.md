<p align="center">
  <img src="https://raw.githubusercontent.com/zxds1/zxds1/main/assets/profile.png" alt="Brian Mwirigi" width="180" style="border-radius:50%; box-shadow: 0 8px 32px rgba(0,0,0,0.4);"/>
</p>

<h1 align="center">Brian Mwirigi</h1>

<p align="center">
  <strong>Designing distributed, AI-native systems under real-world constraints.</strong><br/>
  Technical founder architecting fault-tolerant platforms, autonomous systems, and cloud-native infrastructure.
</p>

<p align="center">
  <a href="https://linkedin.com/in/your-linkedin-username">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://twitter.com/your-twitter-handle">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
  </a>
  <a href="mwirigib332@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## Systems Thesis

Modern software is a distributed system by default.

I design architectures that explicitly account for:

- Network partitions  
- Partial failure  
- Unbounded concurrency  
- Eventual consistency  
- Probabilistic AI subsystems  

The objective: **predictable behavior under unpredictable conditions.**

---

## Distributed Systems Engineering

### Consistency & CAP Tradeoffs

Every system chooses its failure mode.

I make tradeoffs explicit:

- Strong consistency where financial or transactional correctness is non-negotiable  
- Eventual consistency for high-throughput, user-facing workflows  
- Read replicas for horizontal scaling  
- Leader-based write coordination when ordering matters  
- Idempotent operations to survive retries  

I design around the reality that partitions are inevitable — availability decisions are intentional, not accidental.

---

### Consensus & Coordination

Where coordination is required:

- Leader election strategies  
- Quorum-based decision models  
- Distributed locks with bounded TTL  
- Deterministic state transitions  

Where coordination is not required — I eliminate it.

Minimize synchronization. Reduce shared mutable state. Prefer append-only logs and immutable events.

---

### Replication & Data Architecture

- Primary-replica replication for transactional workloads  
- Read-heavy workloads optimized via replica fan-out  
- Logical data separation by bounded contexts  
- Hybrid storage: relational cores + vector memory layers  
- Write-through and write-back caching strategies  

Data durability and recovery paths are designed before features.

---

### Caching & Latency Engineering

Latency is a systems problem, not a frontend problem.

- Multi-layer caching (edge → service → database)  
- Cache invalidation through event propagation  
- TTL tuning aligned to business SLAs  
- Cold-start mitigation strategies  
- Backpressure and load shedding under saturation  

I design systems that maintain SLOs under peak stress.

---

### Failure Isolation & Resilience

- Circuit breakers  
- Bulkhead isolation  
- Graceful degradation pathways  
- Retry with exponential backoff + jitter  
- Health checks, readiness probes, and rolling restarts  

Blast radius is always constrained.

If a component fails, the system bends — it doesn’t collapse.

---

## AI as a Distributed Subsystem

AI components are probabilistic nodes inside deterministic infrastructure.

I build:

- Agent orchestration layers with tool routing  
- Structured memory (vector + relational hybrid models)  
- Inference observability and trace logging  
- Validation loops and human override paths  
- Fallback models under degradation  

AI is wrapped in guardrails, telemetry, and cost-aware orchestration.

---

## Cloud-Native Infrastructure

- Dockerized microservices  
- Kubernetes orchestration  
- Horizontal pod autoscaling  
- Stateless compute + durable storage  
- Rolling deployments and zero-downtime migrations  

Infrastructure is elastic by design, not by hope.

---

## Performance & Concurrency Stack

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
</p>

---

## Engineering Philosophy

- Design for failure before designing for scale  
- Prefer mechanical sympathy over abstraction layering  
- Make tradeoffs explicit and measurable  
- Optimize for operability and observability  
- Build systems that become more reliable as they evolve  

---

## Current Focus

- Agent-driven operational infrastructure  
- High-availability transaction systems  
- Real-time merchant platforms  
- Distributed AI-native backends for emerging startups  

---

<p align="center">
  Based in Mombasa · Shipping globally · Engineering for resilience
</p>

<p align="center">
  <strong>Building systems that remain predictable under scale, concurrency, and uncertainty.</strong>
</p>

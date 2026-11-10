<h1 align="center">Abhinav MV</h1>

<p align="center">
  Backend Engineer &nbsp;·&nbsp; Distributed Systems &nbsp;·&nbsp; Web3 Data
</p>
<p align="center">
  <a href="https://abhinav-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/abhinav-mv-b216b8160/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://twitter.com/abhinav_m_v"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:mvabhinav1998@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<br/>

I build backend services and real-time data pipelines that power blockchain data APIs. At [Moralis](https://moralis.com), I work on wallet, token and price APIs for Solana and EVM chains, with a focus on performance, reliability and clean system design.

### What I work on

- **DEX indexing**: designed a Solana swap-parsing framework with decoders for 9 pool types across Orca, Raydium and Meteora; onboarded 6 EVM chains and 12+ DEX protocols
- **High-throughput APIs**: TypeScript and NestJS services backed by ClickHouse, PostgreSQL and Elasticsearch
- **Performance**: query optimisation, memory profiling and latency tuning, with Rust where it counts
- **Safe migrations**: shadow traffic and response diffing before every cutover, across 7 EVM chains
- **AI-assisted engineering**: Claude Code daily for design, review and debugging; built a latency-regression agent with the Claude Agent SDK

### Recent wins

| Impact | What changed |
| --- | --- |
| **29 → 4.7 GB** | Rust data-processing service memory (−84%), by switching to jemalloc |
| **~230x** | Faster p99 on a ClickHouse price lookup, with zero timeouts and half the memory |
| **3.8x** | Faster Solana block decoding, with byte-identical output |
| **7–8s → 2.5s** | Large-wallet Solana API latency, by parallelising metadata lookups |
| **47%** | Of missed Raydium AMM v4 swaps recovered (~236k records a day) |

### Side projects

- **[epub-translator](https://github.com/AbhinavMV/epub-translator)**: translate EPUBs chapter by chapter with Claude, OpenAI or Gemini, with side-by-side reading and reviewable AI proofreading. [Live demo](https://epub-translator-llm.vercel.app)
- **[Portfolio](https://github.com/AbhinavMV/Portfolio)**: my personal site, built with Next.js 16, TypeScript and Tailwind CSS v4. [Live](https://abhinav-portfolio.vercel.app)

### Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,rust,nodejs,nestjs,postgres,mongodb,redis,elasticsearch&perline=10" alt="Languages, backend and databases" />
  <br/>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,grafana,prometheus,react,nextjs,git&perline=10" alt="Cloud, infrastructure and frontend" />
</p>

<sub>Also: ClickHouse · DynamoDB · gRPC · Kafka-style streaming · Helm · Solana · EVM</sub>

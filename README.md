<!--
  GitHub Profile README — ldamoredev
  Renders at github.com/ldamoredev
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./header-dark.svg">
  <img src="./header-light.svg" alt="Lautaro Damore — Senior Software Engineer · Distributed Systems · Security · Applied AI" width="100%">
</picture>

[X](https://x.com/ldamoredev) · [LinkedIn](https://www.linkedin.com/in/lautaro-damore/)

## About

Senior software engineer from Argentina, 7+ years shipping production software with
international teams. I came up through the software craftsmanship movement — clean code,
solid architecture, XP practices — and I've spent the last years pointing that same rigor
at the parts of a system that are actually hard: concurrency, failure modes, authorization,
and the non-determinism that AI drags into production with it.

I think in trade-offs rather than hype. I like turning vague requirements into specs an
engineer — or an agent — can actually execute, and I'd rather show you a system failing
under load than a demo that always works.

Right now I'm going deeper on the systems side: the design decisions that decide whether
something survives its second year in production, not its first demo.

## What I work on

**Distributed systems & design** — idempotency and concurrency, partitioned logs, multi-region
latency, observability and SLOs. The failure modes that only show up under load.

**Security** — authentication and authorization, the MCP attack surface, and auditing what an
agent is actually allowed to do once you hand it real tools.

**Applied AI** — RAG pipelines, agent architectures, and evaluation harnesses that can fail.
Production, not notebooks.

**Enterprise software** — TypeScript-heavy stacks, clean architecture, TDD, and the boring
discipline that keeps a codebase alive across teams.

## How I build with AI

The model interprets and extracts, with evidence attached. The code calculates, scores and
verifies. The model never decides the final number, and uncertainty stays explicit instead of
being averaged away into a confident answer.

Most AI features break because that line got blurred somewhere. Mine are built so you can
audit which side made each decision.

## Selected work

**[MCPLens](https://mcplens.up.railway.app)** — Security audit for MCP servers. Hybrid rule + model detection, deterministic scoring.

**[CVLens](https://cvlens.up.railway.app)** — Auditable CV analysis. The model extracts findings; a rubric in code does the scoring. No persistence.

**[whatsapp-concurrency-lab](https://github.com/ldamoredev/whatsapp-concurrency-lab)** — Concurrency under real failure: k6 load, Toxiproxy fault injection, and pods killed mid-flight to see what the system actually does.

## Writing

I keep an atlas of what I learn — distributed systems, security, and how AI behaves when it
stops being a demo. Long form on the blog, shorter and messier on X.

[Cybersecurity Atlas](https://ldamoredev.github.io/cibersecurity-notes/) · [AI Atlas](https://ldamoredev.github.io/ai-notes/) · [X](https://x.com/ldamoredev)

Open to talking about hard systems problems. Not looking for freelance work.

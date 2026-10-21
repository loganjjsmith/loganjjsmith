### Logan Smith

Backend engineer, 10+ years in wireless telecom: provisioning, mediation, and the event-driven systems (Java, Kafka, Spring Boot) that keep orders, network changes and billing data in agreement. Madison, WI.

I design systems, own them in production, and lately direct AI coding agents and review what they produce. These repos show that second part, labeled honestly.

| Repo | What it shows | Who wrote the code |
|---|---|---|
| [**offload**](https://github.com/loganjjsmith/offload) | An MCP server that hands reading, extraction and summaries to local open-weight models, checks the results in code, and switches off any flow whose answers keep being redone. Which model does which job is decided by a benchmark harness run on one desktop GPU. | AI agents (Claude Code), under rules I set. I set the goals and constraints, made the decisions and reviewed the results. [How that worked](https://github.com/loganjjsmith/offload/blob/main/docs/BUILDING-WITH-AI.md). |
| [**first-unity-project**](https://github.com/loganjjsmith/first-unity-project) · [▶ play in browser](https://loganjjsmith.github.io/first-unity-project/) | A Unity physics movement sandbox, and my first game project: climbing, wire riding, a slingshot and ragdoll recovery, with 248 unit tests and 14 tests that play the real scene. | Mostly AI agents (Grok, then Claude Code). I directed it, did the Unity Editor work, wrote the smaller pieces where the learning was, and playtested. [Who did what](https://github.com/loganjjsmith/first-unity-project/blob/main/AI-WORKFLOW.md). |

**Coming soon:** an order platform on AWS, written entirely by hand. Postgres, Spring Boot, a tested order state machine, then Kafka and a transactional outbox. The state machine is already arguing with me about whether a cancelled order can ever change its mind.

[LinkedIn](https://www.linkedin.com/in/logan-jj-smith)

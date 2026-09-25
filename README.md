# Kevin Masterson

**Forward-Deployed AI Engineer · Dallas-Fort Worth / Remote**

I build AI systems that go into real environments and keep working after the demo: agents with review gates, monitors that catch the failure nobody is watching for, and tools that civic and community teams actually use.

## Selected work

| Project | What it does | Proof |
|---|---|---|
| [gowork](https://github.com/fivedollarfridays/gowork) · [gowork.city](https://www.gowork.city) | Civic AI workforce navigator. Multi-provider LLM (Claude, OpenAI, Gemini) with fallback, FAISS + barrier-graph retrieval, SSE streaming, SSRF allowlisting, PII-safe logging. | 2nd of 2,700+ at Worldwide Vibes · 2nd at HackFW 2026 |
| [datahub-rail-agent](https://github.com/fivedollarfridays/datahub-rail-agent) | Health-monitoring agent that drives DataHub's context graph over its MCP server: freshness checks, lineage-break root-cause triage, schema-drift artifacts, verdicts written back into DataHub. | 220 tests, 90% coverage · DataHub Agent Hackathon entry |
| [lastrites](https://github.com/fivedollarfridays/lastrites) | Local-first credential-estate watchdog: finds every copy of a credential across machines, canary probes, blast-radius escalation, threat model enforced by a conformance suite. | 358 tests · security audit fixed before first merge · MIT |
| Deadman ([live](https://deadman-mrapac5nda-uc.a.run.app)) | Silent-failure monitor: "the absence of a signal is the signal." Cloud Run, Firestore, Secret Manager, Cloud Scheduler, Gemini on Vertex. | 573 tests · unattended fire drill: 33 minutes from silent failure to alert |
| [dualstack](https://github.com/fivedollarfridays/dualstack) | Open-source full-stack starter kit. | 1,460 tests · 95% coverage |

## How I work

- **Agents in production, with gates.** I run a fleet of coding agents on my own operations system: test-first, native review on every PR, fail-closed checks, and every bypass written to an audit log. 400+ merged PRs.
- **Verify the deployed thing.** More than once, green test suites hid a real bug that only showed up when I exercised the live service. Checking production is part of the job.
- **Write it down.** After an outage I write an incident report and a rule so it can't happen silently again.

## Community

Volunteer with the Fort Worth DAO: I manage the HackFW 2026 campaign and the DAO's production kit, and contribute to its website.

## Contact

[LinkedIn](https://www.linkedin.com/in/theofficialkevinmasterson)

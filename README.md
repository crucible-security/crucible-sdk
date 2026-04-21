# crucible-sdk

Official Python SDK -- connect any AI agent to Crucible security infrastructure in 2 lines.

---

**Status: Under active development.** The SDK is being built alongside the [Crucible](https://github.com/crucible-security/crucible) core framework. Star this repo to get notified when the first release drops.

## What this will do

```python
from crucible_sdk import CrucibleGuard

guard = CrucibleGuard(api_key="sk-...")
result = guard.scan("https://my-agent.com/api/chat")

print(result.grade)
```

**Two lines.** Your agent gets a full security scan with a letter grade and actionable report.

## Planned Features

* Drop-in middleware for LangChain, CrewAI, and OpenAI Agents
* * Continuous monitoring with scheduled scans and alerting
  * * Runtime guard that intercepts and blocks malicious inputs
    * * Dashboard integration for security posture tracking
      * * API key management with team-level access controls
       
        * ## Relationship to Crucible
       
        * * [crucible](https://github.com/crucible-security/crucible) | CLI framework -- run crucible scan from terminal or CI/CD
          * * **crucible-sdk** (this repo) | Python SDK -- integrate security scanning into your agent code
           
            * ## License
           
            * Apache 2.0 -- see [LICENSE](LICENSE).
            * 

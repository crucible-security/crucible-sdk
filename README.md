<p align="center">
  <h1 align="center">:link: crucible-sdk</h1>h1>
    <p align="center"><strong>Official Python SDK -- connect any AI agent to Crucible security infrastructure in 2 lines.</strong>strong></p>p>
    </p>
    
    <p align="center">
      <a href="https://pypi.org/project/crucible-sdk/"><img src="https://img.shields.io/badge/pypi-coming%20soon-lightgrey?style=flat-square" alt="PyPI"></a>
        <a href="https://github.com/crucible-security/crucible-sdk"><img src="https://img.shields.io/badge/python-3.9%2B-blue?style=flat-square" alt="Python 3.9+"></a>
          <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square" alt="License"></a>
          </p>
          
          ---
          
          > **Status: Under active development.** The SDK is being built alongside the [Crucible](https://github.com/crucible-security/crucible) core framework. Star this repo to get notified when the first release drops.
          
          ## What this will do
          
          ```python
          from crucible_sdk import CrucibleGuard
          
          guard = CrucibleGuard(api_key="sk-...")
          result = guard.scan("https://my-agent.com/api/chat")
          
          print(result.grade)  # "A"
          ```
          
          **Two lines.** Your agent gets a full security scan -- prompt injection, goal hijacking, jailbreak testing -- with a letter grade and actionable report.
          
          ## Planned Features
          
          - :electric_plug: **Drop-in middleware** for LangChain, CrewAI, and OpenAI Agents
          - :bar_chart: **Continuous monitoring** with scheduled scans and alerting
          - :shield: **Runtime guard** that intercepts and blocks malicious inputs
          - :chart_with_upwards_trend: **Dashboard integration** for security posture tracking
          - :key: **API key management** with team-level access controls
          
          ## Relationship to Crucible
          
          | Component | Purpose |
          |-----------|---------|
          | [crucible](https://github.com/crucible-security/crucible) | CLI framework -- run `crucible scan` from terminal or CI/CD |
          | **crucible-sdk** (this repo) | Python SDK -- integrate security scanning into your agent code |
          
          ## License
          
          Apache 2.0 -- see [LICENSE](LICENSE).
          
          ---
          
          <p align="center">
            <a href="https://github.com/crucible-security/crucible">:leftwards_arrow_with_hook: Back to Crucible</a>
            </p>
            </strong>

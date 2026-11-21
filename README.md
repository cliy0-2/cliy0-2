<!-- You opened the source. Good instinct. -->

<p align="center">
  <img src="assets/header.svg" alt="cliy0-2 · SOC Analyst" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Elasticsearch-161b22?style=for-the-badge&logo=elasticsearch&logoColor=56d4c1" alt="Elasticsearch" />
  <img src="https://img.shields.io/badge/Kibana-161b22?style=for-the-badge&logo=kibana&logoColor=56d4c1" alt="Kibana" />
  <img src="https://img.shields.io/badge/Python-161b22?style=for-the-badge&logo=python&logoColor=56d4c1" alt="Python" />
  <img src="https://img.shields.io/badge/Linux-161b22?style=for-the-badge&logo=linux&logoColor=56d4c1" alt="Linux" />
  <img src="https://img.shields.io/badge/Wireshark-161b22?style=for-the-badge&logo=wireshark&logoColor=56d4c1" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=for-the-badge&logo=docker&logoColor=56d4c1" alt="Docker" />
</p>

### Hi 👋

I'm a SOC analyst. In practice, I spend my days reading logs and looking for **the one line that doesn't add up**.

I'm a bit of a jack-of-all-trades and genuinely nosy: I like taking security mechanisms apart to see how they hold together, and where they give way. I look at both defense *and* offense, because you can't really learn one without the other.

Also, a bit of a nerd. I'm always learning something: a new tool, a new protocol, a new way to break or protect things. And I lean on **AI** a lot to go further and faster, as a sparring partner, not a crutch.

### 🛡️ What I do

- **Triage & investigation**: turning raw alerts into a clear story: what happened, how far it went, what to do next.
- **Detection engineering**: writing and tuning detection rules, cutting noise without losing signal, mapping coverage to MITRE ATT&CK.
- **Threat hunting**: starting from a hypothesis, not an alert, and digging through endpoint, network and identity data.
- **Incident response support**: scoping, timelines, containment recommendations, and clean write-ups.
- **Automation**: Python tooling to enrich alerts, query the SIEM and take the repetitive work off the analysts' plate.
- **AI-assisted analysis**: using LLMs to speed up triage, summarize investigations and draft detections, always with a human checking the output.

### 🔬 Research: DRM & content protection

On my own time, I study how **DRM and content protection schemes** actually work: license acquisition flows, key handling, white-box cryptography, and the obfuscation and anti-tamper layers built into client applications.

What draws me in is the same question as in the SOC: *where is trust placed, and what happens when that assumption breaks?* Taking these systems apart is a great way to learn reverse engineering, applied crypto and secure design, all at once.

My workflow is **AI-augmented**: I plug reverse engineering tools into AI agents through **MCP servers** (like [REA](https://github.com/morluto/rea), with Ghidra, IDA and Hopper backends) so the agent can decompile, search strings, trace calls and resolve symbols, while I steer the analysis and verify what it finds.

<sub>Research is done for learning purposes, on my own devices and lawfully obtained content. No piracy, no key sharing.</sub>

### 🔁 Both sides

<p align="center">
  <img src="assets/both-sides.svg" alt="Every step of an attack leaves a trace on the defense side" width="100%" />
</p>

### 🧰 Toolbox

| Area | Tools I work with |
|---|---|
| **SIEM & data** | Elasticsearch, Kibana, Logstash, Beats, Splunk |
| **Detection** | Sigma, YARA, KQL / EQL, MITRE ATT&CK |
| **Network** | Wireshark, Zeek, Suricata, tcpdump |
| **Endpoint & DFIR** | Sysmon, Velociraptor, Volatility |
| **Threat intel & case mgmt** | MISP, TheHive, VirusTotal |
| **Reverse engineering** | Ghidra, IDA, Frida, x64dbg, mitmproxy |
| **AI & MCP** | Claude, LLM agents, MCP servers (REA, Ghidra / IDA MCP) |
| **Scripting & infra** | Python, Bash, Docker, Git, Linux |

### 🗂️ Triage notes

```yaml
role:       SOC analyst
method:     observe → doubt → verify
field:      logs, network, systems, and whatever lurks in between
defense:    detection, investigation, incident response
offense:    CTFs, labs, understanding how things break
research:   DRM internals, license flows, client-side hardening
tooling:    AI agents + MCP wired into the RE workflow
mode:       always learning, mildly nerdy, endlessly curious
currently:  figuring out why the things that work actually work
```

<p align="center">
  <sub>Understand offense to defend better. And the other way around.</sub>
</p>

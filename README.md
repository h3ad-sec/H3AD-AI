# H3AD-AI

**AI-Assisted Security — Part of [H3AD-SEC](https://h3ad-sec.github.io)**

H3AD-AI is the AI module of the H3AD-SEC platform. It provides analyst-focused AI tools for runbook generation, detection query building, false positive analysis, ATT&CK mapping, and timeline reconstruction.

Live at: [h3ad-sec.github.io/H3AD-AI](https://h3ad-sec.github.io/H3AD-AI/)

---

## Tools

### [INSIGHT-AI](https://h3ad-sec.github.io/INSIGHT-AI/)
AI-powered incident runbook generator using an L3/SME analyst persona. Input an alert name and context; receive a structured 10-section playbook covering triage, investigation steps, detection queries (KQL/Sigma/XQL), MITRE ATT&CK mapping, and IR decision points. Strict data discipline — no hallucinated indicators or filler.

### [QUERYCRAFT-AI](https://h3ad-sec.github.io/QUERYCRAFT-AI/)
Natural language to detection query builder. Describe what you want to detect and get production-ready KQL, Sigma, or XQL output. Output includes field mappings, platform notes, and ATT&CK technique tags.

### [FPLENS-AI](https://h3ad-sec.github.io/FPLENS-AI/)
False positive analysis tool. Input an alert and its context; receive a structured likelihood assessment with analyst justification, environment factors, and recommended disposition.

### [ATTMAP-AI](https://h3ad-sec.github.io/ATTMAP-AI/)
ATT&CK technique mapper. Paste alert details, log excerpts, or behavioral descriptions and receive ranked MITRE ATT&CK technique matches with sub-technique precision and confidence notes.

### [CHRONO-AI](https://h3ad-sec.github.io/CHRONO-AI/)
Incident timeline builder. Paste raw investigation notes, log snippets, or IR report text and receive a structured chronological event timeline with artifact callouts and gaps flagged.

### [MALBRIEF-AI](https://h3ad-sec.github.io/MALBRIEF-AI/)
Malware behavior analyzer. Input behavioral indicators, sandbox output, or incident context; receive malware classification, MITRE ATT&CK technique mapping, detection signatures, and hunting pivot suggestions. Also listed under H3AD-DF.

### [PROMPTVAULT](https://h3ad-sec.github.io/PROMPTVAULT/)
Curated AI prompt library for SOC analysts and detection engineers. Browse 100+ prompts across 6 categories: detection engineering, threat hunting, incident response, threat intelligence, SOC operations, and training. YAML-backed, searchable.

---

## Part of H3AD-SEC

H3AD-AI is one module of the [H3AD-SEC](https://h3ad-sec.github.io) platform — a SOC analyst and detection engineering portfolio covering threat intelligence, detection engineering, threat hunting, and incident response tooling.

Other modules: [H3AD-X](https://h3ad-sec.github.io/H3AD-X/) · [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/) · [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/) · [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/) · [H3AD-DF](https://h3ad-sec.github.io/H3AD-DF/) · [H3AD-IR](https://h3ad-sec.github.io/H3AD-IR/)

## H3AD-SEC Platform Modules

| Module | Tools |
|--------|-------|
| [H3AD-X](https://h3ad-sec.github.io/H3AD-X/) | X-VERDIKT, PARSE-X, DNSCOPE, MAILSCOPE |
| [H3AD-AI](https://h3ad-sec.github.io/H3AD-AI/) | INSIGHT-AI, QUERYCRAFT-AI, FPLENS-AI, ATTMAP-AI, CHRONO-AI, MALBRIEF-AI, PROMPTVAULT |
| [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/) | TRACERULES |
| [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/) | HYPOS, PIVEX, TRACEPULSE |
| [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/) | QUICKTRACE, SHIFTLOG, PHISHOPS |
| [H3AD-DF](https://h3ad-sec.github.io/H3AD-DF/) | REGSCOPE, MALBRIEF-AI |
| [H3AD-IR](https://h3ad-sec.github.io/H3AD-IR/) | Coming soon |
| [H3AD-LEARN](https://h3ad-sec.github.io/H3AD-LEARN/) | Threat Hunting (9 ch), LOLBAS (8 ch) |

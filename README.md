
/Your-Portfolio-Root
├── README.md                 <-- (Master 20-Phase Roadmap & Exec Summary)
│
├── /Tier-1-Enterprise-Baselines
│   ├── README.md             <-- (Narrative for Phases 1-7)
│   ├── /red-team
│   │   └── /initial-access-c2
│   │       ├── /evidence     <-- (Screenshots of NetExec, MSFvenom shells)
│   │       └── /payloads     <-- (Defanged PowerShell / C2 scripts)
│   └── /blue-team
│       ├── /siem-engineering
│       │   ├── /configs      <-- (Splunk regex, props.conf, inputs.conf)
│       │   └── /evidence     <-- (SPL query results, Sysmon Event ID 3/4625)
│       ├── /architecture-and-policy
│       │   ├── /configs      <-- (Zero Trust network segmentation plans)
│       │   └── /evidence     <-- (Firewall quarantine rules - IN PROGRESS)
│       └── /security-automation
│           ├── /scripts      <-- (Upcoming: Python log parsers)
│           └── /evidence     <-- (Upcoming: LLM API outputs)
│
├── /Tier-2-Focused-Operations
│   ├── README.md             <-- (Narrative for Phases 8-13)
│   ├── /network-forensics    <-- (Upcoming: Zeek, Suricata, PCAP analysis)
│   ├── /enterprise-pentest   <-- (Upcoming: Active Directory, Pass-the-Hash)
│   ├── /endpoint-triage      <-- (Upcoming: MFT, Prefetch, Memory dumps)
│   └── /cloud-security       <-- (Upcoming: AWS CloudTrail, IAM hunting)
│
└── /Tier-3-Specialized-Warfare
    ├── README.md             <-- (Narrative for Phases 14-20)
    ├── /purple-teaming       <-- (Upcoming: EDR bypass, WMI persistence)
    ├── /malware-analysis     <-- (Upcoming: REMnux, Reverse Engineering)
    ├── /ransomware-dfir      <-- (Upcoming: Mass encryption alerts)
    └── /ics-and-ai           <-- (Upcoming: SCADA monitoring, GenAI defense)

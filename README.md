```text
/Portfolio-Root
├── README.md                 <-- (Master 24-Phase Roadmap & Exec Summary)
│
├── /Tier-1-Enterprise-Baselines
│   ├── README.md             <-- (Narrative for Phases 1-7)
│   ├── /red-team
│   │   └── /initial-access-c2
│   │       ├── /evidence     
│   │       └── /payloads     
│   └── /blue-team
│       ├── /siem-engineering
│       │   ├── /configs      
│       │   └── /evidence     
│       ├── /architecture-and-policy
│       │   ├── /configs      
│       │   └── /evidence     
│       └── /security-automation
│           ├── /scripts      
│           └── /evidence     
│
|__ /Tier-2-Focused-Operations
|    ├── README.md                  <-- (Narrative for Phases 8-14)
|    ├── /blue-team
│    |    ├── /network-forensics         <-- (Phase 8: PCAPs, Zeek/Suricata logs)
│    |    ├── /identity-defense          <-- (Phase 11: AD Hardening, Entra ID Conditional Access)
│    |    ├── /cloud-containers          <-- (Phase 12: AWS CloudTrail configs, K8s RBAC)
│    |    ├── /endpoint-triage           <-- (Phase 13: MFT parsing, memory dumps)
│    |    └── /detection-engineering     <-- (Phase 14: Sigma rules, Detections-as-Code)
|    └── /red-team
|        ├── /network-attacks           <-- (Phase 8: Traffic generation, spoofing scripts)
|        ├── /enterprise-pentest        <-- (Phases 9 & 10: BloodHound graphs, Burp Suite payloads)
|        ├── /identity-attacks          <-- (Phase 11: Kerberoasting, SAML forging)
|        └── /cloud-exploitation        <-- (Phase 12: IAM priv-esc scripts, Docker escapes)
│
├── /Tier-3-Specialized-Warfare
│   ├── README.md             <-- (Narrative for Phases 15-21)
│   ├── /threat-emulation     <-- (NEW: CALDERA, APT Playbooks)
│   ├── /malware-development  <-- (NEW: C/Rust Loaders, EDR Evasion)
│   ├── /malware-analysis     
│   ├── /threat-intelligence  
│   ├── /ransomware-dfir      
│   ├── /wireless-mobile      <-- (NEW: IoT, iOS/Android)
│   └── /ics-and-ai           
│
└── /Tier-4-Enterprise-Architecture <-- (NEW TIER)
    ├── README.md             <-- (Narrative for Phases 22-24)
    ├── /enterprise-ir        <-- (NEW: Cross-department IR)
    ├── /grc-compliance       <-- (NEW: NIST, ISO 27001, BIA)
    └── /security-architecture<-- (NEW: Zero Trust Blueprints, Threat Models)
```

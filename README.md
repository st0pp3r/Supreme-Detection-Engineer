# Supreme Detection Engineer 
[![URL Check](https://github.com/st0pp3r/Supreme-Detection-Engineer/actions/workflows/url_check.yml/badge.svg)](https://github.com/st0pp3r/Supreme-Detection-Engineer/actions/workflows/url_check.yml/badge.svg) [![Create Bookmarks File](https://github.com/st0pp3r/Supreme-Detection-Engineer/actions/workflows/create_bookmarks.yml/badge.svg)](https://github.com/st0pp3r/Supreme-Detection-Engineer/actions/workflows/create_bookmarks.yml)

 Online resources for Detection Engineers. Detection rules, event log references, attack samples and others.

## Contents
- [Detection Rules & Detection Logic](#detection-rules-&-dettection-logic) - Online databases with rules, use cases and detection logic.
- [Attack Samples](#attack-samples) - Attack samples, useful for replying attacks and testing detection logic.
- [Event Log References](#event-log-references) - Online vendor documentation and references for event logs.
- [Resources](#resources) - Useful online resources for detection engineers.
- [Online Tools](#online-tools) - Useful online tools for detection engineers.
- [Blogs](#Blogs) -  Blogs that regularly release detection engineering related content.
- [Good Reads](#good-reads) - Good blog posts related to detection engineering.
- [Podcasts](#podcasts) - Podcasts focused on detection engineering.
- [Books](#books) - Books on detection engineering.
- [Trainings](#trainings) - Available trainings related to detection engineering.
- [Twitter/X](#twitter/X) - Relevant Twitter/X accounts.

### Detection Rules & Detection Logic
- [Sigma Rules](https://github.com/SigmaHQ/sigma) - Huge collection of detection rules from SIGMA HQ.
- [Elastic Rules](https://www.elastic.co/guide/en/security/current/prebuilt-rules.html), [Elastic Detection Rules Explorer](https://elastic.github.io/detection-rules-explorer) or [Elastic Rules GitHub Repository](https://github.com/elastic/detection-rules/tree/main/rules)- Elastic's detection rules.
- [Elastic Security for Endpoint Rules](https://github.com/elastic/protections-artifacts/tree/main)- Elastic's Security for Endpoint detection rules.
- [Splunk Rules](https://research.splunk.com/detections/) and [Splunk Rules GitHub Repository](https://github.com/splunk/security_content/tree/develop/detections) - Splunk's detection rules.
- [Sentinel Detections](https://github.com/Azure/Azure-Sentinel/tree/master/Detections) and [Sentinel Solution Rules](https://github.com/Azure/Azure-Sentinel/tree/master/Solutions)- Collection of KQL detection queries for Sentinel.
- [FortiSIEM Rules](https://help.fortinet.com/fsiem/Public_Resource_Access/7_2_2/rules/rule_descriptions.htm) - FortiSIEM's detection rules.
- [Sigma Rules | The DFIR Report](https://github.com/The-DFIR-Report/Sigma-Rules/tree/main/rules/windows) - Collection of sigma rules.
- [Sigma Rules | mdecrevoisier](https://github.com/mdecrevoisier/SIGMA-detection-rules) - Collection of sigma rules.
- [Sigma Rules | Yamato Security](https://github.com/Yamato-Security/hayabusa-rules/tree/main/sigma) - Collection of sigma rules.
- [KQL Queries | SecurityAura](https://github.com/SecurityAura/DE-TH-Aura) - Collection of KQL queries.
- [KQL Queries for Sentinel | reprise99](https://github.com/reprise99/Sentinel-Queries) - Collection of KQL queries.
- [KQL Queries | Cyb3r Monk](https://github.com/Cyb3r-Monk/Threat-Hunting-and-Detection/tree/main) - Collection of KQL queries.
- [KQL Queries for DefenderATP | 0xAnalyst](https://github.com/0xAnalyst/DefenderATPQueries) - Collection of KQL queries.
- [KQL Queries | Bert-JanP](https://github.com/Bert-JanP/Hunting-Queries-Detection-Rules/tree/main) - Collection of KQL queries.
- [KQL Search](https://www.kqlsearch.com/) - Collection of KQL queries from various GitHub repositories.
- [Attack Rule Map](https://attackrulemap.com/) - Mapping of open-source detection rules and atomic tests.
- [MITRE Cyber Analytics Repository (CAR)](https://car.mitre.org/) and [MITRE Cyber Analytics Repository (CAR) Coverage Comparison](https://car.mitre.org/coverage/) - The MITRE Cyber Analytics Repository (CAR) is a knowledge base of analytics based on the MITRE ATT&CK framework.
- [Google Cloud Platform (GCP) Community Security Analytics](https://github.com/GoogleCloudPlatform/security-analytics) - Security analytics to monitor cloud activity within Google Cloud.
- [Anvilogic Detection Armory](https://github.com/anvilogic-forge/armory/tree/main/detections) - Public versions of the sophisticated detections found within the Anvilogic Platform Armory.
- [Chronicle (GCP) Rules](https://github.com/chronicle/detection-rules) - Detection rules written for the Chronicle Platform.
- [SOC Prime](https://socprime.com/) - Great collection of free and paid detection rules.
- [LOLOL Farm](https://lolol.farm/)- A great collection of resources to thrive off the land.

### Attack Samples
- [EVTX Attack Samples](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) - Event viewer attack samples.
- [EVTX to MITRE Attack](https://github.com/mdecrevoisier/EVTX-to-MITRE-Attack) - IOCs in EVTX format.
- [Security Datasets](https://github.com/OTRF/Security-Datasets/tree/master/datasets) - Datasets of malicious and benign indicators, from different platforms.
- [Tool Analysis Results Sheet | jpcertcc](https://jpcertcc.github.io/ToolAnalysisResultSheet) - Results of examining logs recorded in Windows upon execution of 49 tools.

### Detection Rule Tests
- [Atomic Red Team | Red Canary](https://github.com/redcanaryco/atomic-red-team/tree/master/atomics) - Library of tests mapped to the MITRE ATT&CK framework.
- [Stratus Red Team | DataDog](https://github.com/DataDog/stratus-red-team) - Basically atomic red team atomics for cloud.
- [LOLOL Farm](https://lolol.farm/)- A great collection of resources to thrive off the land.
- [MITRE Caldera](https://caldera.mitre.org/) - Adversary Emulation Framework by MITRE.

### Logging Configuration Guidelines

### Event Log References
- [Windows Event IDs and Audit Policies](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/auditing/advanced-security-audit-policy-settings)
- [Windows Security Log Event IDs Encyclopedia](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/default.aspx?i=j)
- [Sysmon Event IDs](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon#events)
- [Cisco ASA Event IDs](https://www.cisco.com/c/en/us/td/docs/security/asa/syslog/b_syslog.html)
- [Palo Alto PAN-OS Log Fields](https://docs.paloaltonetworks.com/pan-os/10-1/pan-os-admin/monitoring/use-syslog-for-monitoring/syslog-field-descriptions)
- [FortiGate FortiOS Log Types and Subtypes](https://docs.fortinet.com/document/fortigate/7.6.1/fortios-log-message-reference/160372/list-of-log-types-and-subtypes) and [FortiGate FortiOS Log Fields](https://docs.fortinet.com/document/fortigate/7.6.1/fortios-log-message-reference/357866/log-message-fields)
- [Microsoft Defender Event IDs](https://learn.microsoft.com/en-us/defender-endpoint/troubleshoot-microsoft-defender-antivirus)
- [Antivirus Cheatsheet from Nextron Systems](https://www.nextron-systems.com/?s=antivirus)

### Resources
- [MITRE ATT&CK®](https://attack.mitre.org/) - MITRE ATT&CK knowledge base of adversary tactics and techniques.
- [DeTT&CT](https://github.com/rabobank-cdc/DeTTECT/) - DeTT&CT aims to assist blue teams in using ATT&CK to score and compare data log source quality, visibility coverage, detection coverage and threat actor behaviors.
- [Active Directory Security (adsecurity.org)](https://adsecurity.org/?page_id=4031) - Page dedicated to Active Directory security. Includes attack descriptions and detection recommendations.
- [Zen of Security Rules | Justin Ibarra](https://br0k3nlab.com/resources/zen-of-security-rules/) - 19 rules for developing detection rules.
- [Uncoder IO](https://uncoder.io/) - Detection logic query converter.
- [Alerting and Detection Strategies (ADS) Framework | Palantir](https://github.com/palantir/alerting-detection-strategy-framework#alerting-and-detection-strategies-framework)- A structured approach to designing and documenting effective detection methodologies.
- [Detection Engineering Maturity Matrix | Kyle Bailey](https://detectionengineering.io/) - Aims to help the community better measure the capabilities and maturity of their detection function.
- [Detection Engineering Maturity (DML) Model | Ryan Stillions](https://ryanstillions.blogspot.com/2014/04/the-dml-model_21.html) - A tool for assessing an organization’s detection engineering capabilities and maturity levels.
- [MaGMa Use Case Framework](https://www.betaalvereniging.nl/wp-content/uploads/FI-ISAC-use-case-framework-verkorte-versie.pdf) - Methodology for defining and managing threat detection use cases.

### Online Tools
 - [Regex101](https://regex101.com/)
 - [CyberChef](https://gchq.github.io/CyberChef/)
 - [JSON Formatter](https://jsonformatter.curiousconcept.com/#)

### Blogs
- [FalconForce Blog](https://falconforce.nl/blogs/)
- [Red Canary Blog](https://redcanary.com/blog) and [Red Canary Blog Threat Detection Category](https://redcanary.com/blog/?topic=threat-detection)
- [Elastic Security Labs Blog](https://www.elastic.co/security-labs) and [Elastic Security Labs Blog Detection Category](https://www.elastic.co/security-labs/topics/detection-science). Also everything [Samir Bousseaden](https://www.elastic.co/security-labs/author/samir-bousseaden).
- [SpecterOps Blog](https://specterops.io/blog) and [SpecterOps on Detection series | Jared Atkinson](https://specterops.io/blog/?_sf_s=on%20detection)
- [Detection Engineering Weekly](https://www.detectionengineering.net/)
- [Detect.fyi](https://detect.fyi/) - Collection of good detection engineering articles.
- [Detections.xyz](https://detections.xyz/) - Collection of good detection engineering articles.
- [Detections Digest](https://detections-digest.rulecheck.io/) - A newsletter with many popular detection content sources.

### Good Reads


### Podcasts
- [Detection Challenging Paradigms | SpecterOps](https://www.dcppodcast.com/all-episodes)
- [Darknet Diaries](https://darknetdiaries.com/) - Not detection engineering focused but one of my favorites.

### Books
 - [Automating Security Detection Engineering: A hands-on guide to implementing Detection as Code](https://www.packtpub.com/en-no/product/automating-security-detection-engineering-9781837636419)
 - [Practical Threat Detection Engineering: A hands-on guide to planning, developing, and validating detection capabilities](https://www.packtpub.com/en-sg/product/practical-threat-detection-engineering-9781801076715)
 - [Malware Analysis and Detection Engineering: A Comprehensive Approach to Detect and Analyze Modern Malware](https://link.springer.com/book/10.1007/978-1-4842-6193-4)

### Trainings
- [XINTRA Attacking and Defending Azure & M365](https://www.xintra.org/training/course/1-attacking-and-defending-azure-m365)
- [Specter Ops Adversary Tactics: Detection](https://specterops.io/training/adversary-tactics-detection/)
- [FalconForce Advanced Detection Engineering in the Enterprise training](https://falconforce.nl/services/training/advanced-detection-engineering-training/)
- [TCM Security Detection Engineering for Beginners](https://academy.tcm-sec.com/p/detection-engineering-for-beginners)

### Twitter/X
- [@sigma_hq](https://x.com/sigma_hq)
- [@cyb3rops](https://x.com/cyb3rops)
- [@frack113](https://x.com/frack113)
- [@SBousseaden](https://x.com/SBousseaden)
- [@SecurityAura](https://x.com/SecurityAura)
- [@Oddvarmoe](https://x.com/Oddvarmoe)
- [@jaredcatkinson](https://x.com/jaredcatkinson)
- [Awesome Detection List](https://x.com/i/lists/952735755838738432)

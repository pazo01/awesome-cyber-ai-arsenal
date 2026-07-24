<div align="center">





 <img src="assets/logo.png" alt="Awesome Cyber AI Arsenal" width="450">





# ⚔️ Awesome Cyber & AI Arsenal

**A curated, battle‑tested collection of offensive, defensive and AI‑powered security tools.**

Everything is split into **🔴 Offensive (Red Team)**, **🔵 Defensive (Blue Team)** and **🤖 AI / LLM Security**, with sane sub‑categories so you can find the right tool in seconds.

![Tools](https://img.shields.io/badge/tools-250+-red)
![Categories](https://img.shields.io/badge/categories-30+-blue)
![AI%20Security](https://img.shields.io/badge/AI%20Security-included-8A2BE2)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

</div>

---

> [!WARNING]
> **For authorized security testing and education only.** Every tool listed here must be used **only** against systems you own or have **explicit written permission** to test. Unauthorized access is illegal. See the [Disclaimer](#-disclaimer).

---

## 📑 Table of Contents

- [🔴 Offensive Security (Red Team)](#-offensive-security-red-team)
  - [Reconnaissance — Subdomain / DNS / ASN](#reconnaissance--subdomain--dns--asn)
  - [Port Scanning & Network](#port-scanning--network)
  - [HTTP Probing / Crawling / Content Discovery](#http-probing--crawling--content-discovery)
  - [JavaScript Analysis & Parameter Discovery](#javascript-analysis--parameter-discovery)
  - [Fuzzing](#fuzzing)
  - [Vulnerability Scanners (Web / App)](#vulnerability-scanners-web--app)
  - [Injection — SQL / NoSQL / Command / SSTI / LFI](#injection--sql--nosql--command--ssti--lfi)
  - [XSS](#xss)
  - [Prototype Pollution / Open Redirect / CRLF](#prototype-pollution--open-redirect--crlf)
  - [SSRF / Request Smuggling / Web Cache](#ssrf--request-smuggling--web-cache)
  - [GraphQL / API](#graphql--api)
  - [CMS / WordPress](#cms--wordpress)
  - [Auth / JWT / Password Cracking](#auth--jwt--password-cracking)
  - [Deserialization / RMI / XXE](#deserialization--rmi--xxe)
  - [403 / 401 Bypass](#403--401-bypass)
  - [C2 / Exploitation / Post-Exploitation](#c2--exploitation--post-exploitation)
  - [Out-of-Band (OOB) Interaction](#out-of-band-oob-interaction)
- [🔵 Defensive Security (Blue Team / DevSecOps)](#-defensive-security-blue-team--devsecops)
  - [SAST / Code Analysis](#sast--code-analysis)
  - [Dependency / Container / Supply-Chain Scanning](#dependency--container--supply-chain-scanning)
  - [Secrets Detection](#secrets-detection)
  - [Network Vulnerability Management](#network-vulnerability-management)
  - [TLS / SSL Testing](#tls--ssl-testing)
  - [Hardening / Sanitization](#hardening--sanitization)
  - [Adversary Emulation / Purple Team](#adversary-emulation--purple-team)
- [🤖 AI / LLM Security](#-ai--llm-security)
  - [AI-Powered Offensive Agents](#ai-powered-offensive-agents)
  - [LLM Red Teaming & Vulnerability Scanning](#llm-red-teaming--vulnerability-scanning)
  - [LLM Defense / Guardrails](#llm-defense--guardrails)
  - [Uncensored / Local Models](#uncensored--local-models)
  - [AI Security Frameworks & Knowledge](#ai-security-frameworks--knowledge)
- [🕵️ OSINT](#️-osint)
- [🧰 Utilities / Proxies / HTTP Clients](#-utilities--proxies--http-clients)
- [📚 Wordlists & Payloads](#-wordlists--payloads)
- [📖 Frameworks, References & Learning](#-frameworks-references--learning)
- [🤝 Contributing](#-contributing)
- [⚠️ Disclaimer](#-disclaimer)
- [📄 License](#-license)

---

## 🔴 Offensive Security (Red Team)

### Reconnaissance — Subdomain / DNS / ASN

| Tool | Description |
| --- | --- |
| [subfinder](https://github.com/projectdiscovery/subfinder) | Fast passive subdomain enumeration. |
| [Amass](https://github.com/OWASP/Amass) | In-depth attack-surface mapping and asset discovery (OWASP). |
| [Sublist3r](https://github.com/aboul3la/Sublist3r) | Subdomain enumeration using search engines. |
| [OneForAll](https://github.com/shmilylty/OneForAll) | Powerful all-in-one subdomain collection tool. |
| [findomain](https://github.com/Edu4rdSHL/findomain) | Cross-platform subdomain finder. |
| [puredns](https://github.com/d3mondev/puredns) | Fast DNS resolver + subdomain bruteforce with wildcard filtering. |
| [shuffledns](https://github.com/projectdiscovery/shuffledns) | massdns wrapper for bruteforce/resolve subdomains. |
| [dnsx](https://github.com/projectdiscovery/dnsx) | Fast, multi-purpose DNS toolkit. |
| [zdns](https://github.com/zmap/zdns) | Fast CLI DNS lookup at scale. |
| [altdns](https://github.com/infosec-au/altdns) | Subdomain permutation / alteration generator. |
| [shosubgo](https://github.com/incogbyte/shosubgo) | Grab subdomains from the Shodan API. |
| [knock](https://github.com/guelfoweb/knock) | Subdomain enumeration via wordlist. |
| [Sudomy](https://github.com/screetsec/Sudomy) | Subdomain enumeration & analysis framework. |
| [scilla](https://github.com/edoardottt/scilla) | Information-gathering (DNS/subdomain/port/dir) tool. |
| [hakrevdns](https://github.com/hakluke/hakrevdns) | Reverse DNS lookups from a list of IPs. |
| [asnmap](https://github.com/projectdiscovery/asnmap) | Map network ranges using ASN information. |
| [DNSDumpster](https://dnsdumpster.com) | Online DNS recon & research service. |
| [tlsx](https://github.com/projectdiscovery/tlsx) | TLS grabber for gathering data from certificates. |
| [HostHunter](https://github.com/SpiderLabs/HostHunter) | Discover hostnames from IP addresses. |
| [subjack](https://github.com/haccer/subjack) | Subdomain takeover detection. |
| [can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz) | Reference of services vulnerable to subdomain takeover. |
| [bbot](https://github.com/blacklanternsecurity/bbot) | Recursive OSINT/recon "BEE-bot" scanner. |
| [reconftw](https://github.com/six2dez/reconftw) | End-to-end automated recon framework. |
| [reNgine](https://github.com/yogeshojha/rengine) | Web recon engine with a UI and pipelines. |
| [Chaos](https://chaos.projectdiscovery.io) | Public DNS/subdomain dataset by ProjectDiscovery. |
| [cloudlist](https://github.com/projectdiscovery/cloudlist) | List assets/hostnames from cloud providers. |
| [uncover](https://github.com/projectdiscovery/uncover) | Query Shodan/Censys/Fofa for exposed hosts. |
| [csprecon](https://github.com/edoardottt/csprecon) | Discover domains from Content-Security-Policy headers. |
| [favirecon](https://github.com/edoardottt/favirecon) | Fingerprint tech via favicon hashes. |

### Port Scanning & Network

| Tool | Description |
| --- | --- |
| [naabu](https://github.com/projectdiscovery/naabu) | Fast SYN/CONNECT port scanner. |
| [masscan](https://github.com/robertdavidgraham/masscan) | Internet-scale TCP port scanner. |
| [RustScan](https://github.com/bee-san/RustScan) | Ultra-fast port scanner that pipes into Nmap. |
| [Smap](https://github.com/s0md3v/smap) | Nmap-compatible scanner powered by Shodan (no packets sent). |
| [proxify](https://github.com/projectdiscovery/proxify) | Swiss-army-knife HTTP/HTTPS proxy for capture & tampering. |
| [axiom](https://github.com/pry0cc/axiom) | Dynamic distributed-scanning infrastructure ("attack fleet"). |
| [ax](https://github.com/attacksurge/ax) | Maintained fork/evolution of Axiom for distributed scanning. |
| [nmap](https://github.com/nmap/nmap) | Network Discovery, Scanning, and Security Auditing. |       
| Netcat | The classic TCP/IP "swiss-army knife" for reading/writing across connections. |

### HTTP Probing / Crawling / Content Discovery

| Tool | Description |
| --- | --- |
| [httpx](https://github.com/projectdiscovery/httpx) | Fast, multi-purpose HTTP toolkit / prober. |
| [httprobe](https://github.com/tomnomnom/httprobe) | Probe a list of hosts for working HTTP/HTTPS. |
| [meg](https://github.com/tomnomnom/meg) | Fetch many paths from many hosts without hammering them. |
| [gowitness](https://github.com/sensepost/gowitness) | Screenshot websites at scale. |
| [crawlergo](https://github.com/Qianlitp/crawlergo) | Headless-Chrome crawler that collects URLs & forms. |
| [cariddi](https://github.com/edoardottt/cariddi) | Crawl + extract endpoints/params/secrets from JS in one shot. |
| [Photon](https://github.com/s0md3v/Photon) | Fast crawler with parameter & data extraction. |
| [katana](https://github.com/projectdiscovery/katana) | Next-gen crawler built for offensive security. |
| [dirsearch](https://github.com/maurosoria/dirsearch) | Web path/content brute-forcer. |
| [feroxbuster](https://github.com/epi052/feroxbuster) | Fast recursive content discovery (Rust). |
| [DirDar](https://github.com/M4DM0e/DirDar) | Directory brute-force & hidden-path discovery. |
| [gau](https://github.com/lc/gau) | Fetch known URLs from Wayback/OTX/Common Crawl. |
| [waymore](https://github.com/xnl-h4ck3r/waymore) | More URLs from more archive sources than gau. |
| [xurlfind3r](https://github.com/hueristiq/xurlfind3r) | Passive URL discovery from online archives. |
| [uro](https://github.com/s0md3v/uro) | De-duplicate and clean lists of near-duplicate URLs. |
| [qsreplace](https://github.com/tomnomnom/qsreplace) | Replace query-string values (great for payload injection). |
| [VHostScan](https://github.com/codingo/VHostScan) | Virtual-host discovery scanner. |
| [hakrawler](https://github.com/hakluke/hakrawler) | Simple, fast web crawler for quick scoping. |
| [gospider](https://github.com/jaeles-project/gospider) | Fast web spider written in Go. |

### JavaScript Analysis & Parameter Discovery

| Tool | Description |
| --- | --- |
| [LinkFinder](https://github.com/GerbenJavado/LinkFinder) | Discover endpoints inside JavaScript files. |
| [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder) | Extract endpoints/links from JS, files & burp exports. |
| [getJS](https://github.com/003random/getJS) | Extract all JavaScript file URLs from a page. |
| [subjs](https://github.com/lc/subjs) | Fetch JavaScript file references from a list of URLs. |
| [jsluice](https://github.com/BishopFox/jsluice) | Extract URLs, paths & secrets from JavaScript (BishopFox). |
| [Arjun](https://github.com/s0md3v/Arjun) | HTTP hidden-parameter discovery. |
| [ParamSpider](https://github.com/devanshbatham/ParamSpider) | Mine parameters from web archives. |
| [x8](https://github.com/Sh1Yo/x8) | Blazing-fast hidden parameter discovery (Rust). |
| [apkleaks](https://github.com/dwisiswant0/apkleaks) | Scan APKs for URIs, endpoints & secrets. |

### Fuzzing

| Tool | Description |
| --- | --- |
| [ffuf](https://github.com/ffuf/ffuf) | Fast web fuzzer (dir, param, vhost, more). |
| [wfuzz](https://github.com/xmendez/wfuzz) | Flexible web application fuzzer. |
| [REcollapse](https://github.com/0xacb/recollapse) | Generate payloads to fuzz normalization/validation logic. |

### Vulnerability Scanners (Web / App)

| Tool | Description |
| --- | --- |
| [nuclei](https://github.com/projectdiscovery/nuclei) | Template-based, fast, community-driven vulnerability scanner. |
| [nuclei-templates](https://github.com/projectdiscovery/nuclei-templates) | Official community templates for Nuclei. |
| [nuclei-wordfence-cve](https://github.com/topscoder/nuclei-wordfence-cve) | Nuclei templates generated from Wordfence CVEs. |
| [cent](https://github.com/xm1k3/cent) | Aggregate community Nuclei templates. |
| [jaeles](https://github.com/jaeles-project/jaeles) | Powerful, flexible web-app scanning framework. |
| [nikto](https://github.com/sullo/nikto) | Classic web-server scanner. |
| [wapiti](https://github.com/wapiti-scanner/wapiti) | Black-box web-app vulnerability scanner. |
| [scan4all](https://github.com/hktalent/scan4all) | All-in-one scanning framework (recon + vuln). |
| [V3n0M-Scanner](https://github.com/v3n0m-Scanner/V3n0M-Scanner) | Pentest scanner (Dorks/SQLi/XSS/LFI…). |
| [VULNX](https://github.com/projectdiscovery/vulnx) | CVE-focused vulnerability intelligence/scanner. |
| [ZAP](https://github.com/zaproxy/zaproxy) | OWASP Zed Attack Proxy — full web-app scanner. |
| [Nettacker](https://github.com/OWASP/Nettacker) | Automated pentest & information-gathering framework (OWASP). |
| [Artemis](https://github.com/CERT-Polska/Artemis) | Modular scanner that assesses many hosts (CERT-PL). |
| [Sn1per](https://github.com/1N3/Sn1per) | Automated recon & attack-surface scanner. |
| [BugBountyScanner](https://github.com/chvancooten/BugBountyScanner) | Recon/scan automation designed to run over multiple days. |
| [webanalyze](https://github.com/rverton/webanalyze) | Technology detection (Wappalyzer-style) at scale. |
| [WAD](https://github.com/CERN-CERT/WAD) | Web application detector (fingerprinting). |
| [RedTeam-Tools](https://github.com/A-poc/RedTeam-Tools) | Curated set of red-team tools & resources. |
| [Aghast](https://github.com/owasp-aghast/aghast) | OWASP scanner for common web issues. |

### Injection — SQL / NoSQL / Command / SSTI / LFI

| Tool | Description |
| --- | --- |
| [sqlmap](https://github.com/sqlmapproject/sqlmap) | Automatic SQL-injection detection & exploitation. |
| [ghauri](https://github.com/r0oth3x49/ghauri) | Fast, smart SQL-injection tool. |
| [DSSS](https://github.com/stamparm/DSSS) | Damn Small SQLi Scanner (<100 lines). |
| [NoSQLMap](https://github.com/codingo/NoSQLMap) | Automated NoSQL / MongoDB injection. |
| [commix](https://github.com/commixproject/commix) | Automated command-injection exploitation. |
| [SSTImap](https://github.com/vladko312/SSTImap) | Server-Side Template Injection detection & exploitation. |
| [tplmap](https://github.com/epinna/tplmap) | Classic SSTI / code-injection exploitation. |
| [LFISuite](https://github.com/D35m0nd142/LFISuite) | Local File Inclusion scanner & exploiter. |

### XSS

| Tool | Description |
| --- | --- |
| [dalfox](https://github.com/hahwul/dalfox) | Fast, powerful XSS scanner & param analyzer. |
| [XSStrike](https://github.com/s0md3v/XSStrike) | Advanced XSS detection with payload generation. |
| [xsser](https://github.com/epsylon/xsser) | Automated framework to detect & exploit XSS. |
| [xsssniper](https://github.com/gbrindisi/xsssniper) | Automatic XSS discovery tool. |
| [XssPy](https://github.com/faizann24/XssPy) | Python XSS scanner that walks subdomains & params. |
| [toxssin](https://github.com/t3l3machus/toxssin) | XSS exploitation command-and-control server. |
| [ezXSS](https://github.com/ssl/ezXSS) | Easy blind-XSS testing & payload management. |
| [LOXS](https://github.com/coffinxp/loxs) | Multi-vuln scanner (LFI/OR/SQLi/XSS/CRLF). |
| [DOMLogger++](https://github.com/kevin-mizu/domloggerpp) | Browser ext to monitor DOM sinks for XSS research. |
| [postMessage-tracker](https://github.com/fransr/postMessage-tracker) | Track postMessage usage for client-side bugs. |
| [weaponised-XSS-payloads](https://github.com/hakluke/weaponised-XSS-payloads) | Collection of impactful XSS payloads. |

### Prototype Pollution / Open Redirect / CRLF

| Tool | Description |
| --- | --- |
| [pphack](https://github.com/edoardottt/pphack) | Client-side prototype-pollution scanner. |
| [ppmap](https://github.com/kleiton0x00/ppmap) | Automated prototype-pollution scanner. |
| [OpenRedireX](https://github.com/devanshbatham/OpenRedireX) | Fuzzer for open-redirect vulnerabilities. |
| [crlfuzz](https://github.com/dwisiswant0/crlfuzz) | Fast CRLF-injection scanner. |

### SSRF / Request Smuggling / Web Cache

| Tool | Description |
| --- | --- |
| [SSRFmap](https://github.com/swisskyrepo/SSRFmap) | Automatic SSRF fuzzer & exploitation. |
| [Gopherus](https://github.com/tarunkant/Gopherus) | Generate gopher payloads for SSRF exploitation. |
| [http-request-smuggling](https://github.com/anshumanpattnaik/http-request-smuggling) | HTTP request-smuggling detection tooling. |
| [http2smugl](https://github.com/neex/http2smugl) | HTTP/2 request-smuggling detection. |
| [smuggler](https://github.com/defparam/smuggler) | HTTP request-smuggling / desync tester. |
| [Web-Cache-Vulnerability-Scanner](https://github.com/Hackmanit/Web-Cache-Vulnerability-Scanner) | Detect web-cache poisoning/deception. |

### GraphQL / API

| Tool | Description |
| --- | --- |
| [graphw00f](https://github.com/dolevf/graphw00f) | GraphQL server fingerprinting. |
| [GraphQLmap](https://github.com/swisskyrepo/GraphQLmap) | Interactive GraphQL pentest / exploitation. |
| [graphql-cop](https://github.com/dolevf/graphql-cop) | Security auditor for GraphQL endpoints. |
| [graphql-voyager](https://github.com/APIs-guru/graphql-voyager) | Visualize a GraphQL API as an interactive graph. |
| [Clairvoyance](https://github.com/nikitastupin/clairvoyance) | Recover GraphQL schema even with introspection off. |
| [CrackQL](https://github.com/nicholasaleks/CrackQL) | GraphQL password/brute-force & fuzzing. |
| [noir](https://github.com/noir-cr/noir) | Attack-surface detector from source code (API endpoints). |

### CMS / WordPress

| Tool | Description |
| --- | --- |
| [wpscan](https://github.com/wpscanteam/wpscan) | WordPress vulnerability scanner. |
| [CMSmap](https://github.com/dionach/CMSmap) | Multi-CMS scanner (WP/Joomla/Drupal). |

### Auth / JWT / Password Cracking

| Tool | Description |
| --- | --- |
| [jwt-hack](https://github.com/hahwul/jwt-hack) | JWT attack toolkit (crack, tamper, encode). |
| [jwt-cracker](https://github.com/lmammino/jwt-cracker) | Brute-force HS256 JWT secrets. |
| [jwt_tool](https://github.com/ticarpi/jwt_tool) | Analyze, tamper & attack JSON Web Tokens. |
| [hashcat](https://github.com/hashcat/hashcat) | World's fastest GPU password cracker. |
| [thc-hydra](https://github.com/vanhauser-thc/thc-hydra) | Fast network login brute-forcer. |

### Deserialization / RMI / XXE

| Tool | Description |
| --- | --- |
| [ysoserial](https://github.com/frohoff/ysoserial) | Generate Java deserialization payloads. |
| [ysoserial.net](https://github.com/pwntester/ysoserial.net) | .NET deserialization payload generator. |
| [SerializationDumper](https://github.com/NickstaDB/SerializationDumper) | Dump Java serialization streams in human-readable form. |
| [BaRMIe](https://github.com/NickstaDB/BaRMIe) | Java RMI enumeration & attack tool. |
| [xxeserv](https://github.com/staaldraad/xxeserv) | Mini web server for XXE OOB exfiltration. |

### 403 / 401 Bypass

| Tool | Description |
| --- | --- |
| [dontgo403](https://github.com/devploit/dontgo403) | Bypass 40x access-control restrictions. |

### C2 / Exploitation / Post-Exploitation

| Tool | Description |
| --- | --- |
| [NetExec](https://github.com/Pennyw0rth/NetExec) | Network/AD swiss-army knife (successor to CrackMapExec). |
| [BeEF](https://github.com/beefproject/beef) | Browser Exploitation Framework. |
| [pwncat](https://github.com/calebstewart/pwncat) | Post-exploitation platform / reverse-shell handler. |
| [CALDERA](https://github.com/mitre/caldera) | Automated adversary-emulation platform (MITRE). |
| [evilginx2](https://github.com/kgretzky/evilginx2) | MITM phishing framework for 2FA session hijacking. |
| [reverse-shell-generator](https://github.com/0dayCTF/reverse-shell-generator) | Generate reverse-shell one-liners quickly. |
| [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) | PowerShell post-exploitation modules. |
| [Findsploit](https://github.com/1N3/Findsploit) | Instantly find exploits locally & online. |
| [PoC-in-GitHub](https://github.com/nomi-sec/PoC-in-GitHub) | Auto-collected CVE proof-of-concepts from GitHub. |

### Out-of-Band (OOB) Interaction

| Tool | Description |
| --- | --- |
| [interactsh](https://github.com/projectdiscovery/interactsh) | OOB interaction-gathering server & client. |
| [dnsobserver](https://github.com/allyomalley/dnsobserver) | Helper DNS server to detect OOB/DNS interactions. |

---

## 🔵 Defensive Security (Blue Team / DevSecOps)

### SAST / Code Analysis

| Tool | Description |
| --- | --- |
| [semgrep](https://github.com/semgrep/semgrep) | Fast, multi-language static analysis with custom rules. |

### Dependency / Container / Supply-Chain Scanning

| Tool | Description |
| --- | --- |
| [trivy](https://github.com/aquasecurity/trivy) | All-in-one scanner for containers, IaC, deps & secrets. |
| [osv-scanner](https://github.com/google/osv-scanner) | Match dependencies against the OSV vulnerability DB (Google). |

### Secrets Detection

| Tool | Description |
| --- | --- |
| [trufflehog](https://github.com/trufflesecurity/trufflehog) | Find & verify leaked credentials in code/history. |
| [gitleaks](https://github.com/gitleaks/gitleaks) | Detect hardcoded secrets in git repos. |
| [S3Scanner](https://github.com/sa7mon/S3Scanner) | Find open/misconfigured S3 buckets. |

### Network Vulnerability Management

| Tool | Description |
| --- | --- |
| [openvas-scanner](https://github.com/greenbone/openvas-scanner) | Full-featured network vulnerability scanner (Greenbone). |

### TLS / SSL Testing

| Tool | Description |
| --- | --- |
| [testssl.sh](https://github.com/drwetter/testssl.sh) | Check a server's TLS/SSL config, ciphers & flaws. |
| [DeepViolet](https://github.com/spoofzu/DeepViolet) | TLS/SSL scanning API & tool (Java). |

### Hardening / Sanitization

| Tool | Description |
| --- | --- |
| [DOMPurify](https://github.com/cure53/DOMPurify) | XSS sanitizer for HTML/DOM (defensive). |

### Adversary Emulation / Purple Team

| Tool | Description |
| --- | --- |
| [CALDERA](https://github.com/mitre/caldera) | Automated adversary-emulation to validate detections (MITRE). |
| [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) | Useful for building & testing blue-team detections. |

---

## 🤖 AI / LLM Security

> The core reason this repo exists: security tooling powered by (and targeting) AI/LLMs. Split into **offensive agents**, **LLM red teaming**, **defensive guardrails**, **local models** and **knowledge**.

### AI-Powered Offensive Agents

| Tool | Description |
| --- | --- |
| [strix](https://github.com/usestrix/strix) | Autonomous AI agents that pentest your apps. |
| [PentestGPT](https://github.com/GreyDGL/PentestGPT) | LLM-driven reasoning layer that guides pentests. |
| [CAI (Cybersecurity AI)](https://github.com/aliasrobotics/cai) | Framework for building AI agents for offensive/defensive security. |
| [hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) | Research framework for LLM-powered autonomous hacking. |
| [Nebula](https://github.com/berylliumsec/nebula) | AI-assisted pentest assistant that suggests & runs commands. |
| [hermes-agent](https://github.com/NousResearch/Hermes-Function-Calling) | Function-calling agent scaffolding (Nous Research). |
| [Colibri](https://github.com/JustVugg/colibri) | Lightweight AI security agent. |

### LLM Red Teaming & Vulnerability Scanning

| Tool | Description |
| --- | --- |
| [garak](https://github.com/NVIDIA/garak) | LLM vulnerability scanner (prompt injection, jailbreaks, leakage) — NVIDIA. |
| [PyRIT](https://github.com/Azure/PyRIT) | Python Risk Identification Toolkit for generative AI (Microsoft). |
| [promptfoo](https://github.com/promptfoo/promptfoo) | Test, red-team & evaluate LLM apps (50+ vuln types). |
| [deepteam](https://github.com/confident-ai/deepteam) | LLM red-teaming framework mapped to OWASP LLM Top 10. |
| [agentic_security](https://github.com/msoedov/agentic_security) | Open-source LLM/agent vulnerability scanner. |
| [agentic-radar](https://github.com/splx-ai/agentic-radar) | Static analysis of agent workflows for excessive-agency risk. |
| [Garak probes / MITRE ATLAS](https://atlas.mitre.org/) | Adversarial-threat landscape for AI systems. |

### LLM Defense / Guardrails

| Tool | Description |
| --- | --- |
| [LLM Guard](https://github.com/protectai/llm-guard) | Security toolkit for LLM interactions (input/output filtering). |
| [Rebuff](https://github.com/protectai/rebuff) | Prompt-injection detector with multi-layer defense. |
| [Vigil](https://github.com/deadbits/vigil-llm) | Detect prompt injections, jailbreaks & risky inputs. |
| [Giskard](https://github.com/Giskard-AI/giskard) | Test & scan ML/LLM models for vulnerabilities & bias. |

### Uncensored / Local Models

> For offline/private research where cloud models refuse security tasks. **Use responsibly and legally.**

| Resource | Description |
| --- | --- |
| [heretic](https://github.com/p-e-w/heretic) | Automatic "decensoring" of transformer models. |
| [Huihui-GLM abliterated](https://huggingface.co/huihui-ai) | Abliterated / uncensored GLM model weights (GGUF). |

### AI Security Frameworks & Knowledge

| Resource | Description |
| --- | --- |
| [MITRE ATLAS](https://atlas.mitre.org/) | Adversarial threat matrix for AI/ML systems. |
| [OWASP Top 10 for LLM Apps](https://genai.owasp.org/) | The standard risk list for LLM applications. |
| [Local LLMs for pentesting (r/Pentesting)](https://www.reddit.com/r/Pentesting/comments/1snwx8p/local_llms_for_penetration_testing_realworld/) | Community discussion on real-world local-LLM pentest use. |

---

## 🕵️ OSINT

| Tool | Description |
| --- | --- |
| [SpiderFoot](https://github.com/smicallef/spiderfoot) | Automated OSINT collection & attack-surface mapping. |
| [recon-ng](https://github.com/lanmaster53/recon-ng) | Full-featured web recon framework (Metasploit-style). |
| [OSINT-Mapping-Tool](https://github.com/anonymousRAID/OSINT-Mapping-Tool) | Map & visualize OSINT relationships. |
| [IntelOwl](https://github.com/intelowlproject/IntelOwl) | Threat-intelligence data at scale via one API. |
| [pagodo](https://github.com/opsdisk/pagodo) | Passive Google-dorking automation. |
| [ditto](https://github.com/evilsocket/ditto) | Detect typosquatting / lookalike domains. |
| [Maigret](https://github.com/soxoj/maigret) | Collect a person's accounts across thousands of sites. |
| [Osintgram](https://github.com/Datalux/Osintgram) | OSINT toolkit for Instagram. |
| [GhostTrack](https://github.com/HunxByts/GhostTrack) | Track location / phone / username info. |
| [TraceLabs OSINT VM](https://github.com/tracelabs/tlosint-vm) | Preconfigured OSINT investigation environment. |
| [Metabigor](https://github.com/j3ssie/metabigor) | OSINT without API keys (ASN, IP, org). |
| [gitGraber](https://github.com/hisxo/gitGraber) | Monitor GitHub for leaked secrets/tokens. |
| [Maltego](https://www.maltego.com/) | Link-analysis & graph OSINT platform. |
| [Hunchly](https://hunch.ly/) | Web-capture tool for OSINT investigations. |
| [IntelX](https://intelx.io/) | Search engine & data archive for OSINT. |

---

## 🧰 Utilities / Proxies / HTTP Clients

| Tool | Description |
| --- | --- |
| [mitmproxy](https://github.com/mitmproxy/mitmproxy) | Interactive HTTPS intercepting proxy. |
| [hetty](https://github.com/dstotijn/hetty) | Open-source HTTP toolkit / Burp alternative. |
| [CyberChef](https://github.com/gchq/CyberChef) | The "cyber swiss-army knife" for encoding/crypto/data (GCHQ). |
| [curl](https://github.com/curl/curl) | The universal command-line HTTP client. |
| [httpie](https://github.com/httpie/httpie) | Human-friendly CLI HTTP client. |
| [hurl](https://github.com/Orange-OpenSource/hurl) | Run & test HTTP requests in plain text. |
| [Atlas](https://github.com/m4ll0k/Atlas) | Quick SQLmap tamper-script suggester. |
| [fzf](https://github.com/junegunn/fzf) | Command-line fuzzy finder. |
| [pet](https://github.com/knqyf263/pet) | Simple command-line snippet manager. |
| [pentest-tools](https://github.com/gwen001/pentest-tools) | Collection of handy pentest scripts (gwen001). |
| [Hack-Tools](https://github.com/LasCC/Hack-Tools) | All-in-one red-team browser extension. |
| [Redcloud](https://github.com/khast3x/Redcloud) | Deploy a full red-team attack infrastructure via UI. |
| [grex](https://github.com/pemistahl/grex) | Generate regexes from example inputs. |

---

## 📚 Wordlists & Payloads

| Resource | Description |
| --- | --- |
| [SecLists](https://github.com/danielmiessler/SecLists) | The go-to collection of wordlists for security testing. |
| [Assetnote Wordlists](https://github.com/assetnote/wordlists) | High-quality wordlists built from internet-wide data. |
| [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) | Payloads & bypasses for every web vuln class. |
| [IntruderPayloads](https://github.com/1N3/IntruderPayloads) | Burp Intruder payloads, fuzz lists & wordlists. |
| [CeWL](https://github.com/digininja/CeWL) | Generate custom wordlists by spidering a target. |
| [COOK](https://github.com/glitchedgitz/cook) | Powerful wordlist generator & permutation engine. |
| [jsfuck](https://github.com/aemkei/jsfuck) | Write JS using only 6 characters (filter bypass). |
| [OCD Mindmaps](https://github.com/Orange-Cyberdefense/ocd-mindmaps) | Pentest / Active Directory attack mindmaps. |

---

## 📖 Frameworks, References & Learning

| Resource | Description |
| --- | --- |
| [MITRE ATT&CK](https://attack.mitre.org/) | Global knowledge base of adversary tactics & techniques. |
| [OWASP](https://owasp.org/) | Foundation for web/app security standards & projects. |
| [PortSwigger Web Security Academy](https://portswigger.net/web-security/all-topics) | Free, hands-on web-security training. |
| [ProjectDiscovery](https://github.com/projectdiscovery) | Home of subfinder/httpx/nuclei & the recon ecosystem. |
| [Awesome-Cybersecurity-Handbooks](https://github.com/0xsyr0/Awesome-Cybersecurity-Handbooks) | Huge handbook of techniques, tools & notes. |
| [reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | Reverse-engineering & pentest skill notes. |
| [Wiz Bug Bounty Masterclass](https://www.wiz.io/bug-bounty-masterclass/reconnaissance/overview) | Free recon/bug-bounty masterclass. |
| [Exploit-DB](https://www.exploit-db.com/) | The classic exploit & shellcode database. |
| [Google Hacking Database](https://www.exploit-db.com/google-hacking-database) | Curated Google dorks for exposure discovery. |
| [cybersecurity-help VDB](https://www.cybersecurity-help.cz/vdb/) | CVE / 0-day vulnerability database. |
| [InfoSec Write-ups](https://infosecwriteups.com/) | Community bug-bounty & security write-ups. |

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

In short: open a Pull Request that adds the tool to the **correct category**, keep the one-line description factual, make sure the link works, and keep entries alphabetical-ish within a section. New categories are fine when something genuinely doesn't fit.

---

## ⚠️ Disclaimer

This repository is provided for **educational purposes and authorized security testing only**. The tools listed are created and maintained by their respective authors. Using any of these tools against systems, networks, or applications **without explicit prior authorization is illegal** and may result in criminal and civil liability. The maintainers of this list assume **no responsibility** for misuse. Always act ethically and within the law.

---

## 📄 License

Distributed under the [MIT License](LICENSE). The listed tools remain the property of their respective owners and are governed by their own licenses.

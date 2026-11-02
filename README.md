# secbyte-network-mapping-burp-suite-metasploit-fundamentals-ctf-labs
A practical collection of cybersecurity CTF labs covering network discovery (Nmap topology mapping, advanced service scanning), web application proxy tools (Burp Suite Proxy, Repeater, Intruder, Decoder, Comparer, Scanner), and Metasploit Framework execution (session handling, multi-stage payloads).
# Network Mapping (Nmap), Burp Suite Web Penetration Testing & Metasploit Exploitation CTF Labs

Welcome to the **Network Mapping (Nmap), Burp Suite Web Penetration Testing & Metasploit Exploitation CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on foundational reconnaissance, proxy-based HTTP manipulation, and exploitation execution frameworks—spanning **Network Reconnaissance, Topology & Advanced Nmap (LAN discovery, service mapping under pressure, active network mapping)**, **Burp Suite Core Tooling & Web Interception (Proxy configuration, Intercept, Repeater, Intruder, Decoder, Comparer, Scanner)**, and **Web Application Assessment & Metasploit Execution (Discovery-to-exploitation workflows, initial session handling, multi-stage payloads)**.

---

## Lab Collection Index

### 1. Network Reconnaissance, Discovery & Advanced Nmap
* **Network Mapping: From Unknown LAN to Actionable Topology**  
  *Lab Link:* [https://learn.secbyte.org/ctf/network-mapping-from-unknown-lan-to-actionable-topology](https://learn.secbyte.org/ctf/network-mapping-from-unknown-lan-to-actionable-topology)  
  *Focus:* Discovering active hosts on unmapped subnets (ARP sweeps, ICMP ping probes), mapping network device topologies, and building host inventory baselines.

<Image src="image_agent_tag_12869554246272684766" alt="Network topology diagram generated from Nmap discovery scanning" caption="Network Discovery & Topology Mapping Representation" />

---

* **Advanced Nmap Techniques: Service Mapping Under Pressure**  
  *Lab Link:* [https://learn.secbyte.org/ctf/advanced-nmap-techniques-service-mapping-under-pressure](https://learn.secbyte.org/ctf/advanced-nmap-techniques-service-mapping-under-pressure)  
  *Focus:* Executing advanced port scan types (SYN `-sS`, UDP `-sU`, ACK `-sA`), optimizing timing templates (`-T0` to `-T5`), customizing packet rates, and leveraging NSE scripts (`--script`) for service version detection (`-sV`).

* **Scanner: Network Discovery and Service Enumeration**  
  *Lab Link:* [https://learn.secbyte.org/ctf/scanner-network-discovery-and-service-enumeration](https://learn.secbyte.org/ctf/scanner-network-discovery-and-service-enumeration)  
  *Focus:* Utilizing automated scanning engines for broad network enumeration, banner grabbing exposed service endpoints, and identifying network service misconfigurations.

### 2. Burp Suite Core Toolkit & HTTP Interception
* **Burp Suite Fundamentals: Intercept, Repeater, Intruder, and Beyond**  
  *Lab Link:* [https://learn.secbyte.org/ctf/burp-suite-fundamentals-intercept-repeater-intruder-and-beyo](https://learn.secbyte.org/ctf/burp-suite-fundamentals-intercept-repeater-intruder-and-beyo)  
  *Focus:* Navigating the Burp Suite UI, setting up browser proxy listeners, configuring scope targets, and understanding core workflow integrations across tools.

* **Proxy Configuration Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/proxy-configuration-essentials](https://learn.secbyte.org/ctf/proxy-configuration-essentials)  
  *Focus:* Configuring browser proxy listeners, importing Burp CA certificates (`http://burp`), handling TLS interception, and configuring invisible proxying for non-proxy-aware clients.

<Image src="image_agent_tag_12869554246272687143" alt="Burp Suite Professional Proxy Intercept interface showing intercepted HTTP request" caption="Burp Suite Intercepting Proxy User Interface" />

---

* **Advanced Burp Suite: Intercept, Rebuild, Bypass**  
  *Lab Link:* [https://learn.secbyte.org/ctf/advanced-burp-suite-intercept-rebuild-bypass](https://learn.secbyte.org/ctf/advanced-burp-suite-intercept-rebuild-bypass)  
  *Focus:* Intercepting and modifying HTTP/S requests in-flight, manipulating headers/cookies/POST parameters, rebuilding client requests, and bypassing client-side validation guardrails.

* **Repeater**  
  *Lab Link:* [https://learn.secbyte.org/ctf/repeater](https://learn.secbyte.org/ctf/repeater)  
  *Focus:* Issuing manual HTTP request iterations using Burp Repeater, analyzing micro-variances in HTTP response status/headers/body, and testing endpoint parameter boundary conditions.

* **Intruder: Identity Drift**  
  *Lab Link:* [https://learn.secbyte.org/ctf/intruder-identity-drift](https://learn.secbyte.org/ctf/intruder-identity-drift)  
  *Focus:* Automating payload injection using Burp Intruder, configuring attack types (Sniper, Battering Ram, Pitchfork, Cluster Bomb), and brute-forcing session tokens/credentials.

* **Decoder: Signals, Encodings, Hidden Messages**  
  *Lab Link:* [https://learn.secbyte.org/ctf/decoder-signals-encodings-hidden-messages](https://learn.secbyte.org/ctf/decoder-signals-encodings-hidden-messages)  
  *Focus:* Decoding complex nested web encodings (URL, HTML entity, Base64, Hex, ASCII hex), constructing obfuscated payloads, and identifying data structures in session cookies.

* **Comparer: Finding Meaning in Similarity**  
  *Lab Link:* [https://learn.secbyte.org/ctf/comparer-finding-meaning-in-similarity](https://learn.secbyte.org/ctf/comparer-finding-meaning-in-similarity)  
  *Focus:* Performing byte-by-byte and word-by-word diff comparisons of HTTP responses in Burp Comparer, detecting subtle SQLi/blind response variations, and discovering hidden application paths.

### 3. Web Application Assessment & Metasploit Fundamentals
* **Web Application Testing: From Discovery to Exploitation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/web-application-testing-from-discovery-to-exploitation](https://learn.secbyte.org/ctf/web-application-testing-from-discovery-to-exploitation)  
  *Focus:* Executing end-to-end web assessments—from target discovery and directory brute-forcing to vulnerability identification and exploitation.

* **Metasploit Fundamentals: First Session to Multi-Stage Exploit**  
  *Lab Link:* [https://learn.secbyte.org/ctf/metasploit-fundamentals-first-session-to-multi-stage-exploit](https://learn.secbyte.org/ctf/metasploit-fundamentals-first-session-to-multi-stage-exploit)  
  *Focus:* Establishing initial command-line sessions in Metasploit, managing active sessions (`sessions -l`), staging multi-stage Meterpreter payloads, and transitioning from foothold to interactive control.

---

## Learning Path

### Path A: Network Reconnaissance & Mapping Specialist
1. **Host Discovery & Topology:** Start with [Network Mapping](https://learn.secbyte.org/ctf/network-mapping-from-unknown-lan-to-actionable-topology) and [Scanner](https://learn.secbyte.org/ctf/scanner-network-discovery-and-service-enumeration).
2. **Advanced Port & Service Scanning:** Master scanning techniques in [Advanced Nmap Techniques](https://learn.secbyte.org/ctf/advanced-nmap-techniques-service-mapping-under-pressure).

### Path B: Burp Suite & Web Application Penetration Tester
1. **Proxy & Basic Interception:** Configure environment via [Proxy Configuration Essentials](https://learn.secbyte.org/ctf/proxy-configuration-essentials) and [Burp Suite Fundamentals](https://learn.secbyte.org/ctf/burp-suite-fundamentals-intercept-repeater-intruder-and-beyo).
2. **Request Modification & Analysis:** Master manual testing in [Advanced Burp Suite](https://learn.secbyte.org/ctf/advanced-burp-suite-intercept-rebuild-bypass) and [Repeater](https://learn.secbyte.org/ctf/repeater).
3. **Automated Fuzzing & Decoders:** Fuzz endpoints via [Intruder](https://learn.secbyte.org/ctf/intruder-identity-drift), decode payloads in [Decoder](https://learn.secbyte.org/ctf/decoder-signals-encodings-hidden-messages), and diff responses in [Comparer](https://learn.secbyte.org/ctf/comparer-finding-meaning-in-similarity).

### Path C: Web Assessment & Exploit Execution Specialist
1. **Web Attack Lifecycle:** Conduct full tests in [Web Application Testing](https://learn.secbyte.org/ctf/web-application-testing-from-discovery-to-exploitation).
2. **Exploitation & Session Management:** Execute staged exploits using [Metasploit Fundamentals](https://learn.secbyte.org/ctf/metasploit-fundamentals-first-session-to-multi-stage-exploit).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, target IP ranges, or web application URLs.
4. Execute Nmap service discovery scans, route web traffic through Burp Suite Proxy, manipulate requests in Repeater, automate fuzzing using Intruder, decode nested cookie formats, or catch Meterpreter shells in Metasploit to capture flags.

---

## Target Audience

* **Penetration Testers & Web Security Auditors:** Master Burp Suite Pro/Community toolsets, perform manual HTTP request manipulation, execute custom Intruder attacks, and analyze response diffs.
* **Network Security Engineers & Reconnaissance Specialists:** Conduct external and internal network discovery using Nmap, analyze open port banners, and map network topologies.
* **Red Team Operators & Ethical Hackers:** Transition from network/web discovery to initial shell access using Metasploit and manage multi-stage Meterpreter payloads.
* **Cybersecurity Students:** Acquire practical hands-on experience in port scanning with Nmap, HTTP proxying with Burp Suite, and basic exploit launching with Metasploit.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning, interception, or exploitation against external production targets without explicit permission is strictly prohibited.

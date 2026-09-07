# 🛡️ Educational Cybersecurity Tools & Techniques

<p align="center">
  <img src="https://img.shields.io/github/stars/OmYarewar/educational-cybersec-tools?style=for-the-badge&color=yellow" alt="Stars" />
  <img src="https://img.shields.io/github/forks/OmYarewar/educational-cybersec-tools?style=for-the-badge&color=blue" alt="Forks" />
  <img src="https://img.shields.io/github/license/OmYarewar/educational-cybersec-tools?style=for-the-badge&color=green" alt="License" />
  <img src="https://img.shields.io/github/last-commit/OmYarewar/educational-cybersec-tools?style=for-the-badge&color=red" alt="Last Commit" />
  <br>
  <img src="https://img.shields.io/badge/Tools-150%2B-orange?style=for-the-badge" alt="Tools Count" />
  <img src="https://img.shields.io/badge/Categories-15-blueviolet?style=for-the-badge" alt="Categories" />
  <img src="https://img.shields.io/badge/Educational-Purposes%20Only-critical?style=for-the-badge" alt="Educational" />
</p>

> **⚠️ DISCLAIMER**: This repository is for **EDUCATIONAL PURPOSES ONLY**. All tools and techniques listed here are intended for ethical hacking, penetration testing, security research, and cybersecurity education. Unauthorized access to systems you do not own or have explicit permission to test is **illegal**. The repository owner assumes no liability for misuse.

---

## 📋 Table of Contents

- [Network Scanning & Reconnaissance](#network-scanning--reconnaissance)
- [Vulnerability Assessment](#vulnerability-assessment)
- [Exploitation Frameworks](#exploitation-frameworks)
- [Web Application Testing](#web-application-testing)
- [Wireless Security Testing](#wireless-security-testing)
- [Password & Hash Tools](#password--hash-tools)
- [OSINT (Open Source Intelligence)](#osint-open-source-intelligence)
- [Social Engineering](#social-engineering)
- [Forensics & Incident Response](#forensics--incident-response)
- [Reverse Engineering](#reverse-engineering)
- [Malware Analysis](#malware-analysis)
- [Mobile Security](#mobile-security)
- [Cloud & Container Security](#cloud--container-security)
- [Post-Exploitation](#post-exploitation)
- [Anonymity & Privacy](#anonymity--privacy)
- [New & Emerging Tools (2024-2026)](#new--emerging-tools-2024-2026)
- [Learning Resources](#learning-resources)

---

## Network Scanning & Reconnaissance

| Tool | Description | Link |
|------|-------------|------|
| **Nmap** | Industry-standard network discovery & port scanning | [nmap.org](https://nmap.org) |
| **Darkmoon** | Autonomous pentest platform, 50 agents over MCP, reproducible proof of exploitation, self hosted | [Repo](https://github.com/ASCIT31/Dark-Moon) |
| **Zenmap** | GUI for Nmap | [nmap.org/zenmap](https://nmap.org/zenmap) |
| **Masscan** | Ultra-fast port scanner (internet-scale) | [github.com/robertdavidgraham/masscan](https://github.com/robertdavidgraham/masscan) |
| **RustScan** | Modern fast port scanner written in Rust | [github.com/RustScan/RustScan](https://github.com/RustScan/RustScan) |
| **Shodan CLI** | Search engine for internet-connected devices | [cli.shodan.io](https://cli.shodan.io) |
| **Censys** | Internet asset discovery platform | [censys.io](https://censys.io) |
| **FOCA** | Metadata & hidden information analyzer | [github.com/ElevenPaths/FOCA](https://github.com/ElevenPaths/FOCA) |
| **theHarvester** | Email, domain, name information gathering | [github.com/laramies/theHarvester](https://github.com/laramies/theHarvester) |
| **Recon-ng** | Full-featured reconnaissance framework | [github.com/lanmaster53/recon-ng](https://github.com/lanmaster53/recon-ng) |
| **Amass** | In-depth DNS enumeration and network mapping | [github.com/owasp-amass/amass](https://github.com/owasp-amass/amass) |
| **Sublist3r** | Fast subdomain enumeration | [github.com/aboul3la/Sublist3r](https://github.com/aboul3la/Sublist3r) |
| **Subfinder** | Passive subdomain discovery | [github.com/projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder) |
| **dnsrecon** | DNS enumeration & zone transfer testing | [github.com/darkoperator/dnsrecon](https://github.com/darkoperator/dnsrecon) |
| **Raccoon** | Offensive security recon tool | [github.com/evyatarmeged/Raccoon](https://github.com/evyatarmeged/Raccoon) |
| **Naabu** | Fast port scanner (ProjectDiscovery) | [github.com/projectdiscovery/naabu](https://github.com/projectdiscovery/naabu) |
| **Httpx** | HTTP probing toolkit | [github.com/projectdiscovery/httpx](https://github.com/projectdiscovery/httpx) |
| **Nuclei** | Template-based vulnerability scanner | [github.com/projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) |

## Vulnerability Assessment

| Tool | Description | Link |
|------|-------------|------|
| **OpenVAS / Greenbone** | Full-featured vulnerability scanner | [openvas.org](https://www.openvas.org) |
| **Nessus** | Commercial vulnerability scanner (free for home) | [tenable.com](https://www.tenable.com/products/nessus) |
| **Nexpose** | Rapid7 vulnerability management | [rapid7.com](https://www.rapid7.com/products/nexpose/) |
| **Nikto** | Web server vulnerability scanner | [github.com/sullo/nikto](https://github.com/sullo/nikto) |
| **Wapiti** | Web application vulnerability scanner | [wapiti-scanner.github.io](https://wapiti-scanner.github.io) |
| **Trivy** | Comprehensive container & IaC vulnerability scanner | [github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy) |
| **Grype** | Vulnerability scanner for container images & filesystems | [github.com/anchore/grype](https://github.com/anchore/grype) |
| **Snyk CLI** | Developer-first security scanning | [snyk.io](https://snyk.io) |
| **OSV-Scanner** | Google's open source vulnerability scanner | [github.com/google/osv-scanner](https://github.com/google/osv-scanner) |

## Exploitation Frameworks

| Tool | Description | Link |
|------|-------------|------|
| **Metasploit Framework** | De facto standard for penetration testing & exploit development | [github.com/rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework) |
| **Armitage** | GUI for Metasploit | [gitlab.com/kalilinux/packages/armitage](https://gitlab.com/kalilinux/packages/armitage) |
| **BeEF** | Browser exploitation framework | [github.com/beefproject/beef](https://github.com/beefproject/beef) |
| **Empire / Starkiller** | Post-exploitation framework (PowerShell & Python) | [github.com/BC-SECURITY/Empire](https://github.com/BC-SECURITY/Empire) |
| **Sliver** | Cross-platform adversary emulation framework | [github.com/BishopFox/sliver](https://github.com/BishopFox/sliver) |
| **Havoc** | Modern post-exploitation C2 framework | [github.com/HavocFramework/Havoc](https://github.com/HavocFramework/Havoc) |
| **Mythic** | Cross-platform post-exploitation framework | [github.com/its-a-feature/Mythic](https://github.com/its-a-feature/Mythic) |
| **Cobalt Strike** | Commercial adversary simulation (licensed) | [cobaltstrike.com](https://www.cobaltstrike.com) |
| **Merlin** | Cross-platform post-exploitation HTTP/2 C2 | [github.com/Ne0nd0g/merlin](https://github.com/Ne0nd0g/merlin) |
| **Villain** | Advanced reverse shell generator & handler | [github.com/t3l3machus/Villain](https://github.com/t3l3machus/Villain) |
| **Commando VM** | Windows-based pentesting VM | [github.com/mandiant/commando-vm](https://github.com/mandiant/commando-vm) |
| **PayloadsAllTheThings** | Collection of payloads for every scenario | [github.com/swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) |

## Web Application Testing

| Tool | Description | Link |
|------|-------------|------|
| **Burp Suite** | Industry-standard web app security testing | [portswigger.net/burp](https://portswigger.net/burp) |
| **OWASP ZAP** | Free web app security scanner | [zaproxy.org](https://www.zaproxy.org) |
| **SQLMap** | Automatic SQL injection tool | [sqlmap.org](https://sqlmap.org) |
| **ffuf** | Fast web fuzzer written in Go | [github.com/ffuf/ffuf](https://github.com/ffuf/ffuf) |
| **wfuzz** | Web application fuzzer | [github.com/xmendez/wfuzz](https://github.com/xmendez/wfuzz) |
| **Dirb / Dirbuster** | Web content scanner | [github.com/v0re/dirb](https://github.com/v0re/dirb) |
| **Gobuster** | Directory/file & DNS busting tool | [github.com/OJ/gobuster](https://github.com/OJ/gobuster) |
| **Feroxbuster** | Fast recursive content discovery tool | [github.com/epi052/feroxbuster](https://github.com/epi052/feroxbuster) |
| **Commix** | Automated command injection tool | [github.com/commixproject/commix](https://github.com/commixproject/commix) |
| **XSSer** | Automated XSS detection & exploitation | [github.com/epsylon/xsser](https://github.com/epsylon/xsser) |
| **XSStrike** | Advanced XSS detection suite | [github.com/s0md3v/XSStrike](https://github.com/s0md3v/XSStrike) |
| **NoSQLMap** | NoSQL injection & exploitation | [github.com/codingo/NoSQLMap](https://github.com/codingo/NoSQLMap) |
| **GraphQLmap** | GraphQL endpoint testing | [github.com/swisskyrepo/GraphQLmap](https://github.com/swisskyrepo/GraphQLmap) |
| **Arjun** | HTTP parameter discovery | [github.com/s0md3v/Arjun](https://github.com/s0md3v/Arjun) |
| **WhatWeb** | Website fingerprinting | [github.com/urbanadventurer/WhatWeb](https://github.com/urbanadventurer/WhatWeb) |
| **Wappalyzer** | Technology stack identifier | [wappalyzer.com](https://www.wappalyzer.com) |
| **JWT_Tool** | JSON Web Token testing toolkit | [github.com/ticarpi/jwt_tool](https://github.com/ticarpi/jwt_tool) |
| **Autorize** | Burp extension for authorization testing | [github.com/portswigger/autorize](https://github.com/portswigger/autorize) |
| **HTTP Request Smuggler** | HTTP request smuggling tool | [github.com/portswigger/http-request-smuggler](https://github.com/portswigger/http-request-smuggler) |

## Wireless Security Testing

| Tool | Description | Link |
|------|-------------|------|
| **Aircrack-ng Suite** | Complete WiFi security auditing suite | [aircrack-ng.org](https://www.aircrack-ng.org) |
| **Wifite** | Automated wireless attack tool | [github.com/derv82/wifite2](https://github.com/derv82/wifite2) |
| **Reaver** | WPS brute force attack tool | [github.com/t6x/reaver-wps-fork-t6x](https://github.com/t6x/reaver-wps-fork-t6x) |
| **PixieWPS** | Offline WPS pin recovery | [github.com/wiire-a/pixiewps](https://github.com/wiire-a/pixiewps) |
| **Kismet** | Wireless network detector & sniffer | [kismetwireless.net](https://www.kismetwireless.net) |
| **Bettercap** | Swiss army knife for WiFi, BLE, and network attacks | [bettercap.org](https://www.bettercap.org) |
| **hcxtools** | WiFi hash capture and conversion | [github.com/ZerBea/hcxtools](https://github.com/ZerBea/hcxtools) |
| **Fluxion** | WiFi social engineering attack | [github.com/FluxionNetwork/fluxion](https://github.com/FluxionNetwork/fluxion) |
| **WEF (WiFi Exploitation Framework)** | Fully automated WiFi attack framework | [github.com/D3Ext/WEF](https://github.com/D3Ext/WEF) |
| **GATTacker** | BLE (Bluetooth Low Energy) central device attack | [github.com/securing/gattacker](https://github.com/securing/gattacker) |
| **Proxmark3 Tools** | RFID/NFC hacking tools | [github.com/RfidResearchGroup/proxmark3](https://github.com/RfidResearchGroup/proxmark3) |
| **Flipper Zero** | Multi-tool pentesting device firmware & tools | [flipperzero.one](https://flipperzero.one) |

## Password & Hash Tools

| Tool | Description | Link |
|------|-------------|------|
| **Hashcat** | World's fastest password recovery tool (GPU) | [hashcat.net](https://hashcat.net) |
| **John the Ripper** | Password security auditing & recovery | [openwall.com/john](https://www.openwall.com/john/) |
| **Hydra** | Network login brute-forcer (many protocols) | [github.com/vanhauser-thc/thc-hydra](https://github.com/vanhauser-thc/thc-hydra) |
| **Medusa** | Parallel network login brute-forcer | [github.com/jmk-foofus/medusa](https://github.com/jmk-foofus/medusa) |
| **CeWL** | Custom wordlist generator from websites | [github.com/digininja/CeWL](https://github.com/digininja/CeWL) |
| **Crunch** | Wordlist generator | [sourceforge.net/projects/crunch-wordlist](https://sourceforge.net/projects/crunch-wordlist/) |
| **CUPP** | Common User Passwords Profiler | [github.com/Mebus/cupp](https://github.com/Mebus/cupp) |
| **hash-identifier** | Hash type identification tool | [github.com/blackploit/hash-identifier](https://github.com/blackploit/hash-identifier) |
| **CrackStation** | Online hash lookup (rainbow tables) | [crackstation.net](https://crackstation.net) |
| **ntlm_theft** | NTLM hash stealing tool | [github.com/Greenwolf/ntlm_theft](https://github.com/Greenwolf/ntlm_theft) |
| **Responder** | LLMNR/NBT-NS/mDNS poisoner & hash capture | [github.com/lgandx/Responder](https://github.com/lgandx/Responder) |
| **Impacket** | Collection of Python classes for network protocols | [github.com/fortra/impacket](https://github.com/fortra/impacket) |
| **Kerbrute** | Kerberos pre-auth bruteforcing | [github.com/ropnop/kerbrute](https://github.com/ropnop/kerbrute) |
| **BloodHound** | Active Directory attack path analysis | [github.com/BloodHoundAD/BloodHound](https://github.com/BloodHoundAD/BloodHound) |
| **Mimikatz** | Windows credential extraction (legendary) | [github.com/ParrotSec/mimikatz](https://github.com/ParrotSec/mimikatz) |
| **LaZagne** | Password recovery for multiple applications | [github.com/AlessandroZ/LaZagne](https://github.com/AlessandroZ/LaZagne) |

## OSINT (Open Source Intelligence)

| Tool | Description | Link |
|------|-------------|------|
| **Maltego** | Graphical link analysis for OSINT | [maltego.com](https://www.maltego.com) |
| **SpiderFoot** | Automated OSINT automation | [github.com/smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) |
| **Sherlock** | Social media username search across 300+ sites | [github.com/sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) |
| **holehe** | Check email registration across services | [github.com/megadose/holehe](https://github.com/megadose/holehe) |
| **Twint** | Twitter scraping without API (archived) | [github.com/twintproject/twint](https://github.com/twintproject/twint) |
| **GHunt** | Google account OSINT tool | [github.com/mxrch/GHunt](https://github.com/mxrch/GHunt) |
| **PhoneInfoga** | Phone number information gathering | [github.com/sundowndev/phoneinfoga](https://github.com/sundowndev/phoneinfoga) |
| **EmailRep** | Email reputation & investigation | [emailrep.io](https://emailrep.io) |
| **Have I Been Pwned API** | Breach data search | [haveibeenpwned.com](https://haveibeenpwned.com) |
| **DeHashed** | Breach data search engine | [dehashed.com](https://dehashed.com) |
| **IntelX** | Intelligence search engine | [intelx.io](https://intelx.io) |
| **Trace Labs** | Missing persons OSINT platform | [tracelabs.org](https://www.tracelabs.org) |
| **OSINT Framework** | Curated OSINT resource collection | [osintframework.com](https://osintframework.com) |
| **Photon** | Incredibly fast web crawler for OSINT | [github.com/s0md3v/Photon](https://github.com/s0md3v/Photon) |
| **Maigret** | Username search across 2500+ sites | [github.com/soxoj/maigret](https://github.com/soxoj/maigret) |
| **Blackbird** | OSINT tool for searching accounts by username | [github.com/p1ngul1n0/blackbird](https://github.com/p1ngul1n0/blackbird) |

## Social Engineering

| Tool | Description | Link |
|------|-------------|------|
| **SET (Social Engineering Toolkit)** | Social engineering attack framework | [github.com/trustedsec/social-engineer-toolkit](https://github.com/trustedsec/social-engineer-toolkit) |
| **GoPhish** | Open-source phishing framework | [github.com/gophish/gophish](https://github.com/gophish/gophish) |
| **Evilginx2** | Man-in-the-middle attack framework (session hijacking) | [github.com/kgretzky/evilginx2](https://github.com/kgretzky/evilginx2) |
| **Modlishka** | Reverse proxy for phishing | [github.com/drk1wi/Modlishka](https://github.com/drk1wi/Modlishka) |
| **King Phisher** | Phishing campaign toolkit | [github.com/rsmusllp/king-phisher](https://github.com/rsmusllp/king-phisher) |
| **Zphisher** | Automated phishing tool | [github.com/htr-tech/zphisher](https://github.com/htr-tech/zphisher) |
| **Nexphisher** | Advanced phishing tool | [github.com/htr-tech/nexphisher](https://github.com/htr-tech/nexphisher) |
| **HiddenEye** | Modern phishing tool with ngrok integration | [github.com/An0nUD4Y/HiddenEye](https://github.com/An0nUD4Y/HiddenEye) |
| **ReelPhish** | Real-time 2FA phishing tool | [github.com/fireeye/ReelPhish](https://github.com/fireeye/ReelPhish) |

## Forensics & Incident Response

| Tool | Description | Link |
|------|-------------|------|
| **Autopsy / Sleuth Kit** | Digital forensics platform | [sleuthkit.org/autopsy](https://www.sleuthkit.org/autopsy) |
| **Volatility 3** | Advanced memory forensics framework | [github.com/volatilityfoundation/volatility3](https://github.com/volatilityfoundation/volatility3) |
| **Velociraptor** | Endpoint visibility & DFIR tool | [github.com/Velocidex/velociraptor](https://github.com/Velocidex/velociraptor) |
| **Wireshark** | Network protocol analyzer | [wireshark.org](https://www.wireshark.org) |
| **tcpdump** | Command-line packet analyzer | [tcpdump.org](https://www.tcpdump.org) |
| **TShark** | CLI version of Wireshark | [wireshark.org/docs/man-pages/tshark](https://www.wireshark.org/docs/man-pages/tshark.html) |
| **NetworkMiner** | Network forensics analysis tool | [netresec.com](https://www.netresec.com/?page=NetworkMiner) |
| **FTK Imager** | Disk imaging & forensics tool | [exterro.com/ftk-imager](https://www.exterro.com/ftk-imager) |
| **Guymager** | Forensic imaging tool for Linux | [guymager.sourceforge.io](https://guymager.sourceforge.io) |
| **bulk_extractor** | Bulk data extraction & analysis | [github.com/simsong/bulk_extractor](https://github.com/simsong/bulk_extractor) |
| **Binwalk** | Firmware analysis tool | [github.com/ReFirmLabs/binwalk](https://github.com/ReFirmLabs/binwalk) |
| **ExifTool** | Metadata reader/writer | [exiftool.org](https://exiftool.org) |
| **CyberChef** | "The Cyber Swiss Army Knife" - data manipulation | [gchq.github.io/CyberChef](https://gchq.github.io/CyberChef/) |
| **MemProcFS** | Physical memory analysis as filesystem | [github.com/ufrisk/MemProcFS](https://github.com/ufrisk/MemProcFS) |
| **Kape (Kroll Artifact Parser and Extractor)** | Fast triage collection | [kroll.com/kape](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape) |

## Reverse Engineering

| Tool | Description | Link |
|------|-------------|------|
| **Ghidra** | NSA's open-source reverse engineering suite | [ghidra-sre.org](https://ghidra-sre.org) |
| **IDA Pro / Freeware** | Industry-standard disassembler & debugger | [hex-rays.com](https://hex-rays.com/ida-free/) |
| **Radare2 / rizin** | Unix-like reverse engineering framework | [rada.re](https://rada.re) |
| **x64dbg** | Open-source x64/x32 debugger for Windows | [x64dbg.com](https://x64dbg.com) |
| **OllyDbg** | 32-bit assembler-level debugger for Windows | [ollydbg.de](http://www.ollydbg.de) |
| **dnSpy / dnSpyEx** | .NET debugger & assembly editor | [github.com/dnSpyEx/dnSpy](https://github.com/dnSpyEx/dnSpy) |
| **ILSpy** | .NET decompiler | [github.com/icsharpcode/ILSpy](https://github.com/icsharpcode/ILSpy) |
| **JD-GUI** | Java decompiler | [java-decompiler.github.io](https://java-decompiler.github.io) |
| **Frida** | Dynamic instrumentation toolkit | [frida.re](https://frida.re) |
| **Objection** | Runtime mobile exploration (Frida-based) | [github.com/sensepost/objection](https://github.com/sensepost/objection) |
| **APKTool** | Android APK reverse engineering | [apktool.org](https://apktool.org) |
| **JADX** | DEX to Java decompiler | [github.com/skylot/jadx](https://github.com/skylot/jadx) |
| **Angr** | Binary analysis platform | [angr.io](https://angr.io) |
| **Binary Ninja** | Modern reverse engineering platform | [binary.ninja](https://binary.ninja) |

## Malware Analysis

| Tool | Description | Link |
|------|-------------|------|
| **Cuckoo Sandbox** | Automated malware analysis system | [cuckoosandbox.org](https://cuckoosandbox.org) |
| **CAPE Sandbox** | Malware sandbox (Cuckoo fork with advanced features) | [github.com/kevoreilly/CAPEv2](https://github.com/kevoreilly/CAPEv2) |
| **Any.Run** | Interactive online malware sandbox | [any.run](https://any.run) |
| **VirusTotal** | File/URL scanning with 70+ AV engines | [virustotal.com](https://www.virustotal.com) |
| **Hybrid Analysis** | Free malware analysis service | [hybrid-analysis.com](https://www.hybrid-analysis.com) |
| **YARA** | Pattern matching swiss knife for malware | [github.com/VirusTotal/yara](https://github.com/VirusTotal/yara) |
| **FLARE VM** | Windows-based malware analysis VM | [github.com/mandiant/flare-vm](https://github.com/mandiant/flare-vm) |
| **REMnux** | Linux toolkit for malware analysis | [remnux.org](https://remnux.org) |
| **pe-sieve** | Process hollowing & malware unpacking scanner | [github.com/hasherezade/pe-sieve](https://github.com/hasherezade/pe-sieve) |
| **ProcMon** | Process Monitor for Windows (Sysinternals) | [docs.microsoft.com/sysinternals](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon) |
| **DIE (Detect It Easy)** | File type & packer detector | [github.com/horsicq/Detect-It-Easy](https://github.com/horsicq/Detect-It-Easy) |
| **x64dbg** | Open-source debugger for malware analysis | [x64dbg.com](https://x64dbg.com) |
| **ProcDOT** | Malware behavior visualization | [procdot.com](https://www.procdot.com) |

## Mobile Security

| Tool | Description | Link |
|------|-------------|------|
| **MobSF (Mobile Security Framework)** | Automated mobile app pentesting | [github.com/MobSF/Mobile-Security-Framework-MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) |
| **Drozer** | Android security assessment framework | [github.com/WithSecureLabs/drozer](https://github.com/WithSecureLabs/drozer) |
| **Frida** | Dynamic instrumentation for mobile apps | [frida.re](https://frida.re) |
| **APKTool** | Reverse engineering Android APKs | [apktool.org](https://apktool.org) |
| **Genymotion** | Android emulator for testing | [genymotion.com](https://www.genymotion.com) |
| **Android Studio Emulator** | Official Android emulator with root | [developer.android.com/studio](https://developer.android.com/studio) |
| **Magisk** | Systemless root for Android | [github.com/topjohnwu/Magisk](https://github.com/topjohnwu/Magisk) |
| **Needle** | iOS security testing framework | [github.com/WithSecureLabs/needle](https://github.com/WithSecureLabs/needle) |
| **iFunBox** | iOS file management tool | [i-funbox.com](https://www.i-funbox.com) |
| **Objection** | Runtime mobile exploration | [github.com/sensepost/objection](https://github.com/sensepost/objection) |
| **r2frida** | Radare2 + Frida integration | [github.com/nowsecure/r2frida](https://github.com/nowsecure/r2frida) |
| **AppMon** | Runtime mobile security analysis | [github.com/dpnishant/appmon](https://github.com/dpnishant/appmon) |
| **RMS (Runtime Mobile Security)** | Android runtime manipulation | [github.com/m0bilesecurity/RMS-Runtime-Mobile-Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) |

## Cloud & Container Security

| Tool | Description | Link |
|------|-------------|------|
| **ScoutSuite** | Multi-cloud security auditing | [github.com/nccgroup/ScoutSuite](https://github.com/nccgroup/ScoutSuite) |
| **Prowler** | AWS security assessment & hardening | [github.com/prowler-cloud/prowler](https://github.com/prowler-cloud/prowler) |
| **CloudSploit** | Cloud security scanning (Aqua) | [github.com/aquasecurity/cloudsploit](https://github.com/aquasecurity/cloudsploit) |
| **CloudFox** | AWS penetration testing tool | [github.com/BishopFox/cloudfox](https://github.com/BishopFox/cloudfox) |
| **kube-hunter** | Kubernetes penetration testing | [github.com/aquasecurity/kube-hunter](https://github.com/aquasecurity/kube-hunter) |
| **kube-bench** | CIS Kubernetes benchmark checker | [github.com/aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench) |
| **Falco** | Cloud-native runtime security | [falco.org](https://falco.org) |
| **CDK (Cloud Development Kit) GOAT** | Vulnerable-by-design cloud infrastructure | [github.com/nccgroup/cdkgoat](https://github.com/nccgroup/cdkgoat) |
| **CloudGoat** | Vulnerable AWS deployment scenarios | [github.com/RhinoSecurityLabs/cloudgoat](https://github.com/RhinoSecurityLabs/cloudgoat) |
| **SadCloud** | Sample vulnerable AWS infrastructure | [github.com/nccgroup/sadcloud](https://github.com/nccgroup/sadcloud) |
| **TruffleHog** | Secrets scanning tool | [github.com/trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog) |
| **Gitleaks** | Git repository secrets scanning | [github.com/gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) |

## Post-Exploitation

| Tool | Description | Link |
|------|-------------|------|
| **PowerShell Empire** | PowerShell post-exploitation agent | [github.com/BC-SECURITY/Empire](https://github.com/BC-SECURITY/Empire) |
| **Covenant** | .NET C2 framework | [github.com/cobbr/Covenant](https://github.com/cobbr/Covenant) |
| **SharpHound** | BloodHound data collector | [github.com/BloodHoundAD/SharpHound](https://github.com/BloodHoundAD/SharpHound) |
| **Seatbelt** | C# host enumeration tool | [github.com/GhostPack/Seatbelt](https://github.com/GhostPack/Seatbelt) |
| **Rubeus** | C# Kerberos toolset | [github.com/GhostPack/Rubeus](https://github.com/GhostPack/Rubeus) |
| **Certify** | Active Directory certificate abuse | [github.com/GhostPack/Certify](https://github.com/GhostPack/Certify) |
| **Ligolo-ng** | Advanced tunneling/pivoting tool | [github.com/nicocha30/ligolo-ng](https://github.com/nicocha30/ligolo-ng) |
| **Chisel** | Fast TCP/UDP tunnel over HTTP | [github.com/jpillora/chisel](https://github.com/jpillora/chisel) |
| **LinPEAS / WinPEAS** | Privilege escalation enumeration | [github.com/carlospolop/PEASS-ng](https://github.com/carlospolop/PEASS-ng) |
| **PowerView** | PowerShell AD enumeration | [github.com/PowerShellMafia/PowerSploit](https://github.com/PowerShellMafia/PowerSploit) |
| **CrackMapExec** | Swiss army knife for pentesting networks | [github.com/byt3bl33d3r/CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) |
| **NetExec** | Modern CrackMapExec successor | [github.com/Pennyw0rth/NetExec](https://github.com/Pennyw0rth/NetExec) |
| **Evil-WinRM** | Ultimate WinRM shell for pen-testing | [github.com/Hackplayers/evil-winrm](https://github.com/Hackplayers/evil-winrm) |

## Anonymity & Privacy

| Tool | Description | Link |
|------|-------------|------|
| **Tor Browser** | Anonymous browsing | [torproject.org](https://www.torproject.org) |
| **Tails OS** | Amnesic incognito live system | [tails.net](https://tails.net) |
| **Whonix** | Anonymous operating system | [whonix.org](https://www.whonix.org) |
| **Proxychains** | Force TCP through proxies | [github.com/haad/proxychains](https://github.com/haad/proxychains) |
| **Privoxy** | Non-caching web proxy with filtering | [privoxy.org](https://www.privoxy.org) |
| **DNSCrypt** | Encrypted DNS protocol | [dnscrypt.info](https://dnscrypt.info) |
| **Pi-hole** | Network-wide ad blocking | [pi-hole.net](https://pi-hole.net) |
| **WireGuard** | Fast, modern VPN protocol | [wireguard.com](https://www.wireguard.com) |
| **OpenVPN** | Full-featured SSL VPN | [openvpn.net](https://openvpn.net) |
| **I2P** | Anonymous network layer | [geti2p.net](https://geti2p.net) |
| **SecureDrop** | Whistleblower submission system | [securedrop.org](https://securedrop.org) |
| **Signal** | End-to-end encrypted messaging | [signal.org](https://signal.org) |

---

## New & Emerging Tools (2024-2026)

These are the latest tools gaining traction in the offensive security community:

| Tool | Category | Description |
|------|----------|-------------|
| **Nuclei v3** | Vulnerability Scanning | Major update with JavaScript protocol, multi-step workflows, advanced template engine |
| **Katana** | Web Crawling | Next-gen headless crawler from ProjectDiscovery with JS rendering |
| **Brutespray** | Credential Attack | Automated bruteforcing based on Nmap scans — port-to-protocol mapping |
| **Sn1per Professional** | Reconnaissance | All-in-one offensive security platform with automated reporting |
| **Caido** | Web App Testing | Modern web security auditing toolkit (Burp Suite alternative) |
| **Smap** | Network Scanning | Shodan-powered Nmap alternative |
| **Atomic Red Team** | Detection Testing | Library of tests mapped to MITRE ATT&CK |
| **PwnKit** | Priv Esc | Polkit (CVE-2021-4034) exploitation |
| **Cerbrutus** | Credential Attack | Modular network brute-forcer in Rust |
| **Ligolo-ng** | Tunneling | Modern, fast tunneling — successor to Ligolo |
| **NetExec** | Post-Exploitation | CrackMapExec rewrite — modern architecture |
| **DragonCastle** | AD Attack | Novel Active Directory attack techniques |
| **COFFLoader** | Payload Execution | Load and execute COFF objects in memory |
| **Packer-Fuzzer** | Web Security | Automated detection of front-end packaging vulnerabilities |
| **RustHound** | AD Recon | BloodHound collector rewritten in Rust |
| **C2-Tool-Collection** | C2 | Curated collection of C2 frameworks and techniques |
| **AI-assisted Fuzzing Tools** | Fuzzing | LLM-powered vulnerability discovery (emerging field) |
| **DeepExploit** | AI/ML Pentesting | Machine learning-based automated penetration testing |

---

## Learning Resources

### 🎓 Training Platforms
- [Hack The Box](https://www.hackthebox.com) — Hands-on pentesting labs
- [TryHackMe](https://tryhackme.com) — Beginner-friendly cybersecurity training
- [PentesterLab](https://pentesterlab.com) — Web pentesting exercises
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Free web security training
- [Offensive Security (OSCP/OSEP)](https://www.offensive-security.com) — Professional certifications
- [SANS Institute](https://www.sans.org) — Advanced cybersecurity training
- [TCM Security](https://tcm-sec.com) — Practical pentesting courses
- [INE (eLearnSecurity)](https://ine.com) — eJPT, eCPPT certifications
- [Cybrary](https://www.cybrary.it) — Free cybersecurity courses

### 📚 Essential Reading
- **The Web Application Hacker's Handbook** — Stuttard & Pinto
- **Penetration Testing: A Hands-On Introduction to Hacking** — Georgia Weidman
- **The Hacker Playbook 3** — Peter Kim
- **Red Team Field Manual (RTFM)** — Ben Clark
- **Blue Team Field Manual (BTFM)** — Alan J White & Ben Clark
- **Black Hat Python / Gray Hat Python** — Justin Seitz
- **Practical Malware Analysis** — Sikorski & Honig
- **Hacking: The Art of Exploitation** — Jon Erickson
- **Metasploit: The Penetration Tester's Guide** — Kennedy et al.
- **Attacking Network Protocols** — James Forshaw

### 🛠️ Essential Distributions
- [Kali Linux](https://www.kali.org) — The industry standard pentesting OS
- [Parrot OS](https://parrotsec.org) — Security-focused Linux distribution
- [BlackArch](https://blackarch.org) — Arch Linux-based pentesting distro (2800+ tools)
- [Commando VM](https://github.com/mandiant/commando-vm) — Windows pentesting VM
- [Tsurugi Linux](https://tsurugi-linux.org) — DFIR-focused Linux distro

### 📊 Frameworks & Standards
- [MITRE ATT&CK](https://attack.mitre.org) — Adversarial tactics & techniques
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — Web application risks
- [CWE Top 25](https://cwe.mitre.org/top25/) — Most dangerous software weaknesses
- [PTES](http://www.pentest-standard.org/) — Penetration Testing Execution Standard
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [OSSTMM](https://www.isecom.org/research.html) — Open Source Security Testing Methodology Manual

---

## ⚖️ Legal & Ethical Guidelines

1. **Always obtain written authorization** before testing any system
2. **Define scope clearly** — know what's in and out of bounds
3. **Follow responsible disclosure** — report vulnerabilities ethically
4. **Never test production systems** without explicit permission
5. **Understand local laws** — cybersecurity laws vary by country/jurisdiction
6. **Document everything** — maintain detailed logs of all testing activities
7. **Respect data privacy** — handle discovered data responsibly

> **Remember**: The difference between a hacker and a criminal is **permission**. Always get it in writing.

---

## 🤝 Contributing

This is a living document. If you know of tools or resources that should be here:
1. Fork the repo
2. Add your contribution
3. Submit a pull request

Help keep this resource comprehensive and up-to-date for the community.

## ⭐ Star History

<p align="center">
  <a href="https://star-history.com/#OmYarewar/educational-cybersec-tools&Date" target="_blank">
    <img src="https://api.star-history.com/svg?repos=OmYarewar/educational-cybersec-tools&type=Date" alt="Star History Chart" width="600" />
  </a>
</p>

## 📣 Share & Support

If this resource helped you, drop a ⭐ and share it:

<p align="center">
  <a href="https://twitter.com/intent/tweet?text=Comprehensive%20cybersecurity%20toolkit%20-%20150%2B%20tools%20for%20ethical%20hacking,%20pentesting,%20OSINT,%20and%20more.%20All%20for%20educational%20purposes.%20Check%20it%20out:&url=https://github.com/OmYarewar/educational-cybersec-tools" target="_blank">
    <img src="https://img.shields.io/badge/Share_on-Twitter-1DA1F2?style=for-the-badge&logo=twitter" alt="Share on Twitter" />
  </a>
  <a href="https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/OmYarewar/educational-cybersec-tools" target="_blank">
    <img src="https://img.shields.io/badge/Share_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" alt="Share on LinkedIn" />
  </a>
  <a href="https://www.reddit.com/submit?url=https://github.com/OmYarewar/educational-cybersec-tools&title=Educational%20Cybersecurity%20Tools%20-%20150%2B%20Tools%20Collection" target="_blank">
    <img src="https://img.shields.io/badge/Share_on-Reddit-FF4500?style=for-the-badge&logo=reddit" alt="Share on Reddit" />
  </a>
</p>

---

*Last updated: May 2026*

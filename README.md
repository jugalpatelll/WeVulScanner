## Authors
- Jugalkumar Patel
- Manasi Rajput
- Ved Patel
- Shweta Narkhede





## Features
- **one-step installation**.
- **executes a multitude of security scanning tools**, does other **custom coded checks** and **prints the results spontaneously**.
- some of the tools include `nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, amass, nikto` etc executes under one entity.
- saves a lot of time, **indeed a lot time!**.
- **checks for same vulnerabilities with multiple tools** to help you **zero-in on false positives** effectively.
- **extremely light-weight and not process intensive.**
- **critical, high, medium, low and informational** classification of vulnerabilities.
- **vulnerability definitions** guides you what the vulnerability actually is and the threat it can pose.
- **remediation** tells you how to plug/fix the found vulnerability.
- **executive summary** gives you an overall context of the scan performed with critical, high, low and informational issues discovered.

---
### FYI:
- _**works** and currently supports **80** vulnerability tests._
- _parallel processing is not yet implemented, may be coded as more tests gets introduced._

## Vulnerability Checks
- :heavy_check_mark: DNS/HTTP Load Balancers & Web Application Firewalls.
- :heavy_check_mark: Checks for Joomla, WordPress and Drupal
- :heavy_check_mark: SSL related Vulnerabilities (_HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling_).
- :heavy_check_mark: Commonly Opened Ports.
- :heavy_check_mark: DNS Zone Transfers using multiple tools (_Fierce, DNSWalk, DNSRecon, DNSEnum_).
- :heavy_check_mark: Sub-Domains Brute Forcing (_DNSMap, amass, nikto_)
- :heavy_check_mark: Open Directory/File Brute Forcing.
- :heavy_check_mark: Shallow XSS, SQLi and BSQLi Banners.
- :heavy_check_mark: Slow-Loris DoS Attack, LFI (_Local File Inclusion_), RFI (_Remote File Inclusion_) & RCE (_Remote Code Execution_).
- & more coming up...

## Requirements
- **Python 3**
- Kali OS (_**Preferred**, as it is shipped with almost all the tools_)
- Tested with Parrot & Ubuntu Operating Systems.

## Usage 
 `python3 rapidscan.py example.com`

##To Clone
- https://github.com/Kuchbhihe/SSPUrapidscanner.git

## Contribution
- Create your feature branch: `git checkout -b my-new-feature`
- Commit your changes: `git commit -am 'Add some feature'`
- Push to the branch: `git push origin my-new-feature`
- Submit a pull request.

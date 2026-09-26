# Week 2 Internship Report: theHarvester and Zenmap

This repository contains my Week 2 practical report for the Cybersecurity internship program at Networkwalks. It covers two modules: footprinting a domain with theHarvester and scanning a local network with Zenmap.

## Modules Completed

- **W2-PM1** — theHarvester Tool (replaces the standard multi tool footprinting module)
- **W2-PM5** — Zenmap Scanning

## Tools Used

- Kali Linux and Windows
- theHarvester
- Zenmap (Nmap GUI)
- Windows CMD (ipconfig)

## What Was Done

**Task 1:** Ran theHarvester against the target domain using only the Baidu source, with the result limit set to 1000.

**Task 2:** Ran theHarvester against the same domain using all available sources, with the result limit set to 50 per source. Several sources needed an API key that was not configured, so the scan fell back to free sources and still found ASN, IP and subdomain information.

**Zenmap:** Identified my local subnet with ipconfig, then ran a Ping scan against it to find live hosts, view their IP and MAC addresses, and generate a network topology diagram.

## Key Findings

- theHarvester found 3 ASNs and 4 IP addresses using the all sources scan, but nothing using Baidu alone
- 3 subdomains were discovered through a DNS based fallback search
- No emails, employee names or hosts were found in either theHarvester task
- Zenmap identified 2 live hosts on the scanned subnet

## Report

The full write up, including screenshots, risk analysis and recommendations, is in ./W2-PM-FINAL.pdf

## Disclaimer

All activities in this report were performed only against a domain with permission already secured, or against my own local network. This work is for education purposes only.

## Author

[Muhammad Faisal Rahman]  
Cybersecurity Program B083E, Networkwalks Internship

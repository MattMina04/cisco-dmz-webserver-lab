# Cisco DMZ Web Server – Professional Packet Tracer Project

**Date:** 2025-08-27

## Contents
- `Professional_Project_Report.docx` – detailed, illustrated report with configuration and evidence.
- `Professional_Project_Report.pdf` – print‑friendly PDF of the report (selected images).
- `Switch_Config.txt` – paste‑ready IOS configuration (VLANs, SVIs, ip routing, ACL).
- `index.html` – example content for the Server0 HTTP service.
- `Evidence/` – copy your own screenshots here to keep the pack together.

## Quick Start
1. Paste `Switch_Config.txt` into your multilayer switch (config mode).
2. Set host IPs: Laptops 192.168.1.2/24 & 1.3/24 (GW 192.168.1.1), Server 192.168.2.2/24 (GW 192.168.2.1).
3. Enable HTTP on Server0. Browse from a laptop to `http://192.168.2.2` (works).
4. Apply ACL `DMZ-WEB-ONLY` (already in the config) and re‑test: web works; ping/non‑web fails.

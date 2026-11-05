# 🖥️ ERTECH HOME // Enterprise Homelab Engineering, Cloud Architecture & Self-Hosted Tech

```text
 ███████╗██████╗ ████████╗███████╗ ██████╗██╗  ██╗    ██╗  ██╗ ██████╗ ███╗   ███╗███████╗
 ██╔════╝██╔══██╗╚══██╔══╝██╔════╝██╔════╝██║  ██║    ██║  ██║██╔═══██╗████╗ ████║██╔════╝
 █████╗  ██████╔╝   ██║   █████╗  ██║     ███████║    ███████║██║   ██║██╔████╔██║█████╗  
 ██╔══╝  ██╔══██╗   ██║   ██╔══╝  ██║     ██╔══██║    ██╔══██║██║   ██║██║╚██╔╝██║██╔══╝  
 ███████╗██║  ██║   ██║   ███████╗╚██████╗██║  ██║    ██║  ██║╚██████╔╝██║ ╚═╝ ██║███████╗
 ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚═════╝╚═╝  ╚═╝    ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
```

> **[OFFICIAL PRODUCTION REPOSITORY]**  
> *The definitive engineering portal for enterprise homelabs, Proxmox VE hypervisors, ZFS storage calculators, Kubernetes on bare metal, and self-hosted AI infrastructure.*  
> Engineered by **Efrain Rivas** — Senior Enterprise Infrastructure Architect.

---

## ⚡ Live Telemetry & Badges

[![Production Site](https://img.shields.io/badge/Production-ertechhome.com-06b6d4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ertechhome.com)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Mirror-10b981?style=for-the-badge&logo=github)](https://digdast.github.io/ertechhome-website/)
[![Status](https://img.shields.io/badge/Status-100%25%20Operational-34d399?style=for-the-badge&logo=statuspage&logoColor=white)](https://ertechhome.com)
[![Cloudflare Edge](https://img.shields.io/badge/Edge-Cloudflare%20Anycast%20CDN-f38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://dash.cloudflare.com)
[![Security Hardened](https://img.shields.io/badge/Security-CSP%20%2B%20OWASP%20Shielded-emerald?style=for-the-badge&logo=shield&logoColor=white)](https://ertechhome.com)
[![Google AdSense](https://img.shields.io/badge/Monetization-Google%20AdSense%20Verified-4285f4?style=for-the-badge&logo=google-ads&logoColor=white)](https://ertechhome.com/ads.txt)
[![Design](https://img.shields.io/badge/Stack-TailwindCSS%20%2B%20Lucide-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

---

## 🌟 Core Platform Highlights

1. **Enterprise ZFS Storage & RAID Pool Calculator**:
   - Interactive array modeling for **Mirror (RAID 10)**, **RAID-Z1 (RAID 5 equivalent)**, **RAID-Z2 (RAID 6 equivalent - recommended for drives > 8TB)**, and **RAID-Z3**.
   - Computes raw capacity, parity overhead, 80% ZFS copy-on-write performance safety threshold, and fault tolerance count.
2. **Cloud vs. On-Premises Homelab ROI Engine**:
   - Compares 3-year Total Cost of Ownership (TCO) between major hyperscalers (AWS EC2 / S3 / Egress, Azure, GCP) and enterprise on-premises refurbished hardware (Dell PowerEdge, HPE ProLiant, Supermicro).
   - Real-time payback timeline and breakeven calculations.
3. **Automated Docker Compose & Stack Blueprint Generator**:
   - Generates production-ready `docker-compose.yml` templates for:
     - **Sovereign AI Stack**: Ollama (GPU acceleration) + Open WebUI.
     - **Telemetry & Monitoring**: Prometheus + Grafana + Node Exporter.
     - **Enterprise Storage & Media**: Nextcloud Hub + Jellyfin + Portainer.
     - **Identity & Security Broker**: Authentik SSO + Nginx Proxy Manager.
4. **Google AdSense Revenue Engine**:
   - High CPC technology, enterprise cloud hosting, and server hardware keywords.
   - 100% verified authorized `ads.txt` integration (`pub-1596056523034714`).
5. **Hardened Production Security**:
   - Content Security Policy (CSP), subresource integrity, MIME sniffing protection, and origin masking.

---

## 🏗️ High-Availability Edge Architecture

```mermaid
flowchart TD
    subgraph Traffic ["🏢 Enterprise Homelab & Cloud Engineers"]
        Engineer["Infrastructure Architects & Homelabbers"]
        Crawler["Search Engines & Google AdSense Bots"]
    end

    subgraph Cloudflare ["☁️ Cloudflare Global Anycast Edge (ertechhome.com)"]
        CF_DNS["Cloudflare DNS (Zone: a83ffc077d1f251a39f91d68769df2c5)"]
        CF_Edge["DDoS Scrubbing & Anycast CDN Caching"]
        CF_TLS["Universal SSL (Full Strict / TLS 1.3)"]
        CF_WAF["WAF & Bot Management Shield"]
    end

    subgraph GitHub_Origin ["⚡ GitHub Pages Origin"]
        Origin["Static HTML5 Engineering Suite"]
        AdsTxt["Verified ads.txt (pub-1596056523034714)"]
        Robots["robots.txt & sitemap.xml"]
    end

    subgraph Client ["🛡️ Client Browser Security"]
        CSP["Content-Security-Policy (AdSense-Safe)"]
        Headers["X-Content-Type-Options: nosniff"]
        Perms["Permissions-Policy"]
    end

    Engineer --> CF_DNS
    Crawler --> CF_DNS
    CF_DNS --> CF_Edge --> CF_TLS --> CF_WAF
    CF_WAF --> Origin
    Origin --> AdsTxt
    Origin --> Robots
    CF_WAF --> Client
```

---

## 🛡️ Security Hardening & Compliance

- **Content-Security-Policy (CSP)**: Restricts script execution to local origins, Google AdSense, and official CDNs while preventing unauthorized cross-origin requests.
- **MIME & Referrer Policies**: `X-Content-Type-Options: nosniff` and `Referrer-Policy: strict-origin-when-cross-origin`.
- **Permissions Policy**: `camera=(), microphone=(), geolocation=()` to protect visitor hardware.
- **Privacy & Compliance**: Integrated GDPR / CCPA cookie consent and privacy policy modals.

---

## 📂 Repository Topology

```text
ertechhome-website/
├── index.html        # High-performance homelab single-page app
├── ads.txt           # Google AdSense publisher validation (pub-1596056523034714)
├── robots.txt        # Universal search engine indexing directive
├── sitemap.xml       # Canonical XML sitemap for SEO discovery
├── CNAME             # GitHub Pages custom domain binding (ertechhome.com)
├── static/           # Vector branding assets, SVGs, and logos
└── README.md         # Architecture, security & telemetry documentation
```

---

## ⚖️ License & Attribution

Designed and maintained by **Efrain Rivas**.  
All rights reserved © 2026 **ERTechHome.com**.

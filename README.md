# SiteMapper
### Professional XML Sitemap Generator & Technical SEO Crawler
**Developed by [Tekzilver](https://tekzilver.com)**

[![Release](https://img.shields.io/github/v/release/tekzilver/SiteMapper?color=0284C7&label=Version)](https://github.com/tekzilver/SiteMapper/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-38BDF8)](https://github.com/tekzilver/SiteMapper/releases)
[![License](https://img.shields.io/badge/License-MIT-gray)](LICENSE)

SiteMapper is a high-performance desktop application engineered to crawl websites, inspect URL structures, analyze HTTP status codes, and generate production-grade XML Sitemaps with no page limits or subscription constraints.

[**Download Latest Release (.exe)**](https://github.com/tekzilver/SiteMapper/releases/latest) | [**Features**](#key-features) | [**Usage Guide**](#how-to-use) | [**Policy**](#acceptable-use--responsible-crawling-policy)

---

## Key Features

- **Multi-Threaded Crawling Engine**: Fast URL discovery with adjustable concurrency and depth levels.
- **Unlimited & Unrestricted**: Free from page limitations, credit caps, and subscription tiers.
- **SEO Standard Compliance**: Full compliance with robots.txt directives, canonical link tags, and noindex meta rules.
- **HTTP & Structure Diagnostics**: Real-time breakdown of response status codes (200 OK, 301/302 Redirects, 404 Broken Links), content MIME types, and URL crawl depths.
- **Multiple Export Formats**:
  - Standard XML Sitemap (`sitemap.xml`)
  - Compressed Gzip Sitemap (`sitemap.xml.gz`)
  - Sitemap Index (automatic chunking for 50,000+ URL websites)
  - CSV Spreadsheet & Plain Text URL list
  - Static HTML Sitemap
- **Search & Filter Capabilities**: Filter crawled URLs by status code, response time, depth level, or target path.
- **Local & Private Execution**: Crawling runs entirely on your local machine. No external proxies, data collection, or telemetry.

---

## Installation & Download

1. Navigate to the [**Releases**](https://github.com/tekzilver/SiteMapper/releases/latest) page.
2. Download the installer: **`SiteMapper Setup 1.0.0.exe`**.
3. Run the installer and launch SiteMapper.

> **Windows Defender / SmartScreen Notice:**  
> When launching SiteMapper for the first time, Windows Firewall may request permission to allow network communication. This is standard behavior for desktop web crawlers initiating outbound HTTP/HTTPS connections. Click **"Allow access"** to enable crawling.

---

## How to Use

1. **Enter URL**: Provide your root domain address (e.g., `https://example.com`).
2. **Configure Settings (Optional)**:
   - Max Crawl Depth (e.g., 3 to 10 levels).
   - Maximum Pages limit.
   - Request delay / rate-limiting parameters.
   - URL inclusion/exclusion patterns.
3. **Start Crawl**: Monitor real-time status code reports and discovered link trees.
4. **Export**: Navigate to the Export tab, select your format (`.xml`, `.xml.gz`, `.csv`, `.html`), and save your sitemap for submission to Google Search Console and Bing Webmaster Tools.

---

## Acceptable Use & Responsible Crawling Policy

SiteMapper is built for website owners, webmasters, SEO professionals, and developers to audit and map their own digital assets.

Users are expected to follow standard web etiquette:
1. **Authorization**: Only crawl domains you own, manage, or have explicit permission to audit.
2. **Server Politeness**: Avoid setting excessive concurrency levels against low-bandwidth or shared hosting environments. Use the built-in request delay settings.
3. **Respect Directives**: Adhere to `robots.txt` crawl-delay and disallow parameters.
4. **Prohibited Activities**: Misuse of this software for Denial of Service (DoS/DDoS) attacks, aggressive data harvesting, or bypassing access controls is strictly prohibited.

---

## System Requirements

- **Operating System**: Windows 10 or Windows 11 (64-bit)
- **Memory**: 2 GB RAM minimum (4 GB recommended for large crawls)
- **Disk Space**: ~250 MB free storage

---

## License & Credits

- Developed by **[Tekzilver](https://tekzilver.com)**
- Open-source under the [MIT License](LICENSE).

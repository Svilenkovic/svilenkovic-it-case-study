# Svilenković IT

A technical service site that makes domains, mail delivery, TLS and website security understandable to business owners.

**[svilenkovicit.com](https://svilenkovicit.com/)** · [ARHIFARM case study](https://svilenkovicit.com/en/projects/arhifarm/) · [Srpski](README.sr.md)

> [!NOTE]
> This is an independent project by D. Svilenković. The production source stays in a private repository; this public repository documents the work.

<table>
  <tr><td><b>Type</b></td><td>Domains, mail and web security</td></tr>
  <tr><td><b>Languages</b></td><td>Serbian and English</td></tr>
  <tr><td><b>Public routes</b></td><td>28 canonical pages</td></tr>
  <tr><td><b>Role</b></td><td>Research, design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>Astro, TypeScript, CSS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## Purpose

Domains and mail are usually discussed only when something stops working. This site gives each part of the system a clear place, from DNS and certificates to mailbox delivery and production checks.

## Design direction

An optical network carries packets through cyan nodes on a dark blue field. The animation follows the path between a browser, DNS, mail and the server without hiding the written explanation.

## What I built

- Separate pages for domains, DNS, mail, TLS and maintenance
- A visual packet path tied to the service explanation
- Security headers and private-path checks on the live release
- A bilingual information architecture with 28 canonical routes
- Contact forms isolated per domain and protected by validation and rate limits

## Release checks

Every canonical route was checked at 390, 768, 1440 and 1920 px. The release was also tested without JavaScript and with reduced motion. Live checks covered HTTPS, redirects, response headers, structured data, sitemap files, protected paths and invalid contact requests without sending test mail.

These are engineering checks, not claims about search ranking or field performance.

---

<sub>Designed and built by [D. Svilenković](https://svilenkovic.com).</sub>

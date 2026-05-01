# CVE-2026-31431 Copy Fail — DFIR Investigation Walkthrough

An interactive, step-by-step forensic investigation walkthrough for the **Copy Fail** Linux kernel vulnerability (CVE-2026-31431).

Click through a realistic incident response scenario — from SIEM alert to confirmed verdict — using **real tools and verified commands**.

## What You'll See

- Authentication logs with no escalation trail
- Disk integrity checks that say "all clean"
- The moment memory forensics reveals what disk can't
- Real **Volatility 3** plugins (`linux.pagecache.Files`, `linux.pagecache.InodePages`)
- Audit trail reconstruction with actual `ausearch` syntax
- Exploit script recovery via `strings` on a memory dump

## Why This Exists


Copy Fail (CVE-2026-31431) is a page-cache-only attack — disk forensics alone will miss it entirely. This walkthrough shows what a DFIR analyst would actually look for.

## Live Demo

**[Try it live →](https://ledlight33.github.io/copyfail-dfir/)**

## Tech

Single-page HTML with React (via CDN). No build step, no dependencies — just open `index.html`.

## Related

🧪 **[Periodic Table of DFIR](https://ledlight33.github.io/periodic-table-of-dfir/)** — 118 tools for Digital Forensics & Incident Response

## Created By

**Marino Bekios** — MB Labs

[linkedin.com/in/marbekios](https://linkedin.com/in/marbekios)

[Visit my Website](https://marinobekios.com/)

## License

MIT - © 2026 Marino Bekios, MB Labs

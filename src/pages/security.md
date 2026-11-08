---
layout: ../layouts/LegalLayout.astro
title: Security policy
description: How to report a security vulnerability in miszori.dev, Mensaplan Zürich, amőba or vault.
lang: en
updated: Last updated 8 November 2026
---

If you find a security vulnerability in one of my sites or projects, please tell me privately so I can fix it before anyone misuses it.

## What this covers

- The sites [miszori.dev](https://miszori.dev), [mensa.miszori.dev](https://mensa.miszori.dev), [amoeba.miszori.dev](https://amoeba.miszori.dev) and [vault.miszori.dev](https://vault.miszori.dev).
- My public repositories on GitHub: [miszori.dev](https://github.com/gmiszori/miszori.dev), [mensa.miszori.dev](https://github.com/gmiszori/mensa.miszori.dev), [amoeba](https://github.com/gmiszori/amoeba), [vault.miszori.dev](https://github.com/gmiszori/vault.miszori.dev) and [webserver-proxy](https://github.com/gmiszori/webserver-proxy).

Only the latest version on each repository's `main` branch is supported.

## How to report

Email [gergo@miszori.dev](mailto:gergo@miszori.dev). English, German and Hungarian are all fine. Please include:

- what is affected (site, repository, file or URL),
- the steps to reproduce it,
- what an attacker could do with it.

Please don't open a public issue or talk about the vulnerability publicly until it is fixed.

## What to expect

These are personal projects that I maintain alone, so I can't promise a response time. I read every report, and I fix confirmed vulnerabilities as soon as I can. I'll tell you when the fix is out.

## Testing

**Please test only locally, never against the live sites.** Every project runs on your own machine with Docker; the README of each repository explains how. On the live sites, please don't scan, fuzz, load-test or brute-force anything, and don't try to access other people's data or accounts. Social engineering and phishing are never allowed.

If you act in good faith and follow this policy, I consider your research authorised and won't take legal action against you. That also applies if you come across a vulnerability by accident while using a site normally.

## Out of scope

- Denial of service and volume testing.
- Reports from automated scanners without a demonstrated impact.
- Limitations a project already documents, such as the trust boundaries in [vault's security documentation](https://github.com/gmiszori/vault.miszori.dev/blob/main/docs/security.md).
- Vulnerabilities in Cloudflare, GitHub or other services I use. Please report those to the service.

## Thanks

There is no bug bounty, but I'm grateful for every report. With your permission, I'll thank you by name in the commit and release notes of the fix.

## Machine-readable contact

Each site publishes this contact in [`/.well-known/security.txt`](/.well-known/security.txt) ([RFC 9116](https://www.rfc-editor.org/rfc/rfc9116)).

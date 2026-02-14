⚠️ **WARNING:** This repository may get squashed and force-pushed if the [GordianOpenIntegrity](https://github.com/Stream44/t44-blockchaincommons.com) implementation must change in incompatible ways. Keep your diffs until the **GordianOpenIntegrity** system is stable.

🔷 **Open Development Project:** The implementation is a preview release for community feedback.

⚠️ **Disclaimer:** Under active development. Code has not been audited, APIs and interfaces are subject to change.

Terminal44 Workspace Starter
===

This workspace contains pre-built applications to get started with the [Terminal44 Workspace Foundation](https://github.com/Stream44/t44) in a matter of minutes.

Status
---

This project is in **early development** and not ready for production use. Everything is subject to change although you should be able to refactor your codebase using AI to keep up if needed.

For now it is best used for small projects and exploration in non-mission critical settings.

Get in touch at [discord.gg](https://discord.gg/9eBcQXEJAN) ([Stream44.Studio](https://Stream44.Studio) server) if you are running it and need support.

Requirements
---

*Tested on macOS so far.*

- [bun](https://bun.sh)
- Optional
  - [vercel.com](https://vercel.com) account
  - [bunny.net](https://bunny.net/) account
  - [npmjs.com](https://npmjs.com/) account
  - [github.com](https://github.com/) account

Usage
---

Clone the repository:

```
git clone git@github.com:Stream44/t44-starter.git
cd t44-starter
```

Install dependencies:

```
bun install
```

Activate workspace:

```
source .workspace/bin/activate
```

- You are now ready to run examples.
- You will be prompted for configuration details as needed.

Play with example:

```
dev 02-next-hono
```

All workspace commands:

```
help
```


Examples
===

- **01-static-simple** - A single static page.
  - Frameworks: *none*
  - Providers: `vercel.com`

- **02-next-hono** - A simple one-page application.
  - Frameworks: `next`, `hono`
  - Providers: `bunny.net`


Reference Material
===

- Frameworks
  - [next](https://nextjs.org/)
  - [hono](https://hono.dev/)

- Providers
  - [vercel.com](https://vercel.com)
  - [bunny.net](https://bunny.net/)


Provenance
===

[![Gordian Open Integrity](https://github.com/Stream44/t44-starter/actions/workflows/gordian-open-integrity.yaml/badge.svg)](https://github.com/Stream44/t44-starter/actions/workflows/gordian-open-integrity.yaml?query=branch%3Amain) [![DCO Signatures](https://github.com/Stream44/t44-starter/actions/workflows/dco.yaml/badge.svg)](https://github.com/Stream44/t44-starter/actions/workflows/dco.yaml?query=branch%3Amain)

Repository DID: `did:repo:17180489989bf9877f91739cd0c3d4e1985fca0a`

<table>
  <tr>
    <td><strong>Inception Mark</strong></td>
    <td><img src=".o/GordianOpenIntegrity-InceptionLifehash.svg" width="64" height="64"></td>
    <td><strong>Current Mark</strong></td>
    <td><img src=".o/GordianOpenIntegrity-CurrentLifehash.svg" width="64" height="64"></td>
    <td>Trust established using<br/><a href="https://github.com/Stream44/t44-blockchaincommons.com">Stream44/t44-BlockchainCommons.com</a></td>
  </tr>
</table>

(c) 2026 [Christoph.diy](https://christoph.diy) • Code: `MIT` • Text: `CC-BY` • Created with [Stream44.Studio](https://Stream44.Studio)

# Fikret İmamoğlu

<p align="left">
  <a href="https://www.npmjs.com/~fibilisim"><img src="https://img.shields.io/badge/NPM-@fibilisim-CB3837?style=flat-square&logo=npm&logoColor=white" alt="NPM" /></a>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MCP-Agent_Tooling-6E56CF?style=flat-square" alt="MCP and Agent Tooling" />
  <img src="https://img.shields.io/badge/Open_Source-Maintainer-2EA44F?style=flat-square" alt="Open Source Maintainer" />
</p>

Open-source maintainer and contributor focused on **AI/agent tooling, TypeScript developer infrastructure, MCP integrations, and practical verification workflows**.

I build small, auditable tools and contribute tested fixes upstream when I find concrete problems.

---

## 🚧 Current Work

### [`LeanAgents`](https://github.com/Fibilisim-Tekno/leanagents) — selective coding workflows

[![CI](https://github.com/Fibilisim-Tekno/leanagents/actions/workflows/ci.yml/badge.svg)](https://github.com/Fibilisim-Tekno/leanagents/actions/workflows/ci.yml)
![Version](https://img.shields.io/badge/version-v0.1.0--alpha.1-orange?style=flat-square)
[![License](https://img.shields.io/github/license/Fibilisim-Tekno/leanagents?style=flat-square)](https://github.com/Fibilisim-Tekno/leanagents/blob/main/LICENSE)

A selective agent/context workflow for coding tasks. Instead of loading every role and rule for every task, LeanAgents routes explicit task facts, prepares only the needed instruction set, and records review/test evidence.

**Current alpha includes:** task routing, context preparation, TypeScript review, bounded fix/apply flow, token-budget checks, benchmark tooling, and editor bundles for **Codex, Kiro, Cursor, and Antigravity**.

Codex bootstrap loading and the bounded review/fix flow have been exercised with the real Codex CLI. Other editor targets currently have format-level validation and remain on the roadmap for native runtime verification.

---

## 📦 Maintained Open Source Projects

### [`EnvForge`](https://github.com/Fibilisim-Tekno/envforge)

[![npm version](https://img.shields.io/npm/v/@fibilisim/envforge?style=flat-square)](https://www.npmjs.com/package/@fibilisim/envforge)
[![CI](https://github.com/Fibilisim-Tekno/envforge/actions/workflows/ci.yml/badge.svg)](https://github.com/Fibilisim-Tekno/envforge/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/Fibilisim-Tekno/envforge?style=flat-square)](https://github.com/Fibilisim-Tekno/envforge/blob/main/LICENSE)

Zero-config local SaaS mock engine and environment synthesizer. It can generate local development credentials and mock common service surfaces so repositories can be exercised without real API keys or paid accounts.

`npx @fibilisim/envforge`

### [`trtext`](https://github.com/Fibilisim-Tekno/trtext)

[![npm version](https://img.shields.io/npm/v/trtext?style=flat-square)](https://www.npmjs.com/package/trtext)
[![CI](https://github.com/Fibilisim-Tekno/trtext/actions/workflows/ci.yml/badge.svg)](https://github.com/Fibilisim-Tekno/trtext/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/Fibilisim-Tekno/trtext?style=flat-square)](https://github.com/Fibilisim-Tekno/trtext/blob/main/LICENSE)

Zero-dependency Turkish text utilities for JavaScript/TypeScript: locale-correct case conversion, folding, slugs, and collation.

`npm i trtext`

---

## 🛠️ Selected Upstream Contributions

| Project | Contribution | Status |
| --- | --- | --- |
| [`ClaudeLint`](https://github.com/pdugan20/claudelint) | [#222](https://github.com/pdugan20/claudelint/pull/222) — fixed SessionStart hook paths containing spaces/non-ASCII characters and added regression coverage | ✅ Merged |
| [`ECC`](https://github.com/affaan-m/ECC) | [#3111](https://github.com/affaan-m/ECC/pull/3111) — MCP `notifications/initialized` metadata compatibility with six regression cases | 🟡 Open |
| [`KTX`](https://github.com/Kaelio/ktx) | [#368](https://github.com/Kaelio/ktx/pull/368) — TTY/raw-mode fix so `ktx ingest` remains interruptible with Ctrl-C, plus regression tests | 🟡 Open |
| [`LangWatch`](https://github.com/langwatch/langwatch) | [#8125](https://github.com/langwatch/langwatch/pull/8125) — distinguish unevaluated completed runs from actual passes, with tests | 🟡 Open |
| [`SpotifyScraper`](https://github.com/AliAkhtari78/SpotifyScraper) | [#161](https://github.com/AliAkhtari78/SpotifyScraper/pull/161), [#162](https://github.com/AliAkhtari78/SpotifyScraper/pull/162) — MCP host setup and migration documentation | 🟡 Open |

I prefer scoped contributions with a reproducible failure, explicit limits, and regression coverage where practical.

---

## 🔭 Focus

- **AI & agent tooling:** selective context, code review, MCP, verification workflows
- **Developer experience:** CLI tools, local-first infrastructure, deterministic behavior
- **Testing & evaluation:** regression tests, benchmark methodology, measurable limits
- **Open source:** maintain small tools and contribute focused fixes upstream

---

## 📬 Contact

- **NPM:** [@fibilisim](https://www.npmjs.com/~fibilisim)
- **Email:** [coldbira@gmail.com](mailto:coldbira@gmail.com)

<details>
<summary>🇹🇷 Türkçe kısa özet</summary>

Açık kaynak geliştirici ve maintainer olarak ağırlıklı olarak **AI ajan araçları, TypeScript, MCP, CLI ve doğrulama/test altyapıları** üzerinde çalışıyorum.

Şu an ana geliştirme projem [`LeanAgents`](https://github.com/Fibilisim-Tekno/leanagents). Bunun yanında [`EnvForge`](https://github.com/Fibilisim-Tekno/envforge) ve [`trtext`](https://github.com/Fibilisim-Tekno/trtext) projelerini sürdürüyorum; farklı açık kaynak projelerine de testli hata düzeltmeleri ve dokümantasyon katkıları gönderiyorum.

</details>

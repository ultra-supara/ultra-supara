<div align="center">

# [atsushi sada](https://blackhat.com/us-26/arsenal/schedule/presenters.html#atsushi-sada-52831)

### Security Engineer — Static Analysis · Malware & Ransomware in Cloud· Software Supply-Chain Security

> *Code wins arguments.* I build the tools that break and defend the software supply chain.

<a href="https://speakerdeck.com/4su_para"><img src="https://img.shields.io/badge/Speaker_Deck-009287?style=flat-square&logo=speakerdeck&logoColor=white" alt="Speaker Deck"/></a>
<a href="https://zenn.dev/ultrasupara"><img src="https://img.shields.io/badge/Zenn-3EA8FF?style=flat-square&logo=zenn&logoColor=white" alt="Zenn"/></a>
<a href="https://www.linkedin.com/in/atsushi-sada-a07736272/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://www.blackhat.com/asia-25/arsenal/schedule/presenters.html#sada-atsushi-49627"><img src="https://img.shields.io/badge/Speaker_Profile-000000?style=flat-square&logo=hackthebox&logoColor=white" alt="Speaker Profile"/></a>

<br/>

<img src="https://img.shields.io/badge/Black_Hat-USA_2026-EE3124?style=flat-square" alt="Black Hat USA 2026"/>
<img src="https://img.shields.io/badge/DEF_CON-34-1a1a1a?style=flat-square" alt="DEF CON 34"/>
<img src="https://img.shields.io/badge/Black_Hat-Asia_2025-EE3124?style=flat-square" alt="Black Hat Asia 2025"/>
<img src="https://img.shields.io/badge/JSAC-2025-005baa?style=flat-square" alt="JSAC 2025"/>

</div>

---

### 🔭 About

- 🐤 **Security Engineer** at a fintech startup — I ship security tooling and research offensive techniques end to end.
- ⭐️ **Focus** — Enterprise Security (AWS, GitHub ecosystem, MDM, EDR) · Security Dev Tooling (Static Analysis, Malware, CloudSec)・Offensive Security（FireFox）
- 🎤 Speaker at **Black Hat USA 2026**, **DEF CON 34**, **Black Hat Asia 2025**, and **JSAC 2025**.
- 🎓 B.S. in Computer Science & Engineering, [Ritsumeikan University](https://www.ritsumei.ac.jp/) ('24).

<div align="center">
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ultra-supara&theme=github#gh-light-mode-only" alt="GitHub stats"/>
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ultra-supara&theme=github#gh-light-mode-only" alt="Top languages"/>
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ultra-supara&theme=github_dark#gh-dark-mode-only" alt="GitHub stats"/>
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ultra-supara&theme=github_dark#gh-dark-mode-only" alt="Top languages"/>
</div>

---

### 🛠️ Current Development

#### [sisakulint](https://github.com/ultra-supara/sisakulint) &nbsp;<sub>'23 – present</sub>

CI-friendly static linter with autofix, SAST, and semantic analysis for **GitHub Actions**. It outperforms GitHub's official tool (CodeQL) in both speed and coverage for Actions-specific vulnerabilities.

🎤 [DEF CON 34 Demo Labs](https://www.blackhat.com/asia-25/arsenal/schedule/#sisakulint---ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions-43229) ('26) · [Black Hat Asia Arsenal](https://www.blackhat.com/asia-25/arsenal/schedule/#sisakulint---ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions-43229) ('25) · 📖 [Docs](https://sisaku-security.github.io/lint/) · ▶️ [Demo video](https://www.youtube.com/watch?v=DhgqKOmzLSk)

| Benchmark | Result |
|---|---|
| GitHub Security Lab (GHSL) advisories | **100% (18/18)** |
| GitHub Security Advisories (GHSA) | **81.6% (31/38)** |
| Auto-fix coverage | **38+ rules** |

<details>
<summary><b>Detection categories &amp; differentiators</b></summary>

| Detection Category | Rules |
|---|---|
| Code Injection & Expression Safety | 9 |
| Supply Chain & Dependency Security | 7 |
| Credential & Secret Protection | 7 |
| Pipeline Poisoning & Artifact Integrity | 8 |
| Triggers & Access Control | 7 |
| Workflow Quality & Best Practices | 8 |

**Differentiators**
- Taint propagation across steps, jobs, and reusable workflows (unique capability)
- Multi-step semantic analysis, not single-step pattern matching
- Validated against real-world vulns in PX4-Autopilot, weaviate, nrwl/nx, ag-grid, and more

</details>

#### [MachStealer](https://github.com/ultra-supara/MachStealer) &nbsp;<sub>'25 – present</sub>

Forensic Tool & reproducing the credential-harvesting pipeline shared by macOS infostealer families (AMOS, Poseidon, Banshee, Cthulhu, Cuckoo). Apple Silicon only. **No exfiltration by design.**

🎤 [Black Hat USA Arsenal · Malware Track](https://blackhat.com/us-26/arsenal/schedule/?track[]=malware#machstealerone-pipeline-behind-every-macos-infostealer-52134) ('26) · ▶️ [Research walkthrough (EN)](https://www.youtube.com/watch?v=mzyQ9-8qsFg) · ▶️ [ずんだもん解説 (JP)](https://www.youtube.com/watch?v=9KyRqy37Iao)

---

### 🎯 Offensive Security — CVEs

Credited vulnerability research: a transpiler-runtime audit of enspirit/elo and reported memory-safety / mitigation-bypass issues in **Mozilla Firefox**.

| CVE | Severity | Target | Vulnerability | Advisory |
|:---|:---:|:---|:---|:---:|
| **CVE-2026-44266** | ![Critical](https://img.shields.io/badge/Critical-9.8-E5484D?style=flat-square) | Elo · Ruby backend | RCE via unescaped `#{...}` interpolation in emitted string literals & subtype-constraint labels | [🔗](https://github.com/enspirit/elo/security/advisories/GHSA-7w38-ggh5-v542) |
| **CVE-2026-44267** | ![Critical](https://img.shields.io/badge/Critical-9.8-E5484D?style=flat-square) | Elo · JS emitter | Sandbox escape to arbitrary Node.js / browser code execution via unfiltered `.constructor` member access | [🔗](https://github.com/enspirit/elo/security/advisories/GHSA-33r5-xmm8-v6x5) |
| **CVE-2026-44265** | ![High](https://img.shields.io/badge/High-7.4-F76808?style=flat-square) | Elo · all backends | Code injection via unvalidated emission of programmatic AST fields (literal, identifier, member-access, object key, datapath, lambda param) | [🔗](https://github.com/enspirit/elo/security/advisories/GHSA-x9rp-7wh3-2rj5) |
| **CVE-2026-12307** | ![Moderate](https://img.shields.io/badge/Moderate-FFB224?style=flat-square) | Firefox 152 | Memory-safety vulnerability (credited reporter) | [🔗](https://www.mozilla.org/en-US/security/advisories/mfsa2026-57/#CVE-2026-12307) |
| **CVE-2026-8969** | ![Low](https://img.shields.io/badge/Low-9BA1A6?style=flat-square) | Firefox 151 | Mitigation bypass in the DOM security component | [🔗](https://www.mozilla.org/en-US/security/advisories/mfsa2026-46/#CVE-2026-8969) |

<sub>Firefox entries credit **Atsushi Sada** as reporter ([Bug 2038133](https://bugzilla.mozilla.org/show_bug.cgi?id=2038133), [Bug 2031123](https://bugzilla.mozilla.org/show_bug.cgi?id=2031123)).</sub>

---

### 🎤 Talks & Recognition

| Year | Event | Topic / Role | |
|:---:|---|---|:---:|
| 2026 | Black Hat USA Arsenal · Malware Track | MachStealer | [🔗](https://blackhat.com/us-26/arsenal/schedule/?track[]=malware#machstealerone-pipeline-behind-every-macos-infostealer-52134) |
| 2026 | DEF CON 34 Demo Labs | sisakulint | [🔗](https://www.blackhat.com/asia-25/arsenal/schedule/#sisakulint---ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions-43229) |
| 2026 | セキュリティ・キャンプ全国大会 · Class D2 | AIシステムにおける脅威対策とガバナンス実践 — Instructor | [🔗](https://www.ipa.go.jp/jinzai/security-camp/zenkoku_program.html#classd) |
| 2025 | Black Hat Asia Arsenal · Code Assessment　Track | sisakulint　| [🔗](https://speakerdeck.com/4su_para/sisakulint-ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions) |
| 2025 | JSAC 2025 | MITRE ATT&CK tooling via multi-LLM agents + RAG — LT | [🔗](https://speakerdeck.com/4su_para/jsac-2025-lt-introduction-to-mitre-att-and-ck-utilization-tools-by-multiple-llm-agents-and-rag) |
| 2025 | セキュリティ若手の会 Workshop | LLM Safety Hands-On — Instructor | [🔗](https://sec-wakate.connpass.com/event/357530/) |
| 2025 | Findy TECH BATON #6 | npm supply-chain attacks — Speaker | [🔗](https://speakerdeck.com/4su_para/npmpatukezinosapuraitienwen-ti) |
| 2024 | Security-JAWS #35 | Malware & content-tampering defense in the cloud | [🔗](https://speakerdeck.com/4su_para/security-jaws-di-35hui-mian-qiang-hui-kuraudoniokerumaruueayakontentugai-zanhenodui-ce) |
| 2024 | Closed Career Event @ RiST | Risk-based security operations | [🔗](https://speakerdeck.com/4su_para/toaruyuzaqi-ye-niokerurisukubesudekao-erusekiyuriteiye-wu-noohua-si) |

> **🎓 セキュリティ・キャンプ2026 全国大会 · クラスD「AIセキュリティクラス」— [Class D2「AIシステムにおける脅威対策とガバナンス実践」](https://www.ipa.go.jp/jinzai/security-camp/zenkoku_program.html#classd)** （2026-08-11 · @HikaruEgashira との共同講師）
>
> LLM / AI エージェントを社会実装する立場から、AI 固有の脅威（プロンプトインジェクション、データ汚染など）を技術的に扱いつつ、実装だけでは消しきれないリスクに対して制度設計・ガバナンス・戦略まで含めた包括的な対策を演習形式で扱うハンズオン講義。

---

### 🌐 Community

- **[セキュリティ若手の会](https://sec-wakate.connpass.com/)** — Co-Founder & Host ('24 – '26)
- **[Security Camp](https://www.security-camp.or.jp/)** — AI Security Class Instructor ('26), Web Security Tutor ('23), Attendee ('21)
- **[SecHack365](https://sechack365.nict.go.jp/)** — Philosophy-Driven Course/思索駆動コース Trainee ('23)
- **[RiST](https://risec.github.io/)** — Member ('20 – '22)

<details>
<summary>📰 セキュリティ若手の会 — articles &amp; event reports</summary>

- [スポンサー発表: セキュリティエンジニアの仕事・業界をつなぐ「セキュリティ若手の会」](https://wakate.org/2025/08/18/58th-general/)
- [セキュリティ・キャンプアワード2025 コミュニティ紹介資料](https://www.docswell.com/s/secwakate/52267G-2025-05-05-202054)
- 開催記: [第4回](https://zenn.dev/sec_wakate/articles/999fd1fb2917f1) · [第3回](https://zenn.dev/sec_wakate/articles/e5f8e9d95c9eff) · [第2回](https://zenn.dev/sec_wakate/articles/3891a59ab0b4fb) · [第1回](https://zenn.dev/sec_wakate/articles/acd5935f189460)
- [若手セキュリティエンジニアのインタビュー記事「asu_para」](https://zenn.dev/sec_wakate/articles/f6f7c3e710ea2f)
- [活動について](https://zenn.dev/sec_wakate/articles/97fbca58f0e8d5)

</details>

---

### ✍️ Tech Blog

- [VSCodeで生産性を上げる](https://zenn.dev/ultrasupara/articles/174429511504c7) — **15,000+ Views**
- [grub rescue モードから抜ける](https://zenn.dev/ultrasupara/articles/dcd4b7a6d95729) — **10,000+ Views**
- [macOS向けInfoStealerを技術的に解説してみた](https://zenn.dev/finatext/articles/1c1a2c78531057) — *Finatext Tech Blog*
- [問題解決のためAWSドキュメントをどう追従するか](https://zenn.dev/ultrasupara/articles/6613ff64760fe4)
- [GoreleaserとGitHub ActionsでプライベートリポジトリのCLIツールをbrewに公開する](https://zenn.dev/ultrasupara/articles/0efd250afc7b17)
- [Kali LinuxでNvidia-driverを用いてデュアルモニターをセットアップする](https://zenn.dev/ultrasupara/articles/3235fc0ed0e509)

---

### 🧰 Tech Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Vagrant](https://img.shields.io/badge/Vagrant-1868F2?style=flat-square&logo=vagrant&logoColor=white)

**Security Tooling**

![YARA](https://img.shields.io/badge/YARA-0e7fc0?style=flat-square)
![Open Policy Agent](https://img.shields.io/badge/Open_Policy_Agent-7D9199?style=flat-square&logo=openpolicyagent&logoColor=white)
![gVisor](https://img.shields.io/badge/gVisor-1a73e8?style=flat-square)
![Jamf](https://img.shields.io/badge/Jamf-4A90D9?style=flat-square)
![Microsoft Intune](https://img.shields.io/badge/Intune-0078D4?style=flat-square&logo=microsoft&logoColor=white)

# Code wins arguments👋
- 🐤 Welcome to my GitHub Pages, **[atsushi, sada](https://www.blackhat.com/asia-25/arsenal/schedule/presenters.html#sada-atsushi-49627)** here!
- 🔭 I’m currently working as a **Security Engineer** at fintech startups!
- ⭐️ Focus
    - Cloud Security (aws, GitHub Ecosystem)
    - Enterprise Security (Jamf, Intune, EDR)
    - Security Dev Tool (Static Analysis全般, Malware, CloudSec)
- 🎤 Presentation
    - BlackHat USA 2026 Arsenal (Malware Track) [link](https://blackhat.com/us-26/arsenal/schedule/?track[]=malware#machstealerone-pipeline-behind-every-macos-infostealer-52134)
    - BlackHat ASIA 2025 Arsenal (Code Assesment Track) [link](https://www.blackhat.com/asia-25/arsenal/schedule/#sisakulint---ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions-43229)

### ⭐️ Current Development

- **[sisakulint](https://github.com/ultra-supara/sisakulint)** ('23-present)
    - 🎤 *[Black Hat Asia Arsenal Web Page](https://www.blackhat.com/asia-25/arsenal/schedule/#sisakulint---ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions-43229) ('25)*
    - [document pages](https://sisaku-security.github.io/lint/)
    - [sisakulint — SAST for GitHub Actions: 52 Rules, 38 Auto-Fix & Taint Tracking Engine - YouTube](https://www.youtube.com/watch?v=DhgqKOmzLSk)
    - CI-Friendly static linter with autofix, SAST and semantic analysis for **GitHub Actions**!
    - sisakulint outperforms GitHub official tool:CodeQL in both speed and coverage for Actions-specific vulnerabilities.
  
  | Benchmark | Result |
  |---|---|
  | GitHub Security Lab (GHSL) advisories | **100% (18/18)** |
  | GitHub Security Advisories (GHSA) | **81.6% (31/38)** |
  | Auto-fix coverage | **38+ rules** |

  **Detection categories**
  | Category | Rules |
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
  - Validated against real-world vulns in PX4-Autopilot, weaviate, nrwl/nx, ag-grid, etc.
 
- **[MachStealer](https://github.com/ultra-supara/MachStealer)** (‘25-present)
    - 🎤 *[Black Hat USA Arsenal Web Page](https://blackhat.com/us-26/arsenal/schedule/?track[]=malware#machstealerone-pipeline-behind-every-macos-infostealer-52134) ('26)*
    - Open-source PoC reproducing the credential harvesting pipeline shared by macOS infostealer families (AMOS, Poseidon, Banshee, Cthulhu, Cuckoo). Apple Silicon only. No exfiltration by design.
    - [MachStealer: The Shared Pipeline Behind Every macOS Infostealer — Security Research PoC - YouTube](https://www.youtube.com/watch?v=mzyQ9-8qsFg)
    - [【ずんだもん解説】MachStealer：全macOSインフォスティーラーに共通する攻撃パイプラインを解剖する - YouTube](https://www.youtube.com/watch?v=9KyRqy37Iao)

### 💬 Regarding past achievements
- **Closed Career Event at RiST**: ('24)
    - [とあるユーザー企業におけるリスクベースで考えるセキュリティ業務のお話し](https://speakerdeck.com/4su_para/toaruyuzaqi-ye-niokerurisukubesudekao-erusekiyuriteiye-wu-noohua-si)
    
- **[Security-JAWS](https://s-jaws.connpass.com/) #35**: (‘24)
    - [クラウドにおけるマルウェアやコンテンツ改ざんへの対策](https://speakerdeck.com/4su_para/security-jaws-di-35hui-mian-qiang-hui-kuraudoniokerumaruueayakontentugai-zanhenodui-ce)
 
- **JSAC 2025**: LT Speaker ('25)
    - [JSAC 2025 LT Introduction to MITRE ATT&CK utilization tools by multiple LLM agents and RAG](https://speakerdeck.com/4su_para/jsac-2025-lt-introduction-to-mitre-att-and-ck-utilization-tools-by-multiple-llm-agents-and-rag)

- **Black Hat Asia Arsenal**: Presenter ('25)
    - [BlackHat Asia 2025 Arsenal Slides: sisakulint - CI-Friendly static linter with SAST, semantic analysis for GitHub Actions](https://speakerdeck.com/4su_para/sisakulint-ci-friendly-static-linter-with-sast-semantic-analysis-for-github-actions)
 
- **セキュリティ若手の会(ワークショップ&交流会)**: Workshop Instructor ('25)
    - [LLM Safety Hands On / LLMセキュリティの攻防入門 〜ガバナンスと脅威対策〜](https://sec-wakate.connpass.com/event/357530/#:~:text=1%EF%BC%9ALLM%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3%E3%81%AE%E6%94%BB%E9%98%B2%E5%85%A5%E9%96%80%20%E3%80%9C%E3%82%AC%E3%83%90%E3%83%8A%E3%83%B3%E3%82%B9%E3%81%A8%E8%84%85%E5%A8%81%E5%AF%BE%E7%AD%96%E3%80%9C)

- **Findy TECH BATON シリーズ第6弾！「あなたの知らない ”サプライチェーン攻撃”を語る セキュリティ Night」** ('25)
    - [npmパッケージのサプライチェーン問題](https://speakerdeck.com/4su_para/npmpatukezinosapuraitienwen-ti)

- **Black Hat USA Arsenal**: Presenter ('26)

- **Secueity Camp**: Instructor ('26)

### 💬 Security Community
- **[RiST](https://risec.github.io/)**: member ('20-22)
- **[Security Camp](https://www.security-camp.or.jp/)**: Attendee (‘21), Tutor at Web Security Class (‘23), Instructor at AI Security Class ('26)
- **[SecHack365](https://sechack365.nict.go.jp/)**: Philosophy Driven Course Trainee ('23)
- **[セキュリティ若手の会](https://sec-wakate.connpass.com/)**: Co-Founder & Host ('24-26)
    - [セキュリティ若手の会の活動について](https://zenn.dev/sec_wakate/articles/97fbca58f0e8d5)
    - [セキュリティ・キャンプアワード2025:「セキュリティ若手の会」コミュニティ紹介資料](https://www.docswell.com/s/secwakate/52267G-2025-05-05-202054)
    - [スポンサー発表: セキュリティエンジニアの仕事・業界をつなぐ「セキュリティ若手の会」](https://wakate.org/2025/08/18/58th-general/#:~:text=%E3%82%B9%E3%83%9D%E3%83%B3%E3%82%B5%E3%83%BC%E7%99%BA%E8%A1%A8%3A%20%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%AE%E4%BB%95%E4%BA%8B%E3%83%BB%E6%A5%AD%E7%95%8C%E3%82%92%E3%81%A4%E3%81%AA%E3%81%90%E3%80%8C%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3%E8%8B%A5%E6%89%8B%E3%81%AE%E4%BC%9A%E3%80%8D%20(%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3%E8%8B%A5%E6%89%8B%E3%81%AE%E4%BC%9A%20%E6%B1%9F%E9%A0%AD%20%E8%BC%9D%20%E6%A7%98%20%E4%BD%90%E7%94%B0%20%E6%B7%B3%E5%8F%B2%20%E6%A7%98%20pizzacat83%E6%A7%98))
    - [イベント開催記「第1回 セキュリティ若手の会（LT&交流会）」](https://zenn.dev/sec_wakate/articles/acd5935f189460)
    - [イベント開催記「第2回 セキュリティ若手の会（LT&交流会）」](https://zenn.dev/sec_wakate/articles/3891a59ab0b4fb)
    - [イベント開催記「第3回 セキュリティ若手の会（ワークショップ&交流会）」](https://zenn.dev/sec_wakate/articles/e5f8e9d95c9eff)
    - [イベント開催記「第4回 セキュリティ若手の会（LT&交流会）」](https://zenn.dev/sec_wakate/articles/999fd1fb2917f1)
    - インタビュー記事
        - [若手セキュリティエンジニアのインタビュー記事2「asu_para」](https://zenn.dev/sec_wakate/articles/f6f7c3e710ea2f)

### 🐤 Tech Blog
- [VSCodeで生産性を上げる](https://zenn.dev/ultrasupara/articles/174429511504c7) **15,000+ Views!**
- [grub rescue モードから抜ける](https://zenn.dev/ultrasupara/articles/dcd4b7a6d95729) **10,000+ Views!**
- [macOS向けInfoStealerを技術的に解説してみた](https://zenn.dev/finatext/articles/1c1a2c78531057) **Finatext Tech Blog!**
- [問題解決のためAWSドキュメントをどう追従するか](https://zenn.dev/ultrasupara/articles/6613ff64760fe4)
- [GoreleaserとGitHub ActionsでプライベートリポジトリのCLIツールをbrewに公開する](https://zenn.dev/ultrasupara/articles/0efd250afc7b17)
- [Kali LinuxでNvidia-driverを用いてデュアルモニターをセットアップする](https://zenn.dev/ultrasupara/articles/3235fc0ed0e509)

### ⭐️ Education
- **[Ritsumeikan University](https://www.ritsumei.ac.jp/)** ('20-'24)
    - Bachelor of Computer Science and Engineering (March, '24)

## Profile
<div align="left">
  <h3>Languages and Tools:</h3>
  <div> 
    <h5>Programming Languages</h5>
    <a href="https://www.python.org" target="_blank"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
    </a>
  </div>
  
  <div>
    <h5>Development</h5>
    <a href="https://go.dev" target="_blank"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> 
    </a>
  </div>
  
  <div>
    <h5>infra</h5>
    <a href="https://aws.amazon.com/jp/" target="_blank"> 
      <img src="https://github.com/ultra-supara/ultra-supara/assets/67861004/2bc13696-620c-4967-8d12-641fd7823f69" alt="aws" width="40" height="40"/> 
    </a> 
  </div>
  
  <div>
    <h5>Development Tools</h5>
    <a href="https://www.linux.org/" target="_blank"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> 
    </a>
    <a href="https://www.docker.com/" target="_blank"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> 
    </a> 
    <a href="https://www.vagrantup.com/" target="_blank"> 
      <img src="https://www.vectorlogo.zone/logos/vagrantup/vagrantup-icon.svg" alt="vagrant" width="40" height="40"/> 
    </a>
    <a href="https://www.yara.com" target="_blank"> 
      <img src="https://logos-download.com/wp-content/uploads/2016/11/Yara_logo_logotype.png" alt="yara" width="40" height="40"/> 
    </a> 
    <a href="https://www.openpolicyagent.org" target="_blank"> 
      <img src="https://www.vectorlogo.zone/logos/openpolicyagent/openpolicyagent-icon.svg" alt="openpolicyagent" width="40" height="40"/> 
    </a> 
    <a href="https://gvisor.dev" target="_blank"> 
      <img src="https://www.gstatic.com/devopsconsole/images/oss/icons/gvisor_logo.svg" alt="gVisor" width="40" height="40"/> 
    </a> 
  </div>
</div>

# AI Weekly Report

## 2026-04-02

### 1. 生成AIの新モデル・新機能リリース

- **OpenAI GPT-5.4** が2026年3月5日にリリース。GPT-5.4 Thinking・GPT-5.4 Proの2バリアント構成。APIで最大100万トークンのコンテキストウィンドウに対応。前世代比で事実誤認が33%減少、回答全体のエラー率が18%低下
  - [Introducing GPT-5.4 | OpenAI](https://openai.com/index/introducing-gpt-5-4/)
  - [OpenAI launches GPT-5.4 | TechCrunch](https://techcrunch.com/2026/03/05/openai-launches-gpt-5-4-with-pro-and-thinking-versions/)
- **OpenAI GPT-5.4** が3月29日にネイティブコンピュータ操作機能を追加。OSWorld-Verifiedベンチマークで75%を達成（人間平均72%を超過）
  - [GPT-5.4 Computer Use Release](https://www.roborhythms.com/gpt-5-4-release-march-2026/)
- **Google Gemini 3** のPro、Flash、Flash-Liteが段階的にリリース
  - [Google Cloud 最新生成AI活用事例120社](https://cloud.google.com/blog/ja/products/ai-machine-learning/120-case-studies-on-the-latest-generative-ai-applications-released?hl=ja)

### 2. AI駆動開発ツールの動向

- **Claude Code** がSWE-bench Verifiedで80.8%を達成。Opus 4.6で1Mコンテキストが標準に。8ヶ月で最も使われるAIコーディングツールに成長
- **GitHub Copilot CLI** がGA（一般提供）に到達
- **Windsurf** がArena Modeを投入
- プロ開発者の主流は「日常編集にCursor/Copilot + 複雑タスクにClaude Code」の使い分けスタイル
  - [AIコーディングツール最新比較 2026春（Qiita）](https://qiita.com/ysshin/items/866b6feb7b3a33ab4171)
  - [Cursor vs Claude Code vs GitHub Copilot 2026](https://www.nxcode.io/resources/news/cursor-vs-claude-code-vs-github-copilot-2026-ultimate-comparison)
  - [Claude Code vs Cursor vs GitHub Copilot（DEV Community）](https://dev.to/alexcloudstar/claude-code-vs-cursor-vs-github-copilot-the-2026-ai-coding-tool-showdown-53n4)

### 3. AI関連の法規制・ガイドライン更新

- **EU AI法**: 2026年8月2日から本格適用開始予定。リスクベースアプローチで4段階のリスクレベルを設定
  - [EU AI規制法の解説（PwC Japan）](https://www.pwc.com/jp/ja/knowledge/column/awareness-cyber-security/generative-ai-regulation10.html)
- **日本 AI事業者ガイドラインv1.2**: 2026年3月31日に総務省・経済産業省が公表。AIエージェントとフィジカルAIが初めて規制対象に明記。Human-in-the-Loopの仕組み構築が事実上の必須要件に
  - [AI事業者ガイドラインv1.2解説（Uravation）](https://uravation.com/media/japan-ai-regulation-guideline-v12-2026/)
  - [AI事業者ガイドライン改定報道（トラベルボイス）](https://www.travelvoice.jp/20260331-159520)
- **日本 AI推進法**: 2025年成立。開発・活用促進と安全性確保の両立を目指す枠組み
- **米国**: 連邦レベルの包括規制はまだないが、AI行動計画・大統領令で国家戦略を明確化中
  - [AIのグローバル規制・政策動向レポート（荒木法律事務所）](https://arakiplaw.com/insight/2658/)

### 4. OWASP LLM Top 10 / AIセキュリティ動向

- **OWASP LLM Top 10 v2.0（2025版）** の主要リスク: プロンプトインジェクション、機密情報漏洩、サプライチェーン脆弱性、データ/モデル汚染、不適切な出力処理、過剰な権限付与、システムプロンプト漏洩、ベクトル/エンベディングの弱点、誤情報生成、無制限リソース消費
  - [OWASP LLM Top 10 公式](https://genai.owasp.org/llm-top-10/)
- **OWASP Top 10 for Agentic Applications 2026** が2025年12月10日に公開。100名超の専門家が協力し、自律型AIエージェント特有のセキュリティリスクを体系化。Palo Alto Networksなど大手セキュリティ企業も対応ガイドを公開
  - [OWASP Top 10 for Agentic Applications 公式](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)
  - [Palo Alto Networks 対応ブログ](https://www.paloaltonetworks.com/blog/cloud-security/owasp-agentic-ai-security/)
- プロンプトインジェクション（LLM01）が本番環境で最も悪用される脆弱性。特に外部コンテンツに敵対的指示を埋め込む間接型が深刻
  - [OWASP LLM Top 10: AI Security Risks 2026](https://elevateconsult.com/insights/owasp-llm-top-10-security-vulnerabilities-every-ai-developer-must-know-in-2026/)

### 5. 主要AIサービスの利用規約変更

- **Anthropic**: サポート対象外地域（中国等）からの間接利用を制限する規約更新。Claude Free/Pro/Maxユーザーのデータはデフォルトで学習利用される方式に変更（Team/Enterprise/APIは対象外）
  - [Anthropic利用規約更新（JOBIRUN）](https://jobirun.com/anthropic-strengthens-ai-security-by-updating-terms-of-service/)
  - [Anthropicプライバシーポリシー変更（ENSOU）](https://ensou.app/blog/anthropic-claude-terms-and-privacy-update-2025/)
- **OpenAI**: 2026年1月1日に利用規約を更新
  - [OpenAI Terms of Use](https://openai.com/policies/row-terms-of-use/)
- **Google**: Geminiが他社AIの履歴を取り込む新機能を発表（2026年3月第4週）
  - [2026年3月第4週 生成AI動向（フィデックス）](https://www.fidx.co.jp/%E3%80%902026%E5%B9%B43%E6%9C%88%E7%AC%AC4%E9%80%B1%E3%80%91openai%E3%83%BBgoogle%E3%83%BBanthropic%E7%94%9F%E6%88%90ai%E5%8B%95%E5%90%91%EF%BD%9Cgemini%E3%81%8C%E4%BB%96%E7%A4%BEai%E3%81%AE%E5%B1%A5/)

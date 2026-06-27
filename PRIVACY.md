# Sumifold プライバシーポリシー / Privacy Policy

**最終更新日 / Last updated: 2026-06-27**
**バージョン / Applies to: Sumifold 0.9.0 以降**

---

## 日本語

### 要約

**Sumifold はテレメトリ（利用状況の収集・送信）を一切行いません。** 唯一の外向き通信は、更新確認機能が GitHub に対して最新バージョン情報を照会する通信のみです。お客様が作成した文書・設定・クラッシュ情報は、すべてお客様の PC 内（ローカル）にのみ保存されます。

### 1. 収集しない情報

権利者（Takeshi Arai）は、本ソフトウェアを通じて以下を**収集・送信しません**。

- 個人を識別する情報
- お客様が編集・保存する文書の内容
- 利用統計・分析・行動ログ（テレメトリ）
- IP アドレス等の接続情報を権利者側で保持すること

### 2. 更新確認時の通信

本ソフトウェアは、起動時およびお客様が「更新を確認」を実行したときに、GitHub 上の公開リリース情報（`https://github.com/TakeshiArai-18/Sumifold` のリリース）へアクセスし、最新バージョン番号を照会します。

- この通信は GitHub のサーバーに対して行われ、GitHub のプライバシーポリシーが適用されます（接続に伴う IP アドレス等は GitHub 側で扱われます）。
- 権利者は、この照会に関するいかなる情報も収集・保持しません。
- 更新の**ダウンロードおよびインストールは、お客様が確認ダイアログで明示的に承認した場合にのみ**実行されます。

### 3. ローカルに保存される情報

以下の情報はお客様の PC 内にのみ保存され、外部に送信されることはありません。

| 種別 | 保存場所 |
| --- | --- |
| アプリ設定 | `%APPDATA%\com.takeshi.sumifold\` |
| クラッシュダンプ | `%APPDATA%\com.takeshi.sumifold\`（ローカル保存のみ。自動送信なし） |
| 診断トレースログ | `%APPDATA%\com.takeshi.sumifold\diagnostics\` |
| 自動保存・リカバリファイル | 編集中ファイルの近傍／一時領域 |

クラッシュ情報を権利者へ共有するかどうかはお客様の任意です（手動でファイルを送付いただく場合に限ります）。

### 4. 第三者への提供

権利者は、お客様の情報を第三者に販売・提供しません（そもそも情報を収集していません）。

### 5. お問い合わせ

本ポリシーに関するお問い合わせは `tsukuru.llc.28@gmail.com` までご連絡ください。

### 6. 改訂

本ポリシーは予告なく改訂される場合があります。重要な変更は GitHub リリースの告知で周知します。

---

## English

### Summary

**Sumifold performs no telemetry whatsoever.** The only outbound communication is the update-check feature querying GitHub for the latest version. All your documents, settings, and crash information are stored solely on your local PC.

### 1. Information We Do NOT Collect

The Licensor (Takeshi Arai) does **not** collect or transmit any of the following through the Software:

- personally identifiable information;
- the content of documents you edit or save;
- usage statistics, analytics, or behavioral logs (telemetry); or
- connection information such as IP addresses retained on the Licensor's side.

### 2. Communication During Update Checks

At startup and when you choose "Check for updates", the Software accesses the public release information on GitHub (releases of `https://github.com/TakeshiArai-18/Sumifold`) to query the latest version number.

- This communication is made to GitHub's servers and is subject to GitHub's privacy policy (IP address and similar data accompanying the connection are handled by GitHub).
- The Licensor collects and retains no information about this query.
- **Downloading and installing an update occurs only with your explicit approval** in the confirmation dialog.

### 3. Information Stored Locally

The following is stored only on your PC and is never transmitted externally:

| Type | Location |
| --- | --- |
| Application settings | `%APPDATA%\com.takeshi.sumifold\` |
| Crash dumps | `%APPDATA%\com.takeshi.sumifold\` (local only; no automatic upload) |
| Diagnostic trace logs | `%APPDATA%\com.takeshi.sumifold\diagnostics\` |
| Autosave / recovery files | near the edited file / temporary area |

Whether to share crash information with the Licensor is entirely up to you (only if you manually send the files).

### 4. Disclosure to Third Parties

The Licensor does not sell or provide your information to third parties (no such information is collected in the first place).

### 5. Contact

For inquiries regarding this policy, contact `tsukuru.llc.28@gmail.com`.

### 6. Revisions

This policy may be revised without prior notice. Material changes will be announced in GitHub release notes.

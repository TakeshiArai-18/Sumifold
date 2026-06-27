# Sumifold

Windows 向けの Markdown エディタ。Mermaid / KaTeX / Shiki / Graphviz によるリッチプレビュー、
ワークスペース全文検索、自動保存・クラッシュリカバリを備えます。

A Markdown editor for Windows with rich preview (Mermaid / KaTeX / Shiki / Graphviz),
workspace-wide full-text search, autosave, and crash recovery.

> **公開ベータ / Public Beta — v0.9.0**
> 本リリースは**未署名**の公開ベータです。安定版（署名済み 1.0.0）は今後提供予定です。
> This release is an **unsigned** public beta. A signed stable release (1.0.0) is planned.

---

## 📥 ダウンロード / Download

最新版は [**Releases**](https://github.com/TakeshiArai-18/Sumifold/releases/latest) から
`Sumifold_x.y.z_x64-setup.exe`（NSIS インストーラ）を入手してください。

- 管理者権限は不要です（現在のユーザーにインストールされます / currentUser install）。
- インストール時にインターネット接続が必要な場合があります（WebView2 ランタイムの取得のため。最近の Windows には標準搭載されています）。

---

## ⚠️ SmartScreen 警告について / About the SmartScreen warning

本アプリは未署名のため、初回起動時に **Microsoft Defender SmartScreen** の警告が表示されることがあります。
これは未署名ソフトウェア全般に表示されるもので、ダウンロード実績が蓄積されると表示されなくなります。

Because this app is unsigned, **Microsoft Defender SmartScreen** may warn you on first run.
This is shown for unsigned software in general and disappears as download reputation accumulates.

**実行する手順 / How to run anyway:**

1. 警告ダイアログの「**詳細情報 / More info**」をクリック。
2. 表示された「**実行 / Run anyway**」をクリック。

> ⚠️ ダウンロードは必ずこの公式リリースページからのみ行ってください。
> Only download from this official releases page.

---

## 📦 winget でのインストール / Install via winget

winget 公開後（Phase 1b）は次のコマンドでインストールできます。

```powershell
winget install Takeshi.Sumifold
```

---

## 🔄 自動更新 / Auto-update

Sumifold は起動時に新しいバージョンの有無を確認し、見つかった場合は確認ダイアログを表示します。
「更新する」を選ぶとダウンロードして再起動します（**お客様の承認なしに自動更新はしません**）。
手動で確認したい場合は **ヘルプ > 更新を確認 / Help > Check for updates** から実行できます。

Sumifold checks for new versions at startup and shows a confirmation dialog if one is found.
Choosing "Update" downloads it and restarts (**it never updates without your approval**).
You can also check manually via **Help > Check for updates**.

---

## 🔐 プライバシー / Privacy

- **テレメトリは一切ありません。** 文書・設定・クラッシュ情報はすべてローカル（`%APPDATA%`）に保存されます。
- 唯一の外向き通信は、更新確認時に GitHub へ最新バージョンを照会する通信のみです。
- 詳細: [プライバシーポリシー / Privacy Policy](./PRIVACY.md)

- **No telemetry.** Documents, settings, and crash info are stored locally (`%APPDATA%`).
- The only outbound communication is querying GitHub for the latest version during update checks.

---

## 📄 ライセンス / License

本ソフトウェアはプロプライエタリ（All Rights Reserved）です。使用前に EULA をご確認ください。

- [使用許諾契約書 / EULA](./EULA.md)
- [第三者 OSS 表示 / Third-Party Notices](./THIRD-PARTY-NOTICES.txt)

---

## 💬 お問い合わせ / Contact

- 不具合報告・要望: [Issues](https://github.com/TakeshiArai-18/Sumifold/issues)
- その他のお問い合わせ: `tsukuru.llc.28@gmail.com`

**Copyright (c) 2026 Takeshi Arai. All Rights Reserved.**

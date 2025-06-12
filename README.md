# ip-law-data

**日本の知的財産関連法令（XML形式）と、e-Gov法令XMLスキーマの保存用リポジトリ**

このリポジトリは、ChatGPTをはじめとするAIと連携するために構造化された、  
**日本の特許法・意匠法・商標法・実用新案法の法令XML**を収集・整理したものです。

---

## 📁 フォルダ構成

laws_xml/          ← 法令XML本体（法域別フォルダ）
├── design/
├── patent/
├── trademark/
└── utility_model/

schemas/           ← e-Gov XML用スキーマ
└── XMLSchemaForJapaneseLaw_v3.xsd

---

## 📌 使用例（ChatGPTなどで使うとき）

- `laws_xml/patent/patent_law_R060401.xml` を読み込んで、構造化解釈する
- `schemas/XMLSchemaForJapaneseLaw_v3.xsd` に準拠してパースする
- 条文や階層構造を自動抽出・表示できる

---

## 🌱 運用・更新方針

- 各法域の最新版XMLのみを管理（施行日付きファイル名）
- 新しい施行日のXMLが公開されたら順次差し替え予定

---

## 🙋‍♀️ 制作・管理

**yui.ipromise（@yuiipromise）**  
"ip" に知財への想いを込めて、AIと法をつなぐ環境を育てています。

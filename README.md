# 📚 EduTrace（開発中アプリ名）

EduTrace is a cross-platform learning progress dashboard that aggregates and visualizes student activity across multiple online learning platforms such as Google Classroom, すらら, Duolingo, and iReady.

---

## ✨ アプリ名称候補（検討中）

以下はいずれも有力候補として検討中です。今後のユーザーテストなどで最終決定します。

- **EduTrace（エデュトレース）**  
  教育（Education）＋ 追跡（Trace）。先進性と直感性を両立。

- **ManabuHub（まなぶハブ）**  
  学びの集約拠点としての「ハブ」。親しみやすさを重視。

- **LearnDock（ラーンドック）**  
  各学習プラットフォームをドッキングする基地的存在。

---

## 🚀 Overview

現代の学生は複数のオンライン学習ツールを並行して使用しています。  
EduTrace はその進捗情報を一元管理し、保護者と生徒の両者にとって利便性の高い学習ダッシュボードを提供します。

- 学習状況を一覧化し、可視化
- 複数のプラットフォームにまたがる履歴を統合
- 弱点をAIが分析してフィードバック（今後追加予定）

---

## 🎯 Key Features

- 🔗 **プラットフォーム連携（モックデータでスタート）**  
  Google Classroom, すらら, Duolingo, iReady などに対応予定

- 📊 **学習進捗ダッシュボード**  
  日付、教科、単元、学習時間、スコアなどを一元表示

- 👨‍👩‍👧 **親子どちらにも嬉しい設計**  
  保護者は進捗チェックが簡単に、子どもはモチベーション維持に繋がる

- 🤖 **AIによる弱点分析とリコメンド（予定）**

---

## 🛠️ Tech Stack

- **Frontend**: React + Next.js + Tailwind CSS  
- **Backend**: Node.js / Express（将来予定）、Supabase または Firebase  
- **Auth**: Firebase Authentication（将来予定）  
- **Data**: MVP では JSONベースのモックAPIを使用

---

## 🧪 MVP Scope（初期開発範囲）

- ログイン（仮）
- プラットフォーム選択と学習記録一覧
- ダッシュボードでの可視化（モックデータ）
- 進捗データ：日付・科目・単元・学習時間・スコア・完了状況

---

## 📸 Screenshots（開発参考用 UI）

| SuRaLa | Google Classroom | iReady |
|--------|------------------|--------|
| ![sulala](screenshots/sulala.png) | ![gclassroom](screenshots/gclassroom.png) | ![iready](screenshots/iready.png) |

---

## 📦 How to Run (ローカル起動手順)

```bash
git clone https://github.com/your-username/edutrace.git
cd edutrace
npm install
npm run dev
```

アプリは以下のURLで起動します: `http://localhost:3000`

---

## 🧩 Future Roadmap

- [ ] 学習プラットフォームとのリアルタイム連携（API or スクレイピング）
- [ ] AIによる弱点分析・レコメンド
- [ ] 通知・リマインダー機能（保護者・生徒向け）
- [ ] モチベーション管理機能（ポイント、バッジなど）
- [ ] レポートエクスポート（保護者や教師用）

---

## 🛡️ License

MIT License

---

## 👤 Author

Created by shoheixkimura. Contributions welcome!


---
title: スマホからスマホアプリを作るためのフロー
created: 2025-06-29T00:00:00.000Z
updated: "2025-06-29"
tags:
  - "#技術"
  - "#ReactNative"
  - "#Expo"
  - "#開発環境"
---

# スマホからスマホアプリを作るためのフロー

作成日時: 2025年6月29日

##  **目標**

**移動中でもスマホだけでアプリ開発サイクルを完結させる**

**フロー:** Slack → AI → コード生成 → スマホで即確認 → 配布

---

## ️ **必要なもの**

- スマホ（iOS/Android）
- PC（初期セットアップのみ）
- Slack + Expo Go + GitHub

---

#  **実行タスク**

## **Phase 1: 基盤構築**

### **A. Expo環境** ✅ **完了**

- [x] **A1.** `npm install -g @expo/cli` (新しいCLIにアップグレード)
- [x] **A2.** Expoアカウント作成・ログイン (`kojitorishima`)
- [x] **A3.** テストプロジェクト作成 `npx create-expo-app test-app --template blank`
- [x] **A4.** スマホにExpo Goインストール
- [x] **A5.** QRコードでスマホ表示テスト

### **B. GitHub連携** ✅ **完了**

- [x] **B1.** リポジトリ作成・プッシュ (https://github.com/K-Torishima/sample_expo_app)
- [x] **B2.** GitHub Actions設定 (Expo CI/CDワークフロー)

## **Phase 2: Slack Bot開発**

### **C. Slack準備**

- [ ] **C1.** Slack Workspace作成
- [ ] **C2.** Bot作成・トークン取得
- [ ] **C3.** Bot用サーバー準備（Node.js）

### **D. AI連携**

- [ ] **D1.** AI API選定（Claude/Gemini/ChatGPT）
- [ ] **D2.** APIキー取得・設定
- [ ] **D3.** React Nativeコード生成プロンプト作成

### **E. Bot機能**

- [ ] **E1.** Slack → AI → Slack フロー実装
- [ ] **E2.** 生成コードのファイル書き込み
- [ ] **E3.** `expo start` 自動実行
- [ ] **E4.** QRコード生成・Slack投稿

## **Phase 3: 自動化**

### **F. デプロイ**

- [ ] **F1.** EAS CLI設定
- [ ] **F2.** 自動ビルド・アップデート設定
- [ ] **F3.** Slack通知設定

## **Phase 4: 運用テスト**

- [ ] **H1.** 「画面作って」→ 生成 → 確認テスト
- [ ] **H2.** エラーハンドリング
- [ ] **H3.** プロンプト最適化

---

## **⚡ 今すぐやること**

~~1. **A1:** `npm install -g @expo/cli` ✅ 完了~~
~~2. **A2:** https://expo.dev/ でアカウント作成 ✅ 完了~~

**次のステップ:**
~~1. **B1:** リポジトリ作成・プッシュ ✅ 完了~~
~~2. **B2:** GitHub Actions設定 ✅ 完了~~

**Phase 2開始:**
1. **C1:** Slack Workspace作成
2. **D1:** AI API選定（Claude/Gemini/ChatGPT）

---

## ** 成功指標**

- [ ] Slackから5分以内でスマホ確認
- [ ] 1日で簡単なアプリ完成
- [ ] 移動中でもスマホのみで開発完結 

 
# Expoログイン手順

## **概要**
Expo開発環境でのアカウント作成・ログイン手順を説明します。

## **前提条件**
- Node.jsがインストール済み
- 新しいExpo CLI (`@expo/cli`) がインストール済み

## **手順**

### **1. test-appディレクトリに移動してログイン**
```bash
cd test-app
npx expo login
```

### **2. ログイン情報を入力**
- Email or username: `torikou3685@gmail.com` または `kojitorishima`
- Password: （設定されたパスワード）

### **3. ログイン確認**
```bash
npx expo whoami
```
成功すると、ユーザー名が表示されます。

## **アカウント作成について**
- Expoアカウントは https://expo.dev/ で作成可能
- ログインコマンド実行時にアカウント作成も可能

## **トラブルシューティング**

### **古いexpo-cliの警告が出る場合**
```bash
# 古いCLIをアンインストール
npm uninstall -g expo-cli

# 新しいCLIをインストール
npm install -g @expo/cli
```

### **ログインできない場合**
- メールアドレスとユーザー名の両方を試す
- パスワードを再確認
- インターネット接続を確認

## **次のステップ**
ログイン完了後は、以下のコマンドでアプリを起動できます：
```bash
npx expo start
``` 
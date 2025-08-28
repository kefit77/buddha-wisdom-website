# GitHub Pages セットアップ手順書

## 📋 次に行うべき作業

### 1. GitHubアカウントでリポジトリ作成

1. https://github.com にログイン
2. 右上の「+」→「New repository」をクリック
3. 以下の設定で作成：
   ```
   Repository name: buddha-wisdom-website
   Description: Official website for Buddha Wisdom app
   Public にチェック
   Initialize with README: チェックしない
   ```
4. 「Create repository」をクリック

### 2. ローカルファイルをGitHubにプッシュ

表示された画面のコマンドをコピーして実行：

```bash
git remote add origin https://github.com/[あなたのGitHubユーザー名]/buddha-wisdom-website.git
git branch -M main
git push -u origin main
```

### 3. GitHub Pages を有効化

1. GitHubのリポジトリページで「Settings」タブをクリック
2. 左サイドバーの「Pages」をクリック
3. Source設定：
   - 「Deploy from a branch」を選択
   - Branch: 「main」を選択
   - Folder: 「/ (root)」を選択
4. 「Save」をクリック

### 4. 公開確認（5-10分後）

以下のURLでアクセス可能になります：
```
メインサイト: https://[ユーザー名].github.io/buddha-wisdom-website/
プライバシーポリシー: https://[ユーザー名].github.io/buddha-wisdom-website/privacy-policy.html
利用規約: https://[ユーザー名].github.io/buddha-wisdom-website/terms-of-service.html
```

## 📱 アプリストア申請時に入力するURL

### Google Play Console
```
プライバシーポリシーURL:
https://[ユーザー名].github.io/buddha-wisdom-website/privacy-policy.html
```

### Apple App Store Connect
```
プライバシーポリシーURL:
https://[ユーザー名].github.io/buddha-wisdom-website/privacy-policy.html

サポートURL（任意）:
https://[ユーザー名].github.io/buddha-wisdom-website/
```

## ✅ 確認事項

サイトが正しく公開されたら、以下を確認してください：

- [ ] メインページが美しく表示される
- [ ] プライバシーポリシーが完全に表示される  
- [ ] 利用規約が完全に表示される
- [ ] スマートフォンでも正常に表示される
- [ ] すべてのリンクが正しく動作する

## 🔧 トラブルシューティング

### よくある問題と解決方法

**Q: "404 - File not found" が表示される**
A: GitHub Pagesの反映に最大10分かかります。しばらく待ってから再度アクセスしてください。

**Q: スタイルが適用されない**
A: ブラウザのキャッシュをクリア（Ctrl+F5）してください。

**Q: モバイルで表示が崩れる**
A: レスポンシブデザインが適用されているため、デバイスを縦向きにしてください。

## 📞 サポート

問題が解決しない場合は、以下を確認：
1. GitHubリポジトリが Public に設定されているか
2. ファイル名が正確か（大文字小文字含む）
3. GitHub Pages の Status が緑色（Active）になっているか

---

**重要**: このURLはアプリストア申請で必須です。必ず正常に表示されることを確認してから申請を進めてください。
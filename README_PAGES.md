# GitHub Pages で公開する手順

## 公開手順（ブラウザだけでOK）
1. GitHubで新規リポジトリ作成（例: `seikotsuin-site`）
2. `Add file` → `Upload files` からこのフォルダ内のファイルをすべてアップロードして `Commit`。
3. `Settings` → `Pages` → Build and deployment:
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
4. 数十秒後、表示されたURL（https://ユーザー名.github.io/seikotsuin-site/）で確認。

## 差し替える箇所
- 〇〇整骨院（院名）、住所、電話、メール、受付時間、地図iframe
- robots.txt / sitemap.xml の URL

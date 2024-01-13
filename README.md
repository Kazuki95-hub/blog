# blog

## 必要機能
- ヘッダー　
- 目次　
- 時系列記事一覧　
- プロフィールカード　
- SNSアカウントとリンク　
- 記事検索　
- タグフッター　
- 関連記事

## 技術構成
- フロントエンド
    - マークダウンで記事を書きたいため、SSGできるフレームワーク
    - 候補
       - next.js 
- UIライブラリ
MUI、Ant Design、Radix UI MANTINE
- 言語
ts
- ホスティング
    -   Vercel Next.jsとの親和性が高い　オールインワンプラットフォーム　シンプル
    -   Netlify GitHubのレポジトリとNetlifyを接続して、レポジトリに変更が加わると自動でデプロイし直してくれる fireabaseより簡単
    -  Firebase Hosting 
    -  Github pages Github Pageは簡単な静的サイトをGithubリポジトリからホステイングされるので、リポジトリと連動することができる。
    -  Azure Static Web Apps
    -  Gatsby Cloud　ReactReact
    -  Surge
    -  Render
    -  IONOS
    -  AWS Amplify

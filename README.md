# EC App

## デモ

http://ec2-54-249-81-74.ap-northeast-1.compute.amazonaws.com:8080

## リポジトリ

https://github.com/tkmoya/ec-app.git

## 概要

会員登録したユーザーが商品を購入することができる EC サイトです。

好きな商品を一覧から選択して、購入したい個数を入力して購入画面で金額を確認して購入することができます。

ゲストユーザーでも商品の閲覧・検索は可能です。

## 主な機能

- 新規会員登録
- ログイン機能
- 会員情報修正・削除
- 商品検索
- ページネーション
- カート機能
- バリデーションチェック

## 使用技術

- **Java**
- **Tomcat**
- **Spring Boot**
- **JDBC Template**
- **Thymeleaf**
- **MySQL**
- **JavaScript**
- **AWS**

# MD Todo

## デモ

https://nextjs-cloudflare-todo.pages.dev/

## リポジトリ

https://github.com/tkmoya/md-todo.git

## 概要

マークダウン形式で Todo を管理できるアプリケーションです。

## 主な機能

- Todo の作成、取得、更新、削除
- マークダウン形式で Todo の説明を記述可能
- Cloudflare Workers を使用した高速なバックエンド
- 優先度設定
- 期限設定

## 使用技術

- **Next.js**: フロントエンドフレームワーク
- **Hono**: 高速な Web フレームワーク（バックエンド）
- **Cloudflare**: サーバーレス環境
- **TypeScript**: 型安全なプログラミング
- **Markdown**: Todo の説明をマークダウン形式で記述可能
- **Fetch API**: データ通信

# TechCorp

## デモ

https://github.com/tkmoya/techcorp.git

## リポジトリ

https://github.com/tkmoya/ec-app.git

## 概要

IT 企業を模したコーポレートサイトです。  
トップページ、メンバー一覧、ニュース一覧、お問い合わせフォームを作成しました。

非エンジニアでも運用できるように microCMS で投稿可能にしています。  
また、お問い合わせフォームは HubSpot と連携しています。

## 主な機能

- microCMS を使用したメンバー編集、ニュース記事の投稿
- HubSpot 連携したお問い合わせフォーム

## 使用技術

- **Next.js**: フロントエンドフレームワーク
- **Vercel**: ホスティング環境
- **TypeScript**: 型安全なプログラミング
- **MicroCMS**: ヘッドレス CMS
- **HubSpot**: CRM

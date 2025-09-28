# portfolio

## アプリ概要
Next.js と Supabase を用いた「旅行支出管理・天気確認アプリ」です。
ユーザーは旅行予定を登録し、その地点の天気情報を確認できます。
登録した支出情報の内訳や使用状況をグラフで確認できます。

## サイトイメージ
メインページの画像です。
![アプリ画面](https://github.com/S-Nishi24/portfolio/blob/11647dfa2fcff3c9ff8ab54495a4df2e41530b36/docs/%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E3%83%A1%E3%82%A4%E3%83%B3%E3%83%9A%E3%83%BC%E3%82%B8%E7%94%BB%E5%83%8F.png?raw=true)


## サイトURL
https://travel-budget-weather-app.vercel.app

未ログインの場合、ログイン画面へ遷移します。
- テストアカウント
  - メールアドレス：test@example.com
  - パスワード：TestApp2025!  

## 使用技術
- フロントエンド：Next.js 14.2.25
- バックエンド：Next.js 14.2.25
- データベース：Supabase
- デプロイ：Vercel
- バージョン管理：Git、GitHub
- テスト・デバッグ：DevTools（Chrome）
- CI/CD：GitHub Actions（ESLint）


## 設計ドキュメント
[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1fbeRh_2ujOQCMXdwZ9QOzGdv37wXA8YMw5U5GZdgjXQ/edit?usp=sharing)

詳細設計時のワイヤーフレーム、ER図の画像はdocsディレクトリに格納しています。（[こちらからアクセス](./docs)）

## 機能一覧
- ユーザー登録、ログイン機能（メールアドレス認証）
- 旅行新規作成・編集・削除
- 旅行ごとの支出登録・編集・削除
- 天気情報の自動取得（OpenWeatherMap API；5日先までの予報）
- 支出の内訳や予算に対する使用率をグラフで確認
  
## テスト・修正の設計及び実施書
[テスト・修正の設計及び実施書_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1tBSOBwkvNtA8l_AV1aVfVJdk9Wie7I7O2mbg1s6xcd4/edit?usp=sharing)

## アプリの改善案
[アプリの改善案_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/14NGym7WFSIpolSZW8icB0dS_Vlo-XBxVxEHNh4WMf2Q/edit?usp=sharing)

## 備考
[ESLintの実行結果_GitHub Actions](https://github.com/S-Nishi24/TravelApp/actions/runs/18041039992)

- 活用した生成AIとその用途
  - ChatGPT：要件定義、設計、各種リサーチ
  - v0：アプリのモック作成
  - GitHub Copilot Chat：ローカル環境でのコードの修正相談

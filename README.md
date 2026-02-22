🎌 anime-platform-portfolio

Spring Boot 3｜Java 17｜Full Stack Web Project

======================================

📌 プロジェクト概要

MyAnimeListベースのアニメ情報検索・レビュー・お気に入り管理が可能な
フルスタックWebサービス

外部API（Jikan / Gemini AI）と連携し、
多言語（KO / JA / EN）対応・AI翻訳・チャットボット機能まで実装。

======================================

🛠 技術スタック
Backend

Java 17

Spring Boot 3

Spring Security

MyBatis

MySQL

Frontend

Thymeleaf

HTML / CSS

JavaScript

External API

Jikan API (MyAnimeList 非公式API)

Google Gemini API (翻訳 / チャットボット)

======================================

👥 ユーザー権限
USER

会員登録 / ログイン / ログアウト

アニメ検索

詳細ページ閲覧

お気に入り登録

レビュー作成 / 修正 / 削除

評点登録

マイページ管理

多言語切替（KO / JA / EN）

AIチャットボット利用

ADMIN

ユーザー管理（停止 / 削除）

レビュー管理（通報処理）

管理者ダッシュボード

======================================

🏗 アーキテクチャ

MVCパターンベース

Controller
  ↓
Service
  ↓
Mapper (MyBatis)
  ↓
Database (MySQL)


CustomUserDetails 実装

Roleベース認可処理

i18n (messages_ko / ja / en)

REST API 非同期通信 (fetch)

======================================


💡 主な実装ポイント

Spring Security カスタム認証処理

レビュー通報システム

多言語動的切替

Gemini API を利用したAI翻訳

キャッシュ制御

管理者専用ページ

======================================

▶ 実行方法

MySQL データベース作成

SQL 実行（テーブル生成）

application.yml にDB情報設定

Gemini API Key 設定

Spring Boot 実行

======================================

👉 [プロジェクト説明ページへ](https://eugene6oz.github.io/anime-platform)


📷 スクリーンショット

※ /docs フォルダに追加予定

======================================

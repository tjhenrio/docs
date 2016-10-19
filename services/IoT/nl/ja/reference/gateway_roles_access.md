---

copyright:
  years: 2016

---

{:new_window: target="blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# ゲートウェイ役割のアクセス・レベル
最終更新日: 2016 年 9 月 16 日
{: .last-updated}

ゲートウェイ役割のそれぞれのアクセス・レベルを、以下の表に示します。

表には、以下のものについてのアクセス・レベルが示されています。
- [デバイス操作](#gateway-device-ops)
- [ログ操作](#gateway-log-ops)
- [キャッシュ操作](#gateway-cache-ops)
<!-- [Historian Operations](#gateway-historian) -->
- [組織操作](#gateway-org-ops)
- [アクセス制御操作](#gateway-access-ops)
- [分析操作](#gateway-analytics-ops)
- [サード・パーティー操作](#gateway-third-party)  
<!-- - [Risk Management Operations](#gateway-risk-mgt) -->

## ゲートウェイ役割
{: #gateway-roles}

### デバイス操作{: #gateway-device-ops}

デバイス操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------
           | **標準ゲートウェイ** | **特権ゲートウェイ**
デバイスの作成、更新、または削除|-|X
デバイスの表示|X|X
デバイスのアクティブ化|-|X
イベントのパブリッシュ|X|X
イベントのサブスクライブ|-|-
コマンドのパブリッシュ|-|-
コマンドのサブスクライブ|X|X
デバイス管理アクションの開始|X|X
デバイス管理アクションの表示|X|X
デバイス管理アクションのクリア|-|-
デバイス管理アクション・バンドルの管理|-|X
デバイス・タイプの作成、更新、削除|-|-
デバイス・タイプの表示|X|X
診断ログの管理|-|-
診断ログの表示|-|-

### ログ操作{: #gateway-log-ops}

ログ操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------
           | **標準ゲートウェイ** | **特権ゲートウェイ**
サーバー・ログの表示|-|-

### キャッシュ操作{: #gateway-cache-ops}

キャッシュ操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------
           | **標準ゲートウェイ** | **特権ゲートウェイ**
稼働中データ (イベント・キャッシュ) の表示|-|-
稼働中データ (イベント・キャッシュ) の管理|-|-


### 組織操作{: #gateway-org-ops}

組織操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------
           | **標準ゲートウェイ** | **特権ゲートウェイ**
ストレージ・パラメーターの構成|-|-
認証プロバイダーの構成|-|-
メール構成の作成、表示、更新、または削除|-|-
使用可能メール・プロバイダーの表示|-|-
メール・テンプレートの作成、表示、更新、または削除|-|-
ユーザーの作成、更新、または削除|-|-
ユーザーの表示|-|-
ユーザー送信勧誘の作成、更新、削除|-|-
ユーザー送信勧誘の表示|-|-
送信勧誘の完了|-|-
API キーの作成、更新、または削除|-|-
API キーの表示|-|-
組織使用情報の表示|-|-

### アクセス制御操作{: #gateway-access-ops}

アクセス制御操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------
           | **標準ゲートウェイ** | **特権ゲートウェイ**
ユーザー・プロパティーの表示 (アクセス権を含む)|-|-
ユーザー独自のプロパティーの表示 (アクセス権を含む)|-|-
ユーザーの管理 (アクセス権を含む)|-|-
API キー・プロパティーの表示 (アクセス権を含む)|-|-
API キー独自のプロパティーの表示 (アクセス権を含む)|-|-
API キーの作成、更新、または削除 (アクセス権を含む)|-|-
デバイス・プロパティーの表示 (アクセス権を含む)|X|-
デバイス独自のプロパティーの表示 (アクセス権を含む)|X|-
デバイスの作成、更新、削除 (アクセス権を含む)|-|X
役割の表示|-|-
カスタム役割の作成、更新、削除|-|-
操作の表示|-|-

### 分析操作{: #gateway-analytics-ops}

分析操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------|
           | **標準ゲートウェイ** | **特権ゲートウェイ** |
分析ルールの表示|-|-
分析ルールの管理|-|-
分析アクションの表示|-|-
分析アクションの管理|-|-
分析アラートの表示|-|-
分析メッセージ・スキーマの表示|-|-
分析メッセージ・スキーマの管理|-|-

### サード・パーティー・サービス操作{: #gateway-third-party}

サード・パーティー・サービス操作 || ゲートウェイ役割|
:--------: | ---------------------|------------------------
           | **標準ゲートウェイ** | **特権ゲートウェイ**
外部プラットフォームからのバッチ通知の処理|-|-
バッチ通知の処理と外部プラットフォームへの送信|-|-
デバイスのイベントのパブリッシュ|-|-
デバイスからイベントへのサブスクライブ|-|-
外部プラットフォームのコールバック URL の設定|-|-
外部プラットフォームのサブスクリプション・レベルの設定|-|-
コネクターからの状況ヘルス状況の取得|-|-
外部システムが稼働しているかどうかの確認と資格情報の検証|-|-
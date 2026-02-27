---
layout: default
title: Support
permalink: /support
---

# サポート

PDAIをご利用いただきありがとうございます。こちらのページでは、よくある質問への回答とサポート情報をご案内します。

---

## よくある質問（FAQ）

### AIチャット

<details>
<summary>AI応答が遅い場合はどうすればよいですか？</summary>
<p>PDAIは2種類のAIに対応しています。「設定」>「LLMプロバイダー」から切り替えできます。</p>
<ul>
<li><strong>Apple Foundation Models</strong>（推奨）: オンデバイスで処理するため高速かつプライベート。追加費用なし。</li>
<li><strong>Google Gemini API</strong>: クラウド処理のため、ネットワーク接続状況により応答速度が変わります。Wi-Fi環境を推奨。APIキーの設定が必要です。</li>
</ul>
</details>

<details>
<summary>AIが意図を正しく理解しない場合は？</summary>
<p>PDAIは14種類の意図（カレンダー・天気・ヘルスケア・地図・連絡先・翻訳・音楽・写真・旅行など）を認識します。より明確な表現で再度入力すると精度が向上します。例: 「天気」→「今日の横浜の天気を教えて」</p>
</details>

### ヘルスケア・ゲーミフィケーション

<details>
<summary>HealthKitのデータが表示されません</summary>
<p>「設定」>「プライバシーとセキュリティ」>「ヘルスケア」>「PDAI」から、必要なヘルスケアデータ（歩数、心拍数、心拍変動、睡眠）へのアクセスを許可してください。許可後、アプリを再起動するとデータが反映されます。</p>
</details>

<details>
<summary>HP・XP・レベルとは何ですか？</summary>
<p>PDAIはヘルスケアデータをRPGゲーム風のステータスに変換します。</p>
<ul>
<li><strong>HP（体力）</strong>: 睡眠・歩数・心拍変動・基礎代謝から計算。時間経過や活動で変動します。</li>
<li><strong>XP（経験値）</strong>: 会話完了（+10）、旅行プラン作成（+30）、ゴール達成（+50）など、アプリの利用で獲得。</li>
<li><strong>Level</strong>: XPの累積で自動的にレベルアップ。レベルが上がるとMaxHPが増加します。</li>
</ul>
</details>

### 旅行プランナー

<details>
<summary>旅行プランの危険度判定はどこのデータを使っていますか？</summary>
<p>外務省が公開している海外安全情報データベースを使用しています。危険度はLevel 0（安全）からLevel 4（退避勧告）まで5段階で表示されます。「設定」から危険度しきい値を変更できます。</p>
</details>

<details>
<summary>旅行プランをAIで修正できますか？</summary>
<p>はい。作成済みのプランは「AIチャット編集」機能で自然な会話を通じて修正できます。目的地の追加・除外、日程の変更、ルートの最適化などが可能です。</p>
</details>

### 翻訳・会話練習

<details>
<summary>対応言語は何ですか？</summary>
<p>翻訳と会話練習は以下の7言語に対応しています: 英語、日本語、中国語、韓国語、フランス語、ドイツ語、スペイン語。翻訳にはApple Translation frameworkを使用し、会話練習ではAIがネイティブスピーカー役を担当します。</p>
</details>

<details>
<summary>音声読み上げ機能はありますか？</summary>
<p>はい。翻訳結果やAIの会話メッセージには読み上げボタンが表示されます。Apple TTS（AVSpeechSynthesizer）を使用して各言語のネイティブ発音で読み上げます。</p>
</details>

### バッテリー・省エネルギー

<details>
<summary>バッテリー消費が気になります</summary>
<p>PDAIは省エネルギー設計を採用しています。iPhoneの「低電力モード」をONにすると、以下の最適化が自動的に適用されます。</p>
<ul>
<li>AI推論の最適化（ProactiveEnhancerスキップ・リトライ抑制）</li>
<li>GPS精度の動的低下（SignificantLocationChangesに切替え）</li>
<li>アニメーション・3D表示の抑制</li>
<li>キャッシュ有効期間の延長</li>
</ul>
<p>バッテリー残量20%以下でも自動的に省電力モードが作動します。</p>
</details>

### サブスクリプション

<details>
<summary>サブスクリプションの管理方法は？</summary>
<p>サブスクリプションの確認・変更・解約は、iPhoneの「設定」>「Apple ID」>「サブスクリプション」から行えます。解約後も期間終了まではプレミアム機能をご利用いただけます。</p>
</details>

<details>
<summary>TestFlight版は無料ですか？</summary>
<p>はい。TestFlight版では全機能が無料で利用可能です。正式リリース後はサブスクリプション（月額¥450 / 年額¥4,500）が必要になります。</p>
</details>

### データ管理

<details>
<summary>データのバックアップはできますか？</summary>
<p>PDAIのデータはiCloud（CloudKit）経由でバックアップ・同期されます。iPhoneの「設定」>「Apple ID」>「iCloud」が有効になっていることをご確認ください。</p>
</details>

---

## お問い合わせ

問題が解決しない場合は、お気軽にご連絡ください。

**メール**: [pdai.app.contact@gmail.com](mailto:pdai.app.contact@gmail.com)

通常、1-2営業日以内にご返信いたします。

お問い合わせの際は、以下の情報を添えていただくとスムーズに対応できます：

- お使いのiPhoneモデル
- iOSバージョン
- PDAIのバージョン（アプリ内「設定」から確認可能）
- 問題の詳細な説明

---

## アプリ情報

| 項目 | 内容 |
|------|------|
| アプリ名 | PDAI - Personal Digital AI Assistant |
| バージョン | 2.5.0 (Build 62) |
| 対応OS | iOS 25.0以降 |
| 開発者 | hide67 |
| カテゴリ | 仕事効率化 |

<p class="last-updated">PDAI Version 2.5.0</p>

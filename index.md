---
layout: default
title: Home
---

<div class="hero">
  <h1>PDAI</h1>
  <p class="tagline">あなたのiPhoneが、もっと賢くなる。</p>
  <p>PDA (Personal Digital Assistant) + AI = <strong>PDAI</strong></p>
  <p>かつての「電子手帳」を、自律型AIエージェントで再発明したパーソナルアシスタント。</p>
</div>

## 主要機能

<div class="feature-grid">

<div class="feature-card">
  <div class="icon">🧠</div>
  <h3>OODA Loop AIエージェント</h3>
  <p>軍事戦略のOODA Loopを応用した自律型意思決定エンジン。観察→方向づけ→決定→行動→振り返りの真のループで、タスクを自動分解・並列実行・動的修正。14種類の意図を認識し、15パターンの直接実行に対応。</p>
</div>

<div class="feature-card">
  <div class="icon">🎮</div>
  <h3>RPGヘルスケア</h3>
  <p>HealthKitデータをHP / XP / Level / Stressに変換。歩数・睡眠・心拍変動・基礎代謝をゲーミフィケーションで可視化。会話・旅行・目標達成でXPを獲得し、レベルアップ。</p>
</div>

<div class="feature-card">
  <div class="icon">🌍</div>
  <h3>安全旅行プランナー</h3>
  <p>外務省の海外安全情報を統合。危険地域を自動回避し、AIが最適な日程・ルート・移動手段を提案。ウィザード形式のプラン作成、地図上でのルート確認、AIチャットによるプラン編集に対応。</p>
</div>

<div class="feature-card">
  <div class="icon">📝</div>
  <h3>議事録・音声メモ</h3>
  <p>音声から議事録を自動生成。リアルタイム波形表示で録音状況を確認。4C分析（提案会議）や4S分析（報告会議）でビジネス文書を構造化。</p>
</div>

<div class="feature-card">
  <div class="icon">📅</div>
  <h3>会話カレンダー管理</h3>
  <p>「明日10時に会議」と話すだけで予定を追加。EventKit統合で競合検出・リッチカード表示。日・週・月の俯瞰ビューと詳細画面でスケジュールを一元管理。</p>
</div>

<div class="feature-card">
  <div class="icon">🌐</div>
  <h3>翻訳・語学学習</h3>
  <p>Apple Translation frameworkによるテキスト翻訳と、AIパートナーとの会話練習。英語・日本語・中国語・韓国語・フランス語・ドイツ語・スペイン語の7言語対応。音声入力・読み上げ機能付き。</p>
</div>

<div class="feature-card">
  <div class="icon">🗺️</div>
  <h3>天気・地図・連絡先統合</h3>
  <p>ひとつの会話で天気予報（WeatherKit）、周辺検索・ナビゲーション（MapKit）、連絡先検索をシームレスに横断処理。3Dフライオーバーマップにも対応。</p>
</div>

<div class="feature-card">
  <div class="icon">🎯</div>
  <h3>目標管理</h3>
  <p>Health / Fitness / Work / Learning / Finance / Personalの6カテゴリで目標の進捗を追跡。マイルストーン達成でXPボーナスを獲得。</p>
</div>

<div class="feature-card">
  <div class="icon">🎵</div>
  <h3>音楽・写真連携</h3>
  <p>Apple MusicKit連携による楽曲検索・再生、フォトライブラリの写真検索・表示。AIチャットから自然な会話で操作可能。</p>
</div>

<div class="feature-card">
  <div class="icon">📊</div>
  <h3>行動学習</h3>
  <p>時間帯・曜日別の行動パターンを自動学習し、次のアクションを予測・先読み提案。天気・カレンダー・ヘルスケア・連絡先・写真・メールの6データソースを統合。</p>
</div>

<div class="feature-card">
  <div class="icon">🔋</div>
  <h3>省エネルギー設計</h3>
  <p>低電力モード時にAI推論の最適化（ProactiveEnhancerスキップ・リトライ抑制）、GPS精度の動的制御、アニメーション抑制、キャッシュTTL延長を自動実行。バッテリー消費を大幅削減。</p>
</div>

<div class="feature-card">
  <div class="icon">✨</div>
  <h3>Premium機能</h3>
  <p>StoreKit 2による月額/年額サブスクリプション。高度なAI機能と全プレミアム機能をアンロック。TestFlight期間中は全機能無料。</p>
</div>

</div>

## PDAIの独自性

| ポイント | 内容 |
|---------|------|
| OODA Loopエージェント | 軍事戦略を応用した自律型AI意思決定。真のループ（最大2回）で動的修正 |
| RPGヘルスケア | 健康データをHP/XP/Levelに変換するゲーミフィケーション |
| 適応型プランナー | エラーから学習し実行プランを動的修正。CircuitBreakerで障害保護 |
| 危険地域回避 | 外務省データ統合の旅行安全フィルタ |
| 構造化議事録 | 4C/4S分析によるビジネス文書自動生成 |
| 省エネルギーAI | 低電力モードでAgent層の推論を自動最適化 |
| VibeCoding | 人間とAI（Claude）が協働で100%構築 |

## 技術スタック

| 項目 | 詳細 |
|------|------|
| 言語/SDK | Swift 6 / iOS 26 (Deployment Target: iOS 25.0+) |
| UI | SwiftUI + Observation framework |
| データ | SwiftData / iCloud (CloudKit) |
| AI | Apple Foundation Models (オンデバイス) / Google Gemini API |
| ヘルスケア | HealthKit (歩数・心拍・睡眠・HRV・BMR) |
| 地図 | MapKit (3D Flyover) / CoreLocation |
| 天気 | WeatherKit |
| 音声 | Speech Framework / AVFoundation (TTS) |
| 翻訳 | Apple Translation framework |
| 音楽 | MusicKit |
| 課金 | StoreKit 2 |

<p class="last-updated">Version 2.5.0</p>

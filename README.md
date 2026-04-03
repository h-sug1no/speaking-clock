# Speaking Clock
https://h-sug1no.github.io/speaking-clock/

Web時計アプリ。デフォルトで毎時特定の分[0, 7, 15, 22, 30, 37, 45, 52]・秒[0, 30]に英語→日本語で時刻を自動アナウンス。

- 朝、起きるまでの数十分位の間、うとうとしながら音楽を効く生活のために
- いつ起きるか決めるために、時刻を読み上げてもらう
  - これの原型を自作
    - agentに実装してもらう実験のためにこのレポジトリを作成
- アナウンス間隔は実運用で個人的に合っている値
- ２つのアナウンスなのは、一回だと聞き逃す、三回以上だとくどい気がしたから

## 機能

- 言語選択可能なバイリンガル・アナウンス（デフォルト: 英語→日本語）
- リアルタイムカスタマイズ：テンプレート、テーマ（Midnight/Cyber Matrix/Pure White）、音声設定
- 画面オン維持機能（Wake Lock）
- クイックテスト機能

## 使い方

1. `index.html` をブラウザで開く
2. 「Start Clock」をクリック
3. 設定パネルでカスタマイズ

## 読み上げテンプレート変数

- `{h}`: 時
- `{m}`: 分
- `{s}`: 秒
- `{lts}`: ロケールに応じた時刻テキスト

## ライセンス

MIT License

---

*This project was enhanced by Gemini, an AI assistant from Google.*
*This project was enhanced by GitHub Copilot *
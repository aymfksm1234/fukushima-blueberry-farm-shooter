# 福島ブルーベリー農園 — 収穫防衛（ブラウザゲーム）

**福島のブルーベリー農園をモチーフにした、横スクロール風のシンプルなシューティングゲームです。**  
上から落ちてくる果実（🫐・🍐・🌰）や金色レア、ボスなどを撃ち落とし、地面に落とさないようにスコアを稼ぎます。PC のキーボードと、スマホのタッチの両方に対応しています。

### いま遊べる URL（GitHub Pages）

**https://aymfksm1234.github.io/fukushima-blueberry-farm-shooter/**  

反映直後は 1〜2 分ほど待つと表示されます。スマホのブラウザからもそのまま開けます。

## このリポジトリでできること

| 内容 | 説明 |
|------|------|
| **プレイ** | `index.html` をブラウザで開くだけで動作（サーバー不要） |
| **スマホ** | [GitHub Pages](#github-pages-で公開する) で HTTPS 公開すると、スマホのブラウザから快適に遊べます |
| **共有** | ゲームオーバー後に Telegram / X（旧 Twitter）へスコアを共有できます |

## 遊び方（概要）

- **移動**: 矢印または A/D（スマホは画面を押したまま左右にスライド）
- **射撃**: スペース（スマホは自動連射）
- **コンボ・ハイパー収穫（🧺）・蜂ボス（🐝）・ボスウェーブ** など、スコアが伸びる要素あり
- **地面に果実が落ちるとゲームオーバー**

## ローカルで試す

リポジトリを clone したあと、次のどちらかで開いてください。

- `index.html` をブラウザにドラッグ＆ドロップ
- VS Code の「Live Server」などで `index.html` を開く

## GitHub Pages（別環境で自分用に公開するとき）

1. リポジトリを GitHub に push する。
2. **Settings → Pages** で **Branch** を `main`、フォルダ **`/ (root)`** を選んで Save。

> スマホで遊ぶときは **https の Pages URL** を使ってください。`file://` だと共有ボタンが期待どおり動かないことがあります。

## 技術スタック

- 単一 HTML（Canvas 2D + 素の JavaScript）。ビルドや npm は不要です。

## ライセンス

特に指定がなければ、利用・改変はご自由にどうぞ。農園・団体名の表記は実在の施設とは限りません。

---

### GitHub の「About」に貼る用の短い説明（Description）

コピーして、リポジトリの **About** の **Description** に貼れます。

```
福島ブルーベリー農園テーマのブラウザ向けシューティング。果実を撃ってスコア稼ぎ。スマホ対応・GitHub Pages で公開可。
```

English（任意）:

```
Browser mini-shooter themed on a Fukushima blueberry farm. Touch-friendly; deploy on GitHub Pages.
```

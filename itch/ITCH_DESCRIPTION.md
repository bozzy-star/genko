# itch.io ページ用の説明文(コピペ用)

## タイトル
元寇 — Genko

## 短い説明(Short description)
文永・弘安の役(元寇)をテーマにした、ファミコン『いっき』風の見下ろし縦スクロールアクション。弓と薙刀で蒙古・高麗・宋の兵を退け、米俵を集めて本陣の旗をめざせ。

## 本文(Description)

鎌倉武士の御家人となり、二度の蒙古襲来を戦い抜くレトロ風アクションです。HTML一枚、依存ライブラリなし。音も声もすべてコードで合成しています。

**遊び方**
- 面のなかの米俵をすべて集めると、いちばん奥の本陣に旗が立つ。旗に触れれば面クリア
- 倒した敵は「首級」として数える。得点が貯まると御家人が増える
- ライフ(♥)は難易度で 5〜1。尽きると御家人を一人失う

**操作(PC)**
- 移動: 矢印キー / WASD
- 攻撃: Z / Space(弓は矢を放つ、薙刀は撫で斬り)
- 持ち替え: X / Shift(第四面で薙刀を得てから)
- P 一時停止(操作説明) / M 音量 / F 全画面
- タイトルで 1〜6 キー: その面から始める

**操作(スマホ)**
- 右上の「全画面」を押してから横向きに
- 画面の左半分をなぞって移動、右下の「射」で攻撃
- 「替」または「射」を押したまま上へなぞると持ち替え

**面構成**
1. 博多湾 — まず矢に慣れる
2. 石築地 — 大将マルコ・ポーロ(必殺「東方見聞録」)
3. 博多の町 — ボーナス面。四十秒で米俵を拾えるだけ拾う
4. 博多防衛戦 — 画面固定。上から来る敵を九十秒しのぐ。町民を斬るな。ここで薙刀を得る
5. 志賀島 夜討ち — 闇の中、見つからずに敵を射る。見つかると「ここじゃー」
6. 鷹島沖 — 海上戦。小舟と漕ぎ手、風。大将フビライ・ハーン(必殺「集団戦法」)

**敵**
歩兵・弓兵・てつはう兵・騎馬兵のほか、盾を構える高麗兵、白旗をあげて降参する宋兵(旧南宋の新附軍)。

**難易度** baby / easy / normal / hard / expert。画面は PC(32×30マス)とスマホ(16×15マス)を自動で切替。

参考: 『蒙古襲来絵詞』『元史』日本伝、『高麗史』。マルコ・ポーロとフビライ・ハーンは史実では元寇に来ていませんが、ゲームの大将として登場します。

ソースコード: https://github.com/bozzy-star/genko

## English (短め)
A retro top-down action game in the style of the Famicom classic "Ikki", set during the Mongol invasions of Japan (1274/1281). Collect rice bales, fend off Mongol, Goryeo and Song soldiers with bow and naginata, and reach the banner. Six stages, five difficulty levels, keyboard and touch controls. Single HTML file, no dependencies.

## itch.io のアップロード設定(おすすめ)
- Kind of project: **HTML**
- アップロード: `genko-itch.zip`(index.html だけが入ったzip)
- 「This file will be played in the browser」にチェック
- Embed options:
  - Viewport dimensions: **1040 × 1060**(PC表示用。画面1024×960+ボタン列)
  - **Fullscreen button** にチェック
  - **Mobile friendly** にチェック(スマホで全画面で開けるようになる)
  - Orientation: **Landscape**
- Frame options: 「Automatically start on page load」はオフでよい(タップで開始するため)

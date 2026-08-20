# ぷにぷにエアホッケー

スマホ1台を2人で共有して遊べる、GitHub Pages向けの静的エアホッケーゲームです。PCでは1台のキーボードを2人で共有して対戦できます。

## Features
- Pointer Eventsによる2人同時マルチタッチ
- pointerIdごとの厳密な入力追跡
- 左右それぞれ自陣のみ操作可能
- PCキーボード対戦（BLUE: WASD / PINK: 矢印キー）
- 高速ドラッグを反映したショット
- サブステップ衝突処理で高速時のすり抜けを軽減
- 5点先取
- ゴール時のシェイク・パーティクル・ヒットストップ風演出
- Canvas描画のぷにキャラ・パック・盤面
- Web AudioによるSE/BGMフォールバック
- AudioContextのresume対策
- BGM/SE設定をlocalStorage保存
- iPhoneのsafe area / 100dvh / 画面回転対応
- visualViewport / resize / orientationchange対応
- タブ非表示・ウィンドウフォーカス喪失時の自動一時停止
- contextmenu / drag / scroll / zoom抑制

## Target browsers
モダンブラウザの標準Web APIのみを使う方針です。

- iPhone / iPad: Safari, Chrome, Edge, Firefox
- Android: Chrome, Firefox, Edge, Samsung Internet
- Windows: Chrome, Edge, Firefox
- macOS: Safari, Chrome, Firefox

タッチ端末では画面を直接操作し、PCではキーボード操作を利用できます。

## GitHub Pages
リポジトリ直下に `index.html` を置き、GitHub PagesのSourceを `Deploy from a branch` → `main` / `(root)` に設定すれば公開できます。

# ぷにぷにエアホッケー

スマホ1台を横向きにして2人で遊ぶ、GitHub Pages向けの静的エアホッケーゲームです。

## Features
- Pointer Eventsによる2人同時マルチタッチ
- 左右それぞれ自陣のみ操作可能
- 高速ドラッグを反映したショット
- サブステップ衝突処理で高速時のすり抜けを軽減
- 5点先取
- ゴール時のシェイク・パーティクル・ヒットストップ風演出
- Canvas描画のぷにキャラ・パック・盤面
- Web AudioによるSE/BGMフォールバック
- BGM/SE設定をlocalStorage保存
- iPhone向け touch-action / safe area / 100%画面対応

## GitHub Pages
リポジトリ直下に `index.html` を置き、GitHub PagesのSourceを `Deploy from a branch` → `main` / `(root)` に設定すれば公開できます。

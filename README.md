# 麻雀AI「RURI(Ravishing  Ultimate Reach Intelligence)」の開発

## 概要
自分自身が学生時代に夢見ていた麻雀AIの作成に社会人になったいま取り組んだプロジェクト

## リポジトリ構造
- src
    - meld.py (ゲーム中のlogを麻雀ルールに則ってデータ化するライブラリ。出力の日本語翻訳のみ実施)
- sketchbook
    - sketchbook_mjlog.ipynb
        - 麻雀のゲームログ(いわゆる牌譜)をデータセットとして扱えるように加工したノートブックです
    - sketchbook_discard_model.ipynb
        - AIのコアとなる麻雀の捨て牌モデル(何を切る)の構築を行っているノート。試行錯誤中。


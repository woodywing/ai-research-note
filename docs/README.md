# Research Notes

このディレクトリは、機械学習に関する論文・技術ドキュメント・調査メモを継続的に追加するための入口です。
単発のメモで終わらせず、今後資料が増えても追跡しやすいように、以下の単位で整理します。

## Directory structure

- `topics/`: 複数の論文・資料を横断して整理するトピック別ノート。
- `papers/`: 論文、PDF、技術記事、内部資料など、個別ソースごとの読書メモ。
- `templates/`: 新しい資料を追加するときに使うテンプレート。

## Current notes

- [Recent machine-learning methods and gradient boosting](topics/gradient-boosting/recent-ml-and-gradient-boosting.md)

## How to add a new source

1. `docs/templates/paper-note.md` をコピーし、`docs/papers/YYYY-author-short-title.md` の形式で保存する。
2. メタデータ、要約、手法、評価、限界、関連トピックを記入する。
3. 関連する `docs/topics/` 配下のトピックノートにリンクを追加する。
4. 新しいトピックが必要な場合は `docs/topics/<topic-name>/` を作成し、この README の `Current notes` へ追加する。

## Naming conventions

- ファイル名とディレクトリ名は、原則として lowercase kebab-case にする。
- 個別資料のメモは `papers/` に置く。
- 複数資料を横断する整理は `topics/` に置く。
- URL、DOI、ローカルファイル名など、後からソースを確認できる情報を可能な限り残す。

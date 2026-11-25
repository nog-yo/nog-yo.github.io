# nog-yo.github.io

https://nog-yo.github.io/ の原稿（GitHub Pages の Jekyll で組み立てる）。開発者の自己紹介と、作ったアプリの一覧を載せる。

- アプリを足す: `_data/apps.yml` に 1 つ足し、アイコン（192×192 の PNG）を `images/apps/<id>.png` に置く。
- このサイトのトップの名前（`_config.yml` の `title` と `alternate_names`。トップの WebSite の構造化データになる）とファビコン（`favicon.png`）は、Google の検索結果で、`nog-yo.github.io` の下のすべてのサイト（アプリごとの使い方のサイトも含む）のサイト名とアイコンに使われる。
- 外部のサイトから読み込むもの（スクリプト・Web フォント・解析）は置かない。

# 概要

[dbplyr 概論](https://shena4746.github.io/dbplyr-overview/) の ソース管理用レポジトリ. dbplyr の基本的な使い方とハンズオン.

## TOC

- dbplyr とは
  - 概要
  - Pros & Cons
  - 標準的な作業をフロー
- Hands-On
  - R から DB への接続
  - テーブルへの参照とクエリの実行
  - SQL 文の取得
  - 翻訳できない R 関数例
  - データのダウンロード
  - データのアップロード
    - ローカルデータ -> DB テーブル
    - ローカルデータ -> tbl_lazy
    - tbl_lazy -> DB テーブル
- References

## References

- Overview
  - [巨大なデータがSQLサーバーにあるときに、Rでどう立ち向かうかマニュアル：dbplyrパッケージを中心として](https://yutatoyama.github.io/note/intro_R_for_SQL.html)
  - [Introduction to dbplyr](https://dbplyr.tidyverse.org/articles/dbplyr.html)
  - [R: Working with Databases](https://nuitrcs.github.io/databases_workshop/r/r_databases.html)
  - [Introduction to DBI](https://dbi.r-dbi.org/articles/dbi)
- DBI
  - [RSQLite & DBIの使い方](http://delta0726.web.fc2.com/packages/database/00_RSQLite.html)
  - [DBI specification](https://dbi.r-dbi.org/articles/spec)
  - [DBI: R Database Interface .pdf](https://cran.r-project.org/web/packages/DBI/DBI.pdf)
  - [Code Examples for DBI and RPostgres](https://shena4746.github.io/code-examples-dbi-rpostgres/)
  - [User-defined functions that DBI + RPostgres users should have](https://shena4746.github.io/r-functions-on-dbi/)
- dbplyr 実践問題集
  - [dbplyrでデータサイエンス100本ノック](https://shena4746.github.io/datascience-100knocks-preprocess-R/)

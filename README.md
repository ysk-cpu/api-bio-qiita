# api-bio-qiita

bio-qiitaバック

単純なAPIまで作成済み。

API仕様

```
Method    URI                    機能
------------------------------------------
GET|HEAD  api/articles           一覧取得
POST      api/articles           投稿
GET|HEAD  api/articles/{article} 詳細取得
PUT|PATCH api/articles/{article} 更新
DELETE    api/articles/{article} 削除
```

とりあえず動いているかどうか確かめるには

Talend API TesterでGET http://localhost:80/api/articles

次のバックのタスクはシーディング実装。

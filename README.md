Web service APIs for Android
========================
Android向けのさまざまなWebサービスを呼び出すAPIを提供します。なるべく外部ライブラリを使わず、Android標準のSDKだけで済むようにしようと思ってます。
とりあえず楽天書籍検索APIを作ってみた。

使い方
--------
```
import nittyan.rakuten.book.book.Condition;
import nittyan.rakuten.book.book.BookSearcher;
import nittyan.rakuten.book.book.BookSearchResult;

BookSearcher searcher = new BookSearcher();
Condition condition = new Condition();
condition.applicationId = RAKUTEN_APP_ID;
condition.isbn = "111111111";
BookSearchResult result = searcher.search(condition);

```



Web service APIs for Android
========================
Android�����̂��܂��܂�Web�T�[�r�X���Ăяo��API��񋟂��܂��B�Ȃ�ׂ��O�����C�u�������g�킸�AAndroid�W����SDK�����ōςނ悤�ɂ��悤�Ǝv���Ă܂��B
�Ƃ肠�����y�V���Ќ���API������Ă݂��B

�g����
--------
```
import nittyan.rakuten.book.Condition;
import nittyan.rakuten.book.RakutenSearcher;
import nittyan.rakuten.book.BookSearchResult;

RakutenSearcher searcher = new RakutenSearcher();
Condition condition = new Condition();
condition.applicationId = RAKUTEN_APP_ID;
condition.isbn = "111111111";
BookSearchResult result = searcher.search(condition);

```



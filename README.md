# EasySummary
### 文章を要約するために開発したモジュール．
今のところ，形態素解析の機能と単語の頻出度を調べる機能がある.  
 
## How to use.
モジュールをPYTHONPATHに追加する．

```loding.py
import sys
sys.path.append("~/Github/python/EasySummary/src/module/")
from get_feature_value import Get_feature as mf
```

```morph_result.py
mf.morph_result("Qiitaにて機械学習についての記事を書いてます．")
>['Qiita', '機械学習', '記事']
```

```word_frequency.py
mf.word_frequency("Qiitaにて機械学習についての記事を書いてます．")
>{'Qiita': 1, '機械学習': 1, '記事': 1}
```

# atma8


--- 
12/04

01.ipynb，02.ipynbで，pandas plofiling，sweetvizをためした． \
Name,デベロッパーは使うのむずそう．

---
12/05
- 03.ipynbで，ベースライン作成．ロスをrmsleにしたら，0.94くらいになった．だが，oofは1.04くらいなので注意！！
- 04.ipynbで，nameをPCAにするやつをやった．Nameだけ，trainとtestの分布が近いことがわかった．
- 05.ipynbで，nameを含めて学習．oofは0.94くらいになったが，LBはさがらず．もっと考える余地あり．
- 06.ipynbで，oofを見たり，色々分析．結構地域で(というか日本だけ)人気のジャンルなどの傾向がちがかった．あと，やっぱNanがおおいやつは予測がむずそう…testにもあるだろうし，ここをどうするか．
- 07.ipynbで，地域ごとに予測した．単純に足しただけでは，改善しなかった．0.97くらい．
- 08.ipynbで，07の予測を元に全体の予測を作ったが，05とかわらず．ちょっと悪くなってしまった．0.95くらい．もっとoofのどこで間違っているかとかみたほうがいい．

---
12/06
- 09.ipynbで，word2vecの効果をいろいろためした
- 10.ipynbで，05をかすたむ．PCAを，train/testどっちもに適用するよう変更
- 11.ipynbで，word2vecを特徴量にして学習．やっぱpublishいれると露骨にさがる．
- 12.ipynbは，ポケモンとかが名前に含まれるか調べてる．
- 13.ipynbは，gotoさんのやつ効果あるか．→多分publishいれてるからcvだけよくなってる．
- 14.ipynbで，翻訳しようとしたらなんかもうバグ
- 15.ipynbで，tifと，word2vec組み合わせたらのびた．
- 16.ipynbで，https://qiita.com/fufufukakaka/items/a7316273908a7c400868#%E3%81%BE%E3%81%A8%E3%82%81%E3%81%A8%E6%84%9F%E3%81%98%E3%81%9F%E8%AA%B2%E9%A1%8C%E3%81%AA%E3%81%A9
これやった
- 17.ipynbで，publisherごとにまとめたら伸びるとか言うからやったら無理だったんだが

---
12/07
- 17.ipynbで，パラメータと，foldと機能できなかったpublisherできた．developperも．
- 18.ipynbで，BERTしたけど，CVのびてLBかわらずだった．また，publisher他の項目もやったけど，のびんかった．
- 19.ipynbで，catboost

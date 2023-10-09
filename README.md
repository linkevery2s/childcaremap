# 子育てマップを作ろう！
![ogp](https://github.com/linkevery2s/childcaremap/assets/23306970/a43c96e1-54c6-4ad3-91c5-2ed52e255b5f)

結婚して3年目。将来的にパパになる自分を想像する毎日ですが、ふと「自分の地域の子育てのことが知りたい！」と思い、早速マップにしてみました。

完成したマップはこちら　→ [一宮市ママパパマップ](https://childcaremap.netlify.app/)


# オープンデータをダウンロードする

一宮市の[オープンデータカタログサイト](https://www.city.ichinomiya.aichi.jp/opendata/)から、子育てに関するデータをダウンロードしました。
   

# csvファイルをgeoJSONファイルに変換する

ネットで調べると様々なツールがあります。自分用に使いたいということと、後々、オープンソース化することを見越して、pythonプログラムをサクッと作ってみました。

詳しくはこちらの記事をご覧ください → [csvファイルをgeoJSONファイルに変換する](https://note.com/hitoshi2s/n/nc12a4daa48f1) 


# マップに載せる

[leaflet](https://leafletjs.com/)を用いて、geoJSONをマップに載せて、属性も表示させます。


# 使用したプラグイン

・[leaflet-hash](https://github.com/mlevans/leaflet-hash)・・・URLにハッシュ値（Zoomや緯度、経度）を含ませることができます。

・[Leaflet.awesome-markers](https://github.com/lennardv2/Leaflet.awesome-markers)・・・leafletはFont Awesomeと親和性が高く、地図の見栄えも良くなります。


# ライセンス
 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja) です。
 
 ご自身が住んでいる地域の子育てマップを作ってみませんか？

## 飛行場一覧の作成
日本国内の飛行場をスプレッドシートでまとめ、GeoJSON ioを用いてGeoJSONファイルを生成する。
そのGeoJSONファイルを地理院地図vectorを用いてインポートし、飛行場一覧を作成する。

### 背景
地理院地図においてDIDは表示されるが、飛行場範囲は反映されていないため

→飛行禁止範囲区域を指定するのは非常に複雑なため、飛行場一覧まとめをGeoJSONファイルで記録する

### レギュレーション
緯度経度は、[地理院地図電子国土WEB](https://maps.gsi.go.jp/#5/35.478565/133.923340/&base=std&ls=std&disp=1&vs=c1j0h0k0l0u0t0z0r0s0m0f1)から参照とする

└緯度経度のズレを防ぐため

└検索をかけた時のラベルの地点を緯度経度とする

対象地は国土交通省が提示している空港とヘリポート全般とする

### 参照
* [スプレッドシート](https://docs.google.com/spreadsheets/d/1_FmYhHCpE0Rr_SXBGBOUYrPH_LQg79eK37jVMataZUg/edit#gid=0)
* [飛行場一覧](https://www.mlit.go.jp/koku/15_bf_000310.html)

## 成果物

※このデータは評点がずれているため、不完全データとなっている

<img width="1440" alt="map2d" src="https://github.com/furuhashilab/gsi_airportmap/blob/main/photos.png?raw=true">

[GeoJSONファイル](https://github.com/furuhashilab/gsi_airportmap/blob/main/datas)

https://github.com/furuhashilab/gsi_airportmap/blob/main/airports.geojson

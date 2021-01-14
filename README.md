## 飛行場一覧の作成
日本国内の飛行場をスプレッドシートでまとめ、GeoJSON ioを用いてGeoJSONファイルを生成する。
そのGeoJSONファイルを地理院地図vectorを用いてインポートし、飛行場一覧を作成する。

### 背景
地理院地図においてDIDは表示されるが、飛行場範囲は反映されていないため
→飛行禁止範囲区域を指定するのは非常に複雑なため、飛行場一覧まとめをGeoJSONファイルで記録する

### レギュレーション
緯度経度は、地理院地図電子国土WEBから参照とする
└緯度経度のズレを防ぐため
対象地は国土交通省が提示している空港とヘリポート全般とする

### 参照
スプレッドシート
飛行場一覧

## 成果物

[GeoJSONファイル](https://github.com/furuhashilab/gsi_airportmap/blob/main/datas)

https://github.com/furuhashilab/gsi_airportmap/blob/main/map.geojson

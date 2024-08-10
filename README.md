# JMA-GIS-GeoJSON

## 概要
- [予報区等GISデータの一覧](https://www.data.jma.go.jp/developer/gis.html)のシェープファイル形式のGISデータを、[mapshaper](https://mapshaper.org/)で簡素化し、GeoJSONに変換したものです。
- 詳細・利用条件等は気象庁ホームページを確認してください。

## ファイル名形式
`{英語名称}_{更新日}.{簡素化率}.geojson`
- `{英語名称}`,`{更新日}`: ZIPファイルの通り(例:`20190125_AreaForecast_GIS.zip` -> `AreaForecast_GIS`,`20190125`)
- `{簡素化率}`: mapshaperのSimplifyでの簡素化率(1%:`1`,0.1%:`01`)

## 更新履歴
### 2024/03/04
初回。2024/02/29更新のものまで

### 2024/08/10
2024/05/20更新のものを追加

### 2024/08/10-2
2024/05/20更新のものを修正
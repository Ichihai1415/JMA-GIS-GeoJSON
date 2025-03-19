# JMA-GIS-GeoJSON

## 概要
- [予報区等GISデータの一覧](https://www.data.jma.go.jp/developer/gis.html)のシェープファイル形式のGISデータを、[mapshaper](https://mapshaper.org/)で簡素化し、GeoJSONに変換したものです。
- 詳細・利用条件等は気象庁ホームページを確認してください。
- 旧データも残します。
- `https://raw.githubusercontent.com/Ichihai1415/JMA-GIS-GeoJSON/refs/heads/release/_url.json` に最新版取得用のバージョン情報があります。

## ファイル名形式
`{英語名称}_{更新日}.{簡素化率}.geojson`
- `{英語名称}`,`{更新日}`: ZIPファイルの通り(例:`20190125_AreaForecast_GIS.zip` -> `AreaForecast_GIS`,`20190125`)
- `{簡素化率}`: mapshaperのSimplifyでの簡素化率(1%:`1`,0.1%:`01`)

## 更新履歴
### 2025/03/19
URL参照用ファイル・更新日ファイルを追加、READMEの調整

### 2024/08/10-2
2024/05/20更新のものを修正

### 2024/08/10
2024/05/20更新のものを追加

### 2024/03/04
初回。2024/02/29更新のものまで

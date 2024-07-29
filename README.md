# 令和 6 年能登半島地震 空中写真の被災前後比較マップ

令和 6 年能登半島地震に関連して被災状況の把握を目的に公開されたデータを MapLibre GL JS で表示するデモサイトです。

## Public Website

https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/

https://github.com/shi-works/noto-hanto-earthquake-2024-gsi-ortho-map-on-maplibre-gl-js/assets/71203808/8be18e7e-b3d9-40c8-b1eb-13a930af5c69

## Data Source

### 国土地理院

- 被災前の空中写真：全国（能登半島：2010 年 4 月～ 5 月撮影）
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#seamlessphoto
- 被災後の空中写真（正射画像）：珠洲地区、輪島東地区、輪島中地区、20240102 撮影
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#t20240102noto_suzu_0102do
- 被災後の空中写真（正射画像）：珠洲地区、輪島中地区、穴水地区、七尾地区、20240105 撮影
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#t20240102_noto_suzu_0105do
- 被災後の空中写真（正射画像）：輪島中地区、穴水地区、輪島西地区、20240111 撮影
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#t20240102noto_wazimanaka_0111do
- 被災後の空中写真（正射画像）：珠洲地区、輪島東地区、穴水地区、20240114 撮影
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#t20240102noto_suzu_0114do
- 被災後の空中写真（正射画像）：輪島西地区、穴水地区、七尾地区、20240117 撮影
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#t20240102noto_wazimanishi_0117do
- 被災後の空中写真（正射画像）：能登地区（2024年4月5日～4月26日撮影）
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#t20240102noto_0405_0426do 
- 斜面崩壊・堆積分布データ（2024 年 1 月 22 日更新）
  - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#2
  - 概要：国土地理院が 1 月 2 日、5 日、11 日、14 日及び 17 日に撮影した空中写真（正射画像）・（珠洲地区、輪島東地区、輪島中地区、輪島西地区、穴水地区、七尾地区）から、令和 6 年能登半島地震によって生じたと考えられる斜面崩壊地及び土砂堆積箇所の範囲について判読（一部は再度判読）したものです。
  - ※1 道路や河川上の土砂は、一部撤去されている可能性があります。
  - ※2 珠洲地区は、1 月 2 日及び 5 日に撮影した空中写真（正射画像）を用いて、輪島東地区は、1 月 2 日に撮影した空中写真（正射画像）を用いて判読しています。
  - ※3 輪島西地区は、1 月 11 日に撮影した空中写真（正射画像）を用いて判読しています。
  - ※4 輪島中地区は、1 月 2 日、5 日及び 11 日に撮影した空中写真（正射画像）を用いて判読しています。
  - ※5 穴水地区は、1 月 5 日、14 日及び 17 日に撮影した空中写真（正射画像）を用いて判読しています。
  - ※6 七尾地区は、1 月 5 日及び 17 日に撮影した空中写真（正射画像）を用いて判読しています。
- 空中写真判読による津波浸水域（推定）データ（2024 年 1 月 19 日更新）

  - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#7
  - 概要：国土地理院が 1 月 2 日、5 日、11 日、14 日及び 17 日に撮影した空中写真（珠洲地区、輪島東地区、輪島西地区、穴水地区、七尾地区）から、令和 6 年能登半島地震によって生じたと考えられる津波到達範囲（堤外地を含む）を判読（一部を再判読）して作成したものです。
  - ※海岸線は空中写真（正射画像）に合わせて取得しており、地形図と整合していない箇所があります。

- 空中写真等の画像判読による輪島市中心の火災焼失範囲（推定）（2024 年 1 月 12 日更新）

  - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#17
  - 概要：国土地理院が令和 6 年 1 月 2 日に撮影した空中写真等を画像判読して輪島市中心の火災による焼失範囲を推定したものです。

- 空中写真で確認した、陸化したと思われる港等（1 月 18 日更新）

  - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#17
  - 概要：下記 HP より港の名称を取得して、空中写真で確認した「隆起の影響で著しく水がなくなっている港データ」を作成。
  - 第九管区海上保安本部海洋情報部 HP：「[航空機から見た石川県の港湾と海岸線](https://www1.kaiho.mlit.go.jp/KAN9/tori-naru/ishikawa-sakuin.htm#ishikawa-plan)」

- 亀裂分布データ（2 月 14 日公表）

  - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#4
  - 概要：地震によって生じたと考えられる地表の亀裂箇所について空中写真を判読して作成。

- 上記の公開データのライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可

### 全国Ｑ地図

- 被災前の空中写真：能登半島（2020 年、2022 年）

  - 出典：https://info.qchizu.xyz/
    - 原初データ出典：[令和 6 年能登半島地震　能登東部写真地図画像データ（発災前）](https://www.geospatial.jp/ckan/dataset/2024-notoeast-ortho)、[令和 6 年能登半島地震　能登西部写真地図画像データ（発災前）](https://www.geospatial.jp/ckan/dataset/2024-notowest-ortho)
  - 測量期間：2020/7/22 ～ 2021/2/26（穴水町,志賀町,七尾市,中能登町,輪島市）、2022/7/13 ～ 2023/2/28（穴水町,七尾市,珠洲市,能登町）
  - 概要：G 空間情報センターにて公開されている、石川県提供の令和 6 年能登半島地震 [能登東部写真地図画像データ（発災前）](https://www.geospatial.jp/ckan/dataset/2024-notoeast-ortho)及び[能登西部写真地図画像データ（発災前）](https://www.geospatial.jp/ckan/dataset/2024-notowest-ortho)を、[山と地図（@Yama_Chizu）](https://twitter.com/Yama_Chizu)様がオルソ画像タイル化したデータです。

- 上記の公開データのライセンス：[Q 地図タイルを表示する Web サイト等の公開](https://info.qchizu.xyz/qchizu/reprint/#toc3)に従い、出典の明示のみで申請不要で利用可能（地理院タイルの取扱と同じ）

### 国土交通省

- 令和 6 年能登半島地震 道路復旧見える化マップ

  - 出典：https://www.mlit.go.jp/road/r6noto/index2.html
  - 掲載情報：緊急復旧済み区間、復旧到達地点、啓開作業状況、啓開前・啓開後比較箇所、主な被災箇所、ETC2.0 速度データ(平均速度)、道の駅の状況、市町道路の状況把握結果（TEC-FORCE 活動報告）、被災状況（360 度画像/三次元点群データ）
  - GeoJSON 形式のデータを国交省のサーバよりダウンロードして、[GitHub リポジトリ](https://github.com/shi-works/noto-hanto-earthquake-2024-gsi-ortho-map-on-maplibre-gl-js/tree/main/data/mlit)でホストしています。
  - データは 1 時間毎に更新されます。
  - [緊急復旧済み区間](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/emergency_restored_section.geojson)
  - [復旧到達地点](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/recovery_point.geojson)
  - [啓開作業状況](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/sagyou.geojson)
  - [啓開前・啓開後比較箇所](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/before_after.geojson)
  - [主な被災箇所](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/damaged_area.geojson)
  - [ETC2.0 速度データ(平均速度)](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/ETC2.0_speed_data.geojson)
  - [道の駅の状況](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/michinoeki.geojson)
  - [市町道路の状況把握結果（TEC-FORCE 活動報告）](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/municipal_road_investigation.geojson)
  - [被災状況（360 度画像/三次元点群データ）](https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-ortho-map-on-maplibre/data/mlit/spherical_image.geojson)

- 上記の公開データのライセンス：[リンク・著作権・免責事項（政府標準利用規約（第 2.0 版）準拠）](https://www.mlit.go.jp/link.html)
<!--

### 東京大学渡邉英徳研究室

- 被災後の SAR 画像：20240106 撮影

  - 出典：https://github.com/wtnv-lab/20240102_Noto_Earthquake_SAR_Umbra/
  - 概要：[Umbra Open Data Program](https://umbra.space/open-data)にて公開されている[Noto Peninsula Earthquake](http://umbra-open-data-catalog.s3-website.us-west-2.amazonaws.com/?prefix=sar-data/tasks/ad%20hoc/Noto%20Peninsula%20Earthquake/)を、東京大学渡邉英徳研究室にて XYZ タイルに変換したものです。

- 上記の公開データのライセンス：[Umbra Open Data Program](https://umbra.space/open-data)、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)
  -->

### 日本地理学会災害対応委員会

- 海岸地形変化の検討結果（1 月 15 日公開）

  - 出典：https://ajg-disaster.blogspot.com/
  - 概要：http://disaster.ajg.or.jp/files/202401_Noto008.pdf

- 上記の公開データのライセンス：令和 6 年能登半島地震変動地形調査グループ（日本地理学会）、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)

### 地域・交通データ研究所

- 令和 2 年簡易 100m メッシュ人口データ（石川県、富山県）（PMTiles 形式）
  - 出典：https://github.com/shi-works/noto-hanto-earthquake-2024-100m-mesh-pop-data
    - 原初データ出典：[地域分析に有用なデータの提供, 地域・交通データ研究所代表（東京大学空間情報科学研究センター客員研究員）西澤明](https://gtfs-gis.jp/teikyo/index.html)
  - 概要：地域・交通データ研究所にて公開されている令和 2 年簡易 100m メッシュ人口データを FlatGeobuf 形式に変換したデータです。
  - ライセンス：[西澤明](https://gtfs-gis.jp/teikyo/index.html)、[@shi-works](https://twitter.com/shi__works)、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)

### 堀池諒｜ GIS 保健師(PHN, Ph.D.)[@GISPHN](https://twitter.com/GISPHN)

- 孤立集落人数データ（石川県）（GeoJSON 形式）
  - 出典：https://x.com/GISPHN/status/1745321675393298538?s=20
    - 原初データ出典：[石川県災害対策本部員会議資料](https://www.pref.ishikawa.lg.jp/saigai/202401jishin-taisakuhonbu.html#honbu)
  - 概要：堀池様（[@GISPHN](https://twitter.com/GISPHN)）が石川県災害対策本部員会議資料の孤立集落の区域と人数を GeoJSON 形式で作成したデータです。
  - 作成方法：https://g-cham.carrd.co/#news10

### 石川県七尾市

- 石川県七尾市避難所開設情報 GIS データ（GeoJSON 形式）
  - 出典：https://github.com/raokiey/R06-Noto-Peninsula-EQ-open-shelter-Nanao
    - 原初データ出典：[七尾市 避難所一覧/開設中の避難所状況](https://www.city.nanao.lg.jp/bosai/mail/202401021200.html)、[石川県 指定緊急避難所一覧](https://www.pref.ishikawa.lg.jp/opendata/shakaikiban_index.html)、[七尾市 10\_指定緊急避難所施設一覧](https://www.city.nanao.lg.jp/koho/shise/koho/opendata/index.html)
  - 概要：石川県七尾市の Web サイトにて公開されている[開設中の避難所情報](https://www.city.nanao.lg.jp/bosai/mail/202401021200.html)を、[ぴっかりん（@ra0kley）](https://twitter.com/ra0kley)様が石川県および七尾市が公開しているオープンデータをもとに位置情報などを付加して、GIS データ化したデータです。
  - ライセンス：[@ra0kley](https://twitter.com/ra0kley)、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

### 背景地図及び地形データ

- 国土地理院 最適化ベクトルタイル
  - 出典：https://github.com/gsi-cyberjapan/optimal_bvmap
  - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 国土地理院 地理院タイル（陰影起伏図）
  - 出典：https://maps.gsi.go.jp/development/ichiran.html#hillshademap
  - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 産業技術総合研究所 シームレス標高タイル（統合 DEM）
  - 出典：https://tiles.gsj.jp/tiles/elev/tiles.html
  - ライセンス：「[産総研地質調査総合センターウェブサイト利用規約](https://www.gsj.jp/license/license.html)」に従い、商用を含む自由な二次利用が可能です。この規約は CC BY 4.0 と互換です。
- 森林総合研究所 CS 立体図(能登(石川県))
  - 出典：https://www2.ffpri.go.jp/soilmap/data-src.html
  - ライセンス：[森林土壌デジタルマップ・利用規約](https://www2.ffpri.go.jp/soilmap/#)参照。

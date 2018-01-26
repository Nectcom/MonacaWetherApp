# 今日の天気は？服装は？

## Description
転轍機のロック値は天候と日照時間によって前後することが経験的に判明している。
現状のロック値管理方法は次の手順による

1.転轍モニタ等でロック値の推移を確認する
2.スマホアプリや気象庁のサイト等で過去の気温と明日以降の天気予報を確認し、明日のロック推移を予測する
3.現状のロック設定の良否を判定する

やりづらさの理由として複数サイトの気象データを取得していること、気象庁のサイトがスマホに対応していないことがあげられる
そこで、DarkSky APIを利用し自動で明日の気温変動は何日前と最も似ているかを判定するアプリを作成する

## 開発メモ
2018/1/26 DarkSkyで毎時の気象データをChart.jsを用いてグラフ化した
しかし横幅が短く醜いのでグリッド表示のほうがまだ現実味がある
グラフは一定以上の幅が確保されている場合に限るべきか

This template is using Onsen UI, a HTML5 framework that is focusing on the speed and ease of use.
For details, please check out [Onsen UI Website](http://onsenui.io) and [the documents](http://onsenui.io/v2/).

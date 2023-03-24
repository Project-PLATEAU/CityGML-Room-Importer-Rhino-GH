# CityGMLクラスRoomをRhinocerosに書き出すためのGrasshopperファイル
## 概要
* Rhinoceros のプラグインである Grasshopper による CityGML クラスの Room の部屋名と形状を Rhinoceros に書き出すためのファイルです。

### 前提ソフトウェア

* 商用ソフトウェア：Rhinoceros, Grasshopper
* ソフトウェアバージョン：Rhino7 以降推奨

## 利用方法

* 上記の前提ソフトウェアをインストール
* 本レポジトリの一式をダウンロードし、任意のディレクトリに置く
* Rhinoceros、Grasshopper を開き、ファイルを Grasshopper に読み込む
* CityGML ファイルを Rhinoceros に取り込む
* Grasshopper に読み込んだスクリプトを使い、CityGML ファイルと接続
※詳細の実行手順は[「3D 都市モデル整備のための BIM 活用マニュアル（第3版）」](https://www.mlit.go.jp/plateau/libraries/handbooks/)資料2第2章ケース1を参照してください。

## 開発について

* 本ファイルは、2022年度に国土交通省が策定した「3D都市モデル標準製品仕様書 第3.0版」に定義された建築物モデル（LOD4）に基づき作成されたCityGML2.0形式の建築物モデルLOD4に含まれるroomクラスの属性情報（名称）及び形状をRhinocerosに書き出すために作成されたGrasshopper用ファイルです。

## License

* ソースコードおよび関連ドキュメントの著作権は国土交通省・デジタル庁に帰属します。
* 本ドキュメントはProject PLATEAUのサイトポリシー（CCBY4.0および政府標準利用規約2.0）に従い提供されています。

## 注意事項

* 本レポジトリは参考資料として提供しているものです。動作保証は行っておりません。
* 予告なく変更・削除する可能性があります。
* 本リポジトリの利用により生じた損失及び損害等について、国土交通省、デジタル庁および著作権者はいかなる責任も負わないものとします。

## 参考資料

* 3D都市モデル整備のためのBIM活用マニュアル（第3.0版）：https://www.mlit.go.jp/plateau/libraries/handbooks/

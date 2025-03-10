
# コアデータモデル解説書 建物 <!-- omit in toc -->

デジタル社会推進実践ガイドブック DS-43A

2022年（令和4年）5月9日

デジタル庁

-----
**[キーワード]**

建物、不動産、データモデル

**[概要]**

建物の情報をシステム実装する際に参照すべきデータモデルについて解説するガイドブックです。このガイドに従いデータ設計を行うことで、同じ設計規則に従うシステム間、分野間でのデータ連携を容易かつ正確に行えるようになります。また、データ設計を実施するコストも削減することができます。

-----

## 改訂履歴 <!-- omit in toc -->

| 改訂年月日   | 改訂箇所 | 改訂内容 |
|--------------|----------|----------|
| 2022年5月9日 | -       | 初版決定 |


## 目次 <!-- omit in toc -->

- [1. 建物のデータモデル](#1-建物のデータモデル)
  - [1.1. 建物データモデルの項目](#11-建物データモデルの項目)
- [2. 関連データ定義](#2-関連データ定義)
  - [2.1. データモデルの関係性](#21-データモデルの関係性)
  - [2.2. コントロールド・ボキャブラリ（統制語彙）](#22-コントロールドボキャブラリ統制語彙)
    - [2.2.1. 種別](#221-種別)
    - [2.2.2. 構造](#222-構造)
    - [2.2.3. 主要用途](#223-主要用途)

-----
## 1. 建物のデータモデル

建物の情報を記述するためのデータモデルです。

必須項目以外は任意項目なので、用途に応じて項目を選択、あるいは独自項目を追加するなどのカスタマイズを行って利用してください。

### 1.1. 建物データモデルの項目

建物データモデルの項目は表1の通りです。英語名や記入例などを含む詳細については、別添の「438_コアデータモデル_DMD.xlsx」を参照してください。

表1 建物データモデルの項目一覧

| 必須項目 | 項目名       | 説明                                                         |
|----------|--------------|--------------------------------------------------------------|
|          | ID           | 機械的に採番された建物を一意に識別するID。建物単位に付番する |
|          | 種別         | 建物の種別                                                   |
| 必       | 名称         | 建物の名称                                                   |
| 必       | 名称（カナ） | 建物のカナ表記                                               |
| 必       | 名称（英字） | 建物の英語名またはローマ字表記                               |
|          | 通称         | 建物に通称がある場合に記入                                   |
|          | 概要         | 建物情報として公開可能な概要情報                             |
| 必       | 説明         | 建物情報として公開可能な詳細情報                             |
|          | 関連建物     | 提携している他建物の情報など（建物型）                       |
|          | 状態         | 「建築」、「稼働中」、「閉鎖中」などのステータス             |
| 必       | 建物住所     | 住所情報（住所型）                                           |
|          | 設備         | 建物内に併設されている設備の情報                             |
|          | 敷地面積     | 建物の敷地面積(m2)                                           |
|          | 主要機能     | 建物の主な働き                                               |
|          | 主要用途     | 建物の主要用途の表記                                         |
|          | 建築面積     | 建物の建築面積(m2)                                           |
|          | 延べ面積     | 建物の延べ床面積(m2)                                         |
|          | 最高の高さ   | 建物の最高点の高さ(m)                                        |
|          | 地上階数     | 建物の地上階数                                               |
|          | 地下階数     | 建物の地下階数                                               |
|          | 構造         | 建物の構造の表記                                             |
|          | 竣工日       | 建物の竣工日                                                 |
|          | 備考         | 建物の備考                                                   |
|          | 連絡先情報   | 連絡先の情報（連絡先型）                                     |

-----
## 2. 関連データ定義

### 2.1. データモデルの関係性

建物は、IMIコア語彙や3D都市モデル標準性仕様書（CityGML）Buildingにも定義があります。その関係性を以下に示します。

表2 建物データモデルと関連モデルとの関係性

| GIFデータ項目        | 対応するIMI   | 対応するCityGML          |
|----------------------|---------------|--------------------------|
| ID                   | ic:ID         | bldg:buildingIDAttribute |
| 種別                 |               |                          |
| 名称                 | ic:名称       | gml:name                 |
| 名称（カナ）         | ic:名称       | gml:name                 |
| 名称（英字）         | ic:名称       | gml:name                 |
| 通称                 | ic:通称       |                          |
| 概要                 | ic:要約       | gml:description          |
| 説明                 | ic:記述       | gml:description          |
| 関連建物             | ic:建物       | bldg:BuildingPart        |
| 状態                 |               |                          |
| 建物住所             | ic:住所       | bldg:address             |
| 設備                 | ic:設備       |                          |
| 敷地面積             | ic:敷地面積   | gml:MeasureType          |
| 主要機能             |               | bldg:function            |
| 主要用途             | ic:主要用途   | bldg:usage               |
| 建築面積             | ic:建築面積   |                          |
| 延べ面積             | ic:延べ面積   |                          |
| 最高の高さ           | ic:最高の高さ | bldg:measuredHight       |
| 地上階数             | ic:地上階数   | bldg:storeysAboveGround  |
| 地下階数             | ic:地下階数   | bldg:storeysBelowGround  |
| 構造                 | ic:構造       |                          |
| 竣工日               | ic:竣工日     | bldg:yearOfConstruction  |
| 備考                 |               |                          |
| 連絡先情報           | ic:連絡先     |                          |
| アクセリビリティ情報 |               |                          |

### 2.2. コントロールド・ボキャブラリ（統制語彙）

#### 2.2.1. 種別

一戸建ての住宅、工場等、建築基準法施行規則（別記様式）に定める建築物用途区分コードを使用できる。

https://elaws.e-gov.go.jp/document?lawid=325M50004000040_20200907_502M60000800074

#### 2.2.2. 構造

不動産登記の「構造」区分を使用できる。

* 構成材料による区分
     * 木造
     * 土蔵
     * 石
     * れんが
     * コンクリートブロック
     * 鉄骨
     * 鉄筋コンクリート
     * 鉄骨鉄筋コンクリート
* 屋根の種類による区分
     * かわらぶき
     * スレートぶき
     * 亜鉛メッキ鋼板ぶき
     * 草ぶき
     * 陸屋根
* 階数による区分
     * 平家建
     * 二階建（三階建以上の建物にあっては、これに準ずるものとする。）

 これらの区分に該当しない建物については、これに準じて定める

#### 2.2.3. 主要用途

都市計画基礎調査実施要領[^1]に準拠する。

| コード | 説明 |
|-------|------|
| 401 | 業務施設 |
| 402 | 商業施設 |
| 403 | 宿泊施設 |
| 404 | 商業系複合施設 |
| 411 | 住宅 |
| 412 | 共同住宅 |
| 413 | 店舗等併用住宅 |
| 414 | 店舗等併用共同住宅 |
| 415 | 作業所併用住宅 |
| 421 | 官公庁施設 |
| 422 | 文教厚生施設 |
| 431 | 運輸倉庫施設設 |
| 441 | 工場 |
| 451 | 農林漁業用施設 |
| 452 | 供給処理施設 |
| 453 | 防衛施設 |
| 454 | その他 |
| 461 | 不明 |

-----

[^1]: https://www.mlit.go.jp/toshi/tosiko/kisotyousa001.html

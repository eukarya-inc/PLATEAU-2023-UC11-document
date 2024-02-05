# 1．Re:Earthへのログイン

## ログイン

- [https://app.reearth.io/](https://app.reearth.io/)にアクセスし、ログインID・パスワードを入力して「ログイン」をクリック
- アカウントを持っていない場合は、新規作成する

![](../resources/userMan/Untitled.png)

# 2．ワークスペースの選択

## ワークスペース

- ワークスペース左上の「ユーザー名」をクリックし、「ワークスペース」からプロジェクトを作成したいワークスペースを選択

![](../resources/userMan/Untitled%201.png)

# ★3．classicプロジェクトでのデータ作成・エクスポート

## classicプロジェクトの作成

- ワークスペースの「クイックスタート」から「新規プロジェクト作成」をクリック

![](../resources/userMan/Untitled%202.png)

- プロジェクトタイプから「classic」をクリック

![](../resources/userMan/Untitled%203.png)

- プロジェクト名、プロジェクト概要（任意）、サムネイル画像（任意）を入力し、「作成」をクリック

![](../resources/userMan/Untitled%204.png)

## マーカー/インフォボックスのデータ作成

- 中央パネルのマーカーアイコンを、3Dマップ上のマーカーを設置したい位置にドラッグ＆ドロップ
- 設置したマーカーを選択した状態で左パネルに表示される設定パネルから、スタイルの変更を行う

![](../resources/userMan/Untitled%205.png)

- 設置したマーカーを選択した状態で左パネルのタブ「インフォボックス」をクリックし、「インフォボックスを作成」をクリック

![](../resources/userMan/Untitled%206.png)

- マーカーのインフォボックスの内容やスタイルを編集

![](../resources/userMan/Untitled%207.png)

## ★マーカー/インフォボックスのデータエクスポート（※インフォボックスもBetaに取り込みたい場合）

- 下記リンクより、プラグインをダウンロード
  - ★Export makers to GeoJSON（GitHubのプラグインデータリンクを貼る）

- 画面上部のプロジェクト名をクリックし、「プラグイン」をクリック

![](../resources/userMan/pc01.png)

- 表示されたプラグイン管理画面で「個人インストール済み」をクリックし、「PCからZipファルをアップロード」をクリック

![](../resources/userMan/pc02.png)

- インストールしたいプラグインを選択し、アップロード

![](../resources/userMan/pc03.png)

- 管理画面の「インストール済み」一覧にアップロードしたプラグインが表示されていることを確認し、画面左上の編集ボタンをクリックしエディターに戻る

![](../resources/userMan/pc04.png)

- 左パネル「ウィジェット」の＋ボタンをクリックし、追加したいプラグインをクリック

![](../resources/userMan/pc05.png)

- 「ウィジェット」の▼ボタンをクリックし、プラグインが追加されているかを確認できる

![](../resources/userMan/pc06.png)

- 右パネル「レイヤー」でフォルダアイコンをクリックしてフォルダを作成
- エクスポートしたいマーカーをすべて作成したフォルダ内にドラッグで移動

![](../resources/userMan/Untitled%208.png)

- 中央のマップ画面左上にあるエクスポート機能のアイコンをクリック

![](../resources/userMan/Untitled%209.png)

- エクスポートしたいマーカーが格納されたフォルダを選択し、「Export to GeoJSON」をクリックし、マーカー/インフォボックスのデータをエクスポート

![](../resources/userMan/Untitled%2010.png)

## マーカーのデータエクスポート（※インフォボックスをBetaで使用しない場合）

- 右パネル「レイヤー」でフォルダアイコンをクリックしてフォルダを作成
- エクスポートしたいマーカーをすべて作成したフォルダ内にドラッグで移動

![](../resources/userMan/Untitled%208.png)

- 右パネルのアイコンリストから「エクスポート」をクリックし、ファイル形式「GeoJOSN」をクリック

![](../resources/userMan/Untitled%2011.png)

- 「エクスポート」をクリック

![](../resources/userMan/Untitled%2012.png)

# 4．Betaプロジェクトの作成

## Betaプロジェクトの作成

- ワークスペースの「クイックスタート」から「新規プロジェクト作成」をクリック

![](../resources/userMan/Untitled%202.png)

- プロジェクトタイプから「Beta」をクリック

![](../resources/userMan/Untitled%2013.png)

- プロジェクト名、プロジェクト概要（任意）、サムネイル画像（任意）を入力し、「作成」をクリック

![](../resources/userMan/Untitled%2014.png)

# 5．Betaプロジェクトのシーン設定

## タイルマップ設定

- 「マップエディター」の左パネル「タイル」をクリックし、右パネルのタイル一覧から「Default」をクリック
- 表示される設定メニューの「Tile type」から変更したいタイルを選択する（デフォルトでは衛星画像が設定されている）

![](../resources/userMan/Untitled%2015.png)

## 地形（Terrain）設定

- 「マップエディター」の左パネル「地形」をクリック
- 右パネルの「有効化」をオンにして地形を有効化
- 「Terrain type」を「Cesium Ion」に変更し、表示される設定項目から以下の通り入力
    - Asset ID: `770371`
    - Access token: `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiI5N2UyMjcwOS00MDY1LTQxYjEtYjZjMy00YTU0ZTg5MmViYWQiLCJpZCI6ODAzMDYsImlhdCI6MTY0Mjc0ODI2MX0.dkwAL1CcljUV7NA7fDbhXXnmyZQU_c-G5zRx8PtEcxE`
    
    ![](../resources/userMan/Untitled%2016.png)
    

## 3Dマップの陰影表現の設定

- 「マップエディター」の左パネル「地球」をクリック
- 右パネル「Globe Shadow」を有効化すると、建物モデルの陰影表現が追加される（描画が重くなる可能性があるので注意）

![](../resources/userMan/Untitled%2017.png)

## 空の表現設定

- 「マップエディター」の左パネル「空」をクリック
- 3Dマップの背景の空の描画設定を変更できる。（デフォルトではすべてオン）
    - Sky BOX：星の描画
    - Sun：太陽の描画
    - Moon：月の描画
    - Sky Atmosphere：大気の描画
    
    ![](../resources/userMan/Untitled%2018.png)
    

## 初期カメラ位置設定（※ストーリーテリングの初期位置とは異なる）

（※）プロジェクトを更新した際に最初に表示される位置を設定。「ストーリーテリング」の初期位置とは異なるので留意

- 「マップエディター」の左パネル「カメラ」をクリック
- 3Dマップを操作し、初期位置に設定したい位置にカメラを調整
- 右パネル「キャプチャ」をクリックし、表示される設定画面右下の「キャプチャ」をクリック

![](../resources/userMan/Untitled%2019.png)

# ★6.Betaエディターへのプラグイン読み込み・設定
## 本ユースケースで使用するプラグイン
- 下記リンクより、プラグインをダウンロード
  - Classical marker infobox（GitHubのプラグインデータリンクを貼る）
  - 3D Tiles feature inspector（GitHubのプラグインデータリンクを貼る）

## プラグインのインストール・設定
- 画面上部のプロジェクト名をクリックし、「プラグイン」をクリック

![](../resources/userMan/pb01.png)

- 表示されたプラグイン管理画面で「個人インストール済み」をクリックし、「PCからZipファルをアップロード」をクリック

![](../resources/userMan/pb02.png)

- インストールしたいプラグインを選択し、アップロード

![](../resources/userMan/pb03.png)

- 管理画面の「インストール済み」一覧にアップロードしたプラグインが表示されていることを確認し、画面左上の編集ボタンをクリックしエディターに戻る

![](../resources/userMan/pb04.png)

- エディター右上の「ウィジェット」をクリックし、ウィジェットエディターに移動
- ウィジェットエディター内右上の追加ボタンをクリックし、インストールしたプラグインを追加

![](../resources/userMan/pb05.png)

- 追加したプラグインのうち、設定を変更したいものをクリックするとインスペクターが表示される

![](../resources/userMan/pb06.png)

# 7．レイヤーの読み込み

## 3D Tilesの読み込み

- 12/9ワークショップにて使用する3D TilesのURLは以下の通り
    - 都市モデル（LOD2）：[https://assets.cms.plateau.reearth.io/assets/f1/ddaa47-16ef-46f7-98b9-1cc76ca76bac/bldg_lod2_no_texture/tileset.json](https://assets.cms.plateau.reearth.io/assets/f1/ddaa47-16ef-46f7-98b9-1cc76ca76bac/bldg_lod2_no_texture/tileset.json)
    - 建物モデル（1街区）：[https://assets.cms.plateau.reearth.io/assets/2c/c6fe5c-192b-4444-b741-695f872aede1/1gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/2c/c6fe5c-192b-4444-b741-695f872aede1/1gaiku_231204/tileset.json)
    - 建物モデル（2街区）：[https://assets.cms.plateau.reearth.io/assets/62/a7a2eb-5151-409f-abd1-820f5243d28b/2gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/62/a7a2eb-5151-409f-abd1-820f5243d28b/2gaiku_231204/tileset.json)
    - 建物モデル（3街区）：[https://assets.cms.plateau.reearth.io/assets/76/3ba1e2-0fbf-4acf-9c99-bd56c1743fdc/3gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/76/3ba1e2-0fbf-4acf-9c99-bd56c1743fdc/3gaiku_231204/tileset.json)
    - 建物モデル（4街区）：[https://assets.cms.plateau.reearth.io/assets/66/ec4e67-85b1-4605-bd77-2f0a013e4887/4gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/66/ec4e67-85b1-4605-bd77-2f0a013e4887/4gaiku_231204/tileset.json)
- 「マップエディター」左パネルの「レイヤー」新規作成アイコンをクリックし、「リソースからレイヤーを追加」をクリック

![](../resources/userMan/Untitled%2020.png)

- 表示されたレイヤー追加画面から「3D Tiles」を選択し、追加したい3D TilesのURLを入力して「レイヤー追加」をクリック

![](../resources/userMan/Untitled%2021.png)

- 追加したレイヤーの名前をダブルクリックして変更

![](../resources/userMan/Untitled%2022.png)

## エクスポートしたマーカー/インフォボックス（GeoJSON）の読み込み

- 「マップエディター」左パネルの「レイヤー」新規作成アイコンをクリックし、「リソースからレイヤーを追加」をクリック

![](../resources/userMan/Untitled%2023.png)

- 表示されたレイヤー追加画面から「Common」を選択。「ファイル形式」を「GeoJSON」、「ソースの種類」を「アセットから追加」にし、「アセット」の「アップロード」をクリック

![](../resources/userMan/Untitled%2024.png)

- 追加したいデータを選択し、アップロード

![](../resources/userMan/Untitled%2025.png)

- アップロードが完了したら、「レイヤー追加」をクリック

![](../resources/userMan/Untitled%2026.png)

- （任意）すでにアップロード済みのアセットから追加したい場合は、「アセット」の「選択」をクリック

![](../resources/userMan/Untitled%2027.png)

- （任意）表示されるアセット一覧から追加したいアセットをクリックし、「選択」をクリック

![](../resources/userMan/Untitled%2028.png)

# 8．レイヤーのスタイル編集（サンプルコード有り）

## スタイルの作成・記述

- マップエディターの中央下「レイヤースタイル」の＋ボタンをクリック

![](../resources/userMan/Untitled%2029.png)

- 作成したレイヤースタイルの名前を変更するには、名前部分をダブルクリック

![](../resources/userMan/Untitled%2030.png)

- 編集したいレイヤースタイルを選択した状態で右パネルに表示されるフィールドにスタイルのコードを記述し、「保存」をクリック

![](../resources/userMan/Untitled%2031.png)

## レイヤーへのスタイルの反映

- レイヤー一覧からスタイルを反映したいレイヤーをクリック
- 右パネルに表示されるアイコンから「スタイリング」のアイコンをクリック
- 右パネルに表示されるスタイル設定ボタンをクリック

![](../resources/userMan/Untitled%2032.png)

- 表示されたレイヤースタイル一覧から反映したいスタイルを選択し、「選択」をクリック

![](../resources/userMan/Untitled%2033.png)

## （サンプル）高さによる色分け For Plateau building 3D Tiles

```jsx
{
  "3dtiles": {
    "color": {
      "expression": {
        "conditions": [
          [
            "${計測高さ}>=180",
            "color('#F9FD4C')"
          ],
          [
            "${計測高さ}>=120",
            "color('#F6CD3D')"
          ],
          [
            "${計測高さ}>=60",
            "color('#EBD384')"
          ],
          [
            "${計測高さ}>=31",
            "color('#9E79BA')"
          ],
          [
            "${計測高さ}>=12",
            "color('#5230C2')"
          ],
          [
            "true",
            "color('#362C52')"
          ]
        ]
      }
    },
    "colorBlendMode": "highlight",
    "pbr": false,
    "shadows": "disabled"
  }
}
```

## （サンプル）用途による色分け For Plateau building 3D Tiles

```json
{
  "3dtiles": {
    "color": {
      "expression": {
        "conditions": [
          [
            "${用途}==='義務施設'",
            "color('#6D4C2E')"
          ],
          [
            "${用途}==='商業施設'",
            "color('#D4332A')"
          ],
          [
            "${用途}==='宿泊施設'",
            "color('#D98DB0')"
          ],
          [
            "${用途}==='商業系複合施設'",
            "color('#D87247')"
          ],
          [
            "${用途}==='住宅'",
            "color('#EDE95D')"
          ],
          [
            "${用途}==='共同住宅'",
            "color('#E7AB9F')"
          ],
          [
            "${用途}==='店舗等併用住宅'",
            "color('#F2EA70')"
          ],
          [
            "${用途}==='店舗等併用共同住宅'",
            "color('#CB3630')"
          ],
          [
            "${用途}==='作業所併用住宅'",
            "color('#A487B3')"
          ],
          [
            "${用途}==='官公庁施設'",
            "color('#326EAA')"
          ],
          [
            "${用途}==='文教厚生施設'",
            "color('#E29F4C')"
          ],
          [
            "${用途}==='運輸倉庫施設'",
            "color('#223681')"
          ],
          [
            "${用途}==='工場'",
            "color('#2E613B')"
          ],
          [
            "${用途}==='農林漁業用施設'",
            "color('#579F7D')"
          ],
          [
            "${用途}==='供給処理施設'",
            "color('#565659')"
          ],
          [
            "${用途}==='防衛施設'",
            "color('#000000')"
          ],
          [
            "${用途}==='その他'",
            "color('#9A9B9F')"
          ],
          [
            "${用途}==='不明'",
            "color('#DBDDDD')"
          ],
          [
            "true",
            "color('white')"
          ]
        ]
      }
    },
    "colorBlendMode": "highlight",
    "pbr": false,
    "shadows": "disabled"
  }
}
```

## （サンプル）インフォボックスも含めてエクスポートしたマーカーの色・サイズ・画像適用

（※）「Marker to GeoJSON」でエクスポートした【インフォボックス付きマーカー】に対応。それ以外のエクスポート方法で出力したデータには非対応のため、「（サンプル）ポイントの色・サイズの変更」を使用する

```jsx
{
  "marker": {
    "height": {
      "expression": "${reearthClassicMarker.height}"
    },
    "heightReference": {
      "expression": "${reearthClassicMarker.heightReference}"
    },
    "image": {
      "expression": "${reearthClassicMarker.image}"
    },
    "imageSize": {
      "expression": "${reearthClassicMarker.imageSize}"
    },
    "imageSizeInMeters": {
      "expression": "${reearthClassicMarker.imageSizeInMeters}"
    },
    "pointColor": {
      "expression": "${reearthClassicMarker.pointColor}"
    },
    "pointOutlineColor": {
      "expression": "${reearthClassicMarker.pointOutlineColor}"
    },
    "pointOutlineWidth": {
      "expression": "${reearthClassicMarker.pointOutlineWidth}"
    },
    "pointSize": {
      "expression": "${reearthClassicMarker.pointSize}"
    },
    "style": {
      "expression": "${reearthClassicMarker.style}"
    }
  }
}
```

## （サンプル）「エクスポート機能」からエクスポートしたマーカー（インフォボックス無し）の色・サイズ・画像の適用

- Point
    
    ```jsx
    {
      "marker": {
        "style": "point",
        "pointColor":"red",
        "pointSize": 12,
    		"pointOutlineColor":"white",
    		"pointOutlineWidth": 1,
    		"height": 100,
    		"heightReference": "relative"
      }
    }
    ```
    
- Marker（画像）
    
    ```jsx
    {
      "marker": {
        "image": "https://assets.cms.plateau.reearth.io/assets/92/b5fab2-af4a-49f9-a6a5-980a32e865c5/Icon_flag.png",
        "imageColor": "red",
        "imageSize": 2,
        "style": "image"
      }
    }
    ```
    

## （サンプル）別サイト等で作ったGeoJSONのスタイルを適用

```jsx
{
  "marker": {
    "pointColor": {
      "expression": "${marker-color}"
    },
    "pointOutlineColor": {
      "expression": "${marker-color}"
    },
    "pointSize": {
      "expression": {
        "conditions": [
          [
            "${marker-size}==='small'",
            "8"
          ],
          [
            "${marker-size}==='medium'",
            "12"
          ],
          [
            "${marker-size}==='large'",
            "16"
          ]
        ]
      }
    },
    "style": "point"
  },
  "polygon": {
    "fillColor": {
      "expression": "color(${fill},${fill-opacity})"
    },
    "heightReference": "clamp",
    "stroke": "true",
    "strokeColor": {
      "expression": "${stroke}"
    },
    "strokeWidth": {
      "expression": "${stroke-width}"
    }
  },
  "polyline": {
    "clampToGround": true,
    "strokeColor": {
      "expression": "color(${stroke},${stroke-opacity})"
    },
    "strokeWidth": {
      "expression": "${stroke-width}"
    }
  }
}
```

## （アイコン画像サンプル）アイコンの画像をデフォルトから変更する場合

下記のリンクに掲載されている画像は、自由に色を変更したりエクスポートしたりすることができます。また、Eukaryaメンバーに「この画像をアイコンに使いたい」と言っていただければその場で作成が可能です。

[https://www.figma.com/file/kElEMT0FZ4oBax6ParE8L2/workshop-icon-Library?type=design&node-id=0-1&mode=design&t=179P5g0w1KVHFnej-0](https://www.figma.com/file/kElEMT0FZ4oBax6ParE8L2/workshop-icon-Library?type=design&node-id=0-1&mode=design&t=179P5g0w1KVHFnej-0)

# 9．ストーリーテリングの作成

## 「ページ」の作成・設定

- 「ストーリー」エディターを開き、左下の「新しいページ」をクリックして「ページ」を新規作成

![](../resources/userMan/Untitled%2034.png)

- 「ページ」のタイトル編集
    - 「ページ」のタイトル部分をクリックして表示される編集ボタンをクリックして編集
- 「ページ」ごとのレイヤー表示/非表示設定
    - 左パネルで編集したい「ページ」を選択した状態で、右パネルの「レイヤー」一覧からこの「ページ」にスクロールしたときに表示するレイヤーを設定（レイヤーはマップエディターから追加する）
- 「ページ」ごとのカメラ位置と遷移アニメーションの設定
    - 右パネルの「Camera Animation」からこの「ページ」にスクロールしたときに最初に表示するカメラ位置を設定。カメラの位置は3Dマップを操作して調整し、「キャプチャ」をする。
    - 「Duration」でこの「ページ」にスクロールしたときのカメラの遷移時間を設定
- 「ページ」ごとのタイムポイントの設定
    - 右パネルの「Time Point Setting」からこの「ページ」にスクロールしたときのタイムポイント（日時）を設定（太陽光や陰影の描画、タイムラインブロックに影響する）
    
    ![](../resources/userMan/Untitled%2035.png)
    

## テキストブロックの作成

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「Text」を選択

![](../resources/userMan/Untitled%2036.png)

- 追加されたテキストブロックをクリックし、編集ボタンをクリックしてテキストを追加。必要に応じてテキストの装飾等を変更

![](../resources/userMan/Untitled%2037.png)

## マークダウンブロックの作成

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「MD Text」を選択

![](../resources/userMan/Untitled%2038.png)

- 追加されたマークダウンブロックをクリックし、編集ボタンをクリックしてテキスト（マークダウン記述）を入力

![](../resources/userMan/Untitled%2039.png)

## 画像ブロックの作成

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「Image」を選択

![](../resources/userMan/Untitled%2040.png)

- 追加された画像ブロックをクリックし、編集ボタンをクリックして画像の追加画面を開く

![](../resources/userMan/Untitled%2041.png)

- URL入力、追加済みのアセットから選択、新規アップロードから追加したい方法を選び画像を追加

![](../resources/userMan/Untitled%2042.png)

## 動画ブロックの作成

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「Image」を選択

![](../resources/userMan/Untitled%2043.png)

- 追加された動画ブロックをクリックし、編集ボタンをクリックして動画の追加画面を開く

![](../resources/userMan/Untitled%2044.png)

- 追加したい動画のURLを入力

![](../resources/userMan/Untitled%2045.png)

## カメラボタン（クリックでカメラが移動するボタン）の作成

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「Camera Button」を選択

![](../resources/userMan/Untitled%2046.png)

- 追加されたカメラボタンをクリックし、編集ボタンをクリックして編集画面を開く

![](../resources/userMan/Untitled%2047.png)

- 編集画面から、編集するボタンを選択し、クリックで移動する先のカメラ位置の設定、遷移にかかる時間、ボタンのタイトルやスタイルを変更。カメラ位置は3Dマップを操作して調整し「キャプチャ」する。

![](../resources/userMan/Untitled%2048.png)

- カメラボタンを追加したい場合は「アイテムを追加」をクリック

![](../resources/userMan/Untitled%2049.png)

- （※）カメラボタンの動作確認をするには、エディター右上の「公開」をクリックし、プレビュー画面から確認する（ストーリーエディター上では動作確認ができない）

## レイヤー表示ボタンの作成

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「show Layers Button」を選択

![](../resources/userMan/Untitled%2050.png)

- 追加されたレイヤー表示ボタンをクリックし、編集ボタンをクリックして編集画面を開く

![](../resources/userMan/Untitled%2051.png)

- 編集画面から、編集するボタンを選択し、ボタンのタイトルやスタイルを変更。
- ボタンクリックによって表示させるレイヤーを設定するには、「Show Layers」をクリック

![](../resources/userMan/Untitled%2052.png)

- ボタンクリックによって表示させるレイヤーを選択。複数選択も可能。

![](../resources/userMan/Untitled%2053.png)

- （※）レイヤー表示ボタンの動作確認をするには、エディター右上の「公開」をクリックし、プレビュー画面から確認する（ストーリーエディター上では動作確認ができない）

## タイムラインブロックの作成

（※）この機能を活用するにはCZML形式の「時間軸」をもったデータが必要

- 「ページ」上にマウスオーバーで表示される＋ボタンをクリックし「Timeline」を選択

![](../resources/userMan/Untitled%2054.png)

- 追加されたタイムラインブロックをクリックし、編集ボタンをクリックして編集画面を開く

![](../resources/userMan/Untitled%2055.png)

- 編集画面から、時間軸をもったデータを再生する開始時間、現在時間、終了時間の設定画面を開く
- 再生をループさせるには、「Play Mode」を変更する

![](../resources/userMan/Untitled%2056.png)

- タイムラインの時間設定を開き、開始時間、現在時間、終了時間それぞれを設定し「Apply」をクリック
    - 「現在時間」とは、プロジェクトを開いたときのデフォルトで設定される時間のこと。通常の「開始時間」からスタートさせたい場合は、「開始時間」と同じ日時を入力。

![](../resources/userMan/Untitled%2057.png)

## ブロックの移動（順番入れ替え）・削除・余白設定

- 作成したブロックを削除するには、ブロックをクリックして表示される歯車アイコンをクリックし、「削除」をクリック

![](../resources/userMan/Untitled%2058.png)

- 作成したブロックの順番を入れ替えたいは、ブロックにマウスオーバーすると表示されるアイコンをクリックした状態でドラッグして移動させたい位置でクリックを解除

![](../resources/userMan/Untitled%2059.png)

- ブロックの余白（上下左右）を変更する場合は、ブロックをクリックして表示される歯車アイコンをクリックし、「余白設定」をクリック
- 表示された余白編集画面で、上下左右の余白を変更

![](../resources/userMan/Untitled%2060.png)

![](../resources/userMan/Untitled%2061.png)

## 「ページ」の位置・背景色の設定

- 画面上部のプロジェクト名をクリックし、「ストーリー」をクリック

![](../resources/userMan/Untitled%2062.png)

- 「パネルポジション」から「ページ」の表示位置の左右を設定

![](../resources/userMan/Untitled%2063.png)

- 「背景色」で「ページ」の背景色を変更（デフォルトは白）

![](../resources/userMan/Untitled%2064.png)

- 「反映」をクリックし、変更を完了

![](../resources/userMan/Untitled%2065.png)

- 編集画面に戻るときは、左上の編集アイコンをクリック

![](../resources/userMan/Untitled%2066.png)

# 11．（任意）ウィジェットの設定

## ナビゲーションの設定

- Betaエディターの右上「ウィジェット」をクリック
- 「ウィジェット管理」から追加ボタンをクリックし、「Nabigator」をクリック

![](../resources/userMan/Untitled%2067.png)

- 「アラインシステム」を有効にすると、設置したナビゲーションの配置を変更できる

![](../resources/userMan/Untitled%2068.png)

# 12．作成したストーリーテリングの公開

## プレビューの確認

- Betaエディターの右上「公開」をクリック
- 「ストーリー」をクリックし、ストーリーテリングのプレビューを確認

![](../resources/userMan/Untitled%2069.png)

## 公開設定・完了

- 右上の「非公開」をクリックし、表示されるメニューから「公開」をクリック

![](../resources/userMan/Untitled%2070.png)

- 公開設定を確認し、「公開」をクリック
    - ドメインを独自のものに変更したい場合は、「設定へ」をクリック
    - 検索エンジンでの検索を可能にしたい場合は、「検索可能」を有効化

![](../resources/userMan/Untitled%2071.png)
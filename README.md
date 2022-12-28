# mypkg

## mypkgについて

このリポジトリ内のmypkgファイルにはlistener.pyとtalker.pyというコマンドが存在します。

## listener.pyとtalker.pyコマンドについて

### コマンドの説明

### トピックについて

## コマンドの使用例

### talker.py

#### 入力例

```
ros2 run mypkg talker
```
#### 出力例

表示されない
```

```

### listener.py

#### 入力例
別の端末を起動後
```
ros2 topic echo /countup
```

#### 出力例
```

data: 1
---
data: 2
---
data: 3
---
   .
   .
   .
```

## テストについて

### テスト環境

* ubuntu 22.04.1 LTS
* Python 3.10.6

### テスト内容

千葉工業大学の上田　隆一先生のコンテナを使用

### テスト結果

![test](https://github.com/RyomaMinami/mypkg/actions/workflows/test.yml/badge.svg)

## LICENSE

* このソフトウェアパッケージは、３条項BSDライセンスの下、再配布および許可が許可されています。
* [LICENSE](https://github.com/RyomaMinami/mypkg/LICENSE)
* このパッケージのコードは千葉工業大学の上田　隆一先生の許可を得て自身の著作としています。
* [上田　隆一先生のスライド](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Ryoma Minami




　

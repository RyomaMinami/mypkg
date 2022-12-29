# mypkg

## mypkgについて

mypkgは千葉工業大学の2022年度ロボットシステム学の授業内課題であり、listener.pyとtalker.pyというコマンドはmypkgファイルの中に存在します。

## listener.pyとtalker.pyコマンドについて

### コマンドの説明

talker.pyがカウントしていった数字をlistener.pyが受け取り、端末に表示する。

### トピックについて

talker.pyというノードからlistener.pyにというノードに対して、std_msgs.msgというトピックがInt16型でパブリッシュされています

## コマンドの使用例

### talker.py

#### 入力例

```
ros2 run mypkg talker
```
#### 出力例

なにも出力されません

### listener.py

#### 入力例
別の端末を起動後
```
ros2 run mypkg listener
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
* ROS2 Humble Hawksbill

### テスト内容

* 千葉工業大学の上田　隆一先生のコンテナを使用
* テストの詳細は[上田　隆一先生のコンテナ](https://hub.docker.com/layers/ryuichiueda/ubuntu22.04-ros2/latest/images/sha256-0e1773bc6f12b57172c8818aac36aeb97ca13269028028d49ad5f6f8cc0d6204?context=explore)をご覧ください
### テスト結果

![test](https://github.com/RyomaMinami/mypkg/actions/workflows/test.yml/badge.svg)

## LICENSE

* このソフトウェアパッケージは、３条項BSDライセンスの下、再配布および許可が許可されています。
* [LICENSE](https://github.com/RyomaMinami/mypkg/blob/master/LICENSE)
* このパッケージのコードは千葉工業大学の上田　隆一先生の許可を得て自身の著作としています。
* [上田　隆一先生の授業内スライド](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Ryoma Minami




　

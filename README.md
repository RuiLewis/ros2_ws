# ros2_ws
ROS2 repository for assignment

# 本プログラムの目的・概要
本プログラムはtalker-listenerの一対一通信をパッケージ化したものである．

# 使用に当たり
## インストール
* 環境内にROS2がインストールされていることを確認する
* 下記の手順に従う
  * git clone https://github.com/RuiLewis/ros2_ws.git
  * ( cd ros2_ws && colcon build )
  * ~/.bashrcの最下段行に"source ~/ros2_ws/install/setup.bash", "source ~/ros2_ws/install/local_setup.bash"を追記
  * source ~/.bashrc

## クイックトライアル
  * ( cd ~/ros2_ws/ && colcon build )
  * source ~/.bashrc
  * talk_listen.launch.py
  * Listen: 10

## テスト
* 下記URLのリポジトリで行ったテストは/ros2_ws/src/mypkg以降の内容についてである．
* github actions上で実施
(https://github.com/RuiLewis/mypkg/actions)

# ライセンス
BSD三条項ライセンス適用，詳細はLICENSEを参照

# 権利関係・謝辞
* 本プログラム内にて使用されるplusコマンドとそのテストは，千葉工業大学準教授，上田隆一先生がはじめて著作，使用された.そのソースコードは以下の講義用資料・動画に紹介されたものを参考とした．
（https://www.youtube.com/watch?v=mBhtD08f5KY&t=1s）
（https://www.youtube.com/watch?v=hkcIRYE9J1M）
（https://www.youtube.com/watch?v=nrNK8Dfbte4&t=1412s）
（https://ryuichiueda.github.io/my_slides/robosys_2022/lesson8.html）
（https://ryuichiueda.github.io/my_slides/robosys_2022/lesson9.html）
（https://ryuichiueda.github.io/my_slides/robosys_2022/lesson10.html）
* このREADME.mdは以下のリポジトリを参考にマークダウン方式で記述された． (https://github.com/ryuichiueda/GlueLang)
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージは，ryuichiueda/emcl由来のコード（© 2022 Ryuichi Ueda）を利用しています．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです． * ryuichiueda/my_slides robosys_2022
* © 2023 Rui Suzuki

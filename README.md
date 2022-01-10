# mypkg
ロボットシステム学　課題2

# 概要
ラズパイ上でROSを用いて、定期的にデータを投げトピックとして得たデータを表示する。

# 実行動画
https://youtu.be/JRWDjip2B3s

# 動作環境
Raspberry Pi 3 (ModelB)

ubuntu20.04 LTS

ROS

# インストール方法
$ cd catkin_ws/src/

$ git clone https://github.com/20C1141/mypkg.git

$ cd .. 

$ catkin_make

$ source ~/.bashrc

# 実行方法
端末1でroscoreを立ち上げる。

$ roscore

端末2でcount.pyを実行する。

$ rosrun mypkg count.py

端末3でtwice.pyを実行する。

$ rosrun mypkg twice.py

端末4で

$ rostopic echo /twice


# ライセンス
GNU　General　Public Licensev3.0

# 著者
Soya Watabe +　Ryuichi Ueda

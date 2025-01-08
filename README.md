# PyLoT Robot Face
[PyLoT Robotics](https://pylot.kaijo-physics.club)で作っているRobotの顔です

# 環境
- bun 1.1.42

# 実行方法
```
#(パッケージ・環境のインストール)
curl -fsSL https://bun.sh/install | bash #bun
sudo apt update
apt search rosbridge_suite #rosbridge_suite
```
```bash
ros2 launch rosbridge_server rosbridge_websocket_launch.xml #rosbridge_serverの起動

git clone https://github.com/Ampoi/pylot-robot-face
cd pylot-robot-face
bun i
bun run dev
```
http://localhost:5173 からアクセスできます。
> 映像を受け取るためにros2のrosbridge_severを実行しておく必要があります。

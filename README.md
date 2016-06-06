# edison-mpu9250

弊社Henryボード用のリポジトリです。
Intel様のupmからMPU9250関係だけ抜き出しました。
Henryボードはi2cのバス接続は6へ接続しているのでサンプルやヘッダファイルの調整もしてあります。
手順は下記の通りです。
git clone https://github.com/MotionCTL/edison-mpu9250.git
cd edison-mpu9250
cmake .
make
make install

# Spresense WORKSHOP　#1 補足情報

株式会社ケイエスワイが提供するSpresenseワークショップに関する補足情報です。

# 環境構築に関して

- Spresense Arduinoスタートガイド<br>
  https://developer.sony.com/spresense/development-guides/arduino_set_up_ja.html

- Arduino IDE<br>
 https://www.arduino.cc/en/software

- Spresense用のボードマネージャー追加用URL<br>
https://github.com/sonydevworld/spresense-arduino-compatible/releases/download/generic/package_spresense_index.json

Arduino IDEの環境設定で上記URLを指定します。

- Processingダウンロードページ<br>
  https://processing.org/download

  

# サンプルコードへのリンク
- USBシリアル経由での画像取得サンプル<br>
 Processing、SPRESENSE両方のサンプルが格納されています。<br>
  https://github.com/TomonobuHayakawa/Spresense-Playground/tree/master/IntegrationWithProcessing/LiveCamera/viaUSBSerial
  
- USBシリアルライブラリ<br>
  https://github.com/baggio63446333/USBSerial

## USBシリアルライブラリのインストール方法
* 上記githubのページからzip形式でダウンロードします。
* Arduino IDEのメニューから[スケッチ]-[ライブラリをインクルード]-[zip形式のライブラリをインストール]を選びます。
* ファイル選択ダイアログが開くので、先ほどダウンロードしたzipファイルを選択します。

# Neural Network Console
- ダウンロード先<br>
 https://nnabla.org/ja/nnc/?_fsi=UkaJuvwg

# サンプル
- Bitmapを作成するライブラリ<br>
  https://github.com/YoshinoTaro/BmpImage_ArduinoLib
  
- データを取得するサンプル<br>
https://github.com/TomonobuHayakawa/Spresense-Playground/tree/master/IntegrationWithProcessing/AiCamera/NumberRecognition/viaUSBSerial/DataCollection

- サンプルの数字のデータ
https://github.com/TE-YoshinoriOota/Spresense-LowPower-EdgeAI/blob/main/Chap07/dnnrt_test/numberRecogTest.zip

- 作成済みの教師データ
  https://github.com/TE-YoshinoriOota/Spresense-LowPower-EdgeAI/blob/main/Chap04/nnc_dataset/number.zip

- 作成済みのNMCサンプルプロジェクト
  https://github.com/TomonobuHayakawa/Spresense-LowPower-EdgeAI/tree/main/Chap04/nnc_project

- 数字読み込みのサンプルプロジェクト
  https://github.com/TomonobuHayakawa/Spresense-Playground/tree/master/IntegrationWithProcessing/AiCamera/NumberRecognition/viaUSBSerial

  


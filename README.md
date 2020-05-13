# Scratch3

*Read this in other languages: [English](README.en.md), [日本語](README.md)*

## 利用できる独自拡張機能

- [ML2Scratch](https://github.com/champierre/ml2scratch) 機械学習を使った画像認識が簡単に体験、利用できます。
- [Posenet2Scratch](https://github.com/champierre/posenet2scratch) 人の姿勢を検出し、身体の各部分のxとyの位置を取得できます。
- [micro:bit More](https://lab.yengawa.com/project/scratch-microbit-more/) Scratchに付属するmicro:bit拡張よりも高機能で、micro:bitに備わっているセンサーや出力の機能をほぼすべて利用できます。
- [TM2Scratch](https://github.com/champierre/tm2scratch) Google Teachable Machine(https://teachablemachine.withgoogle.com/)で作成できる学習モデルを利用して、機械学習を使った画像認識、音声認識が利用できます。
- [Scratch2Maqueen](https://github.com/champierre/scratch2maqueen) グラフィカルプログラミングロボットMaqueenをScratchからリアルタイムにプログラムできます。
- [Facemesh2Scratch](https://github.com/champierre/facemesh2scratch) Webカメラだけで顔のトラッキングができます。
- [Handpose2Scratch](https://github.com/champierre/handpose2scratch) Webカメラだけで手と指のトラッキングができます。
- [PaSoRich](https://github.com/con3office/pasorich) ICカードリーダー「PaSoRi」(パソリ)を利用して、SuicaなどのICカードを読み取ることができます。
- [scratch3-qrcode](https://github.com/sugiura-lab/scratch3-qrcode) QRコードを読み取ります。QRコードは株式会社デンソーウェーブの登録商標です。
- [Speech2Scratch](https://github.com/champierre/speech2scratch) ブラウザの音声認識機能を利用して、音声をテキストに変換します。
- [ImageClassifier2Scratch](https://github.com/champierre/ic2scratch) Webカメラに映った物体を認識し、それが何であるかを判定します。

## How to add a custom extension.

- TBD

## Release Notes

### ML2Scratch

- 3.0.0 2020/03/28 Scratchのステージ画像を学習/判定できるようにした。
- 3.0.1 2020/03/29 デフォルトで、カメラの画像を学習/判定するようにする。ラベル名を自由に設定できるようにする。
- 3.0.2 2020/04/18 「ビデオを切にする」と「カメラの画像を学習/判定する」などのブロックを続けて使用した時、あとに続けたブロックが実行されないバグを修正しました。

### PaSoRich

- 0.4.3 2020/03/20 Improve Connect function

### scratch3-qrcode

- v1.1 2020/05/13 Add error handling to TextDecoder.
- v1.0 2020/05/12 Initial version.

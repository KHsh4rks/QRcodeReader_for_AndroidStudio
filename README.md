# ■ QRcodeReader_for_AndroidStudio

<img src="https://i.imgur.com/lkVEq8B.png" alt="サンプル" title="サンプル">

職業訓練校で勉強したJava言語をもとに、個人的な勉強をかねて作成したポートフォリオです。

内容はシンプルなQRコードリーダーです。CompaundBarcodeViewの情報が少なくとても苦戦しました。

Googleストアへの登録は検討中ですので、未実装項目があります。バグやコードの修正案があればコメントを頂けると幸いです。

## 【開発環境】

・Android Studio: Giraffe | 2022.3.1 Patch 2

・compileSdk: 34

・Java


## 【要件定義】

### 目的
・JavaプログラミングおよびAndroidStudioを利用したGUIデザインの勉強

### システム方式・構成
・基本的なQRコードスキャン（スキャン、スキャンデータの利用）

・フラッシュライト、フロントカメラの切り替え機能

・QRコード画像の生成と保存

・設定画面（アプリの公開が未定のため現在は未実装）

### スケジュール
2023年11月3日(金) 　要件確認、整理、（開発）

2023年11月4日(土) 　開発

2023年11月5日(日)　テスト、テスト結果に伴う調整

## 【使用ライブラリ】

・zxing-android-embedded:4.3.0

[https://github.com/zxing/zxing](https://github.com/journeyapps/zxing-android-embedded)https://github.com/journeyapps/zxing-android-embedded

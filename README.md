# image-combiner
![image1](images/image-1.jpeg)

## Recommended Environment
This tool is designed for use on a PC with the Google Chrome browser. Operation on other devices or browsers is not guaranteed.

## 推奨環境
このツールは、PC上のGoogle Chromeブラウザでの使用を想定しています。他のデバイスやブラウザでの動作は保証されていません。

## Demo
You can try this tool on the page below.

https://black-sesame-ice-cream.github.io/image-combiner/

## デモ
以下のページでこのツールを試すことができます。

https://black-sesame-ice-cream.github.io/image-combiner/

## Overview
**Image Combiner** is a client-side web tool that allows you to easily combine multiple images into a single image file (tiling/mosaic).

* **Privacy First**: All processing is done within your browser using JavaScript. Your images are never uploaded to a server.
* **HEIC Support**: Supports HEIC/HEIF formats (standard on iPhones) in addition to JPEG, PNG, WebP, and GIF.
* **Flexible Layout**:
    * Choose between Horizontal (Z-pattern) or Vertical (N-pattern) tiling.
    * Auto-fill logic repeats images to fill the canvas.
* **Customization**: Adjust canvas size, resize input images while maintaining aspect ratio, set padding (gaps), and change background colors.

## 概要
**Image Combiner** は、複数の画像を簡単に1枚の画像（タイル状）に結合できる、クライアントサイド完結型のWebツールです。

* **プライバシー保護**: すべての処理はJavaScriptを用いてブラウザ上で行われます。画像データがサーバーに送信されることはありません。
* **HEIC対応**: JPEG, PNG, WebP, GIFに加え、iPhoneなどで標準的なHEIC/HEIF形式の読み込みに対応しています。
* **柔軟なレイアウト**:
    * 横方向（Z型）または縦方向（N型）の並べ方を選択できます。
    * キャンバスが埋まるまで、登録した画像を自動でループして配置します。
* **カスタマイズ**: キャンバスサイズの指定、画像のサイズ統一（アスペクト比維持）、余白（padding）の設定、背景色の変更が可能です。

## Usage
1.  **Add Images**: Drag and drop your image files into the "Add Images" area, or click to select files.
    * Supported formats: JPEG, PNG, WebP, BMP, HEIC/HEIF, GIF.
2.  **Manage Pool**: You can check the added images in the "Media Pool" list on the left. Remove unwanted images using the "x" button.
3.  **Configure Settings**: Adjust the canvas settings in the right panel.
    * **Canvas Size**: Set the output width and height (px).
    * **Direction**: Choose how images flow (Horizontal/Vertical).
    * **Resize**: Enable to unify image sizes based on width or height.
    * **Padding/Background**: Set the gap between images and the background color.
4.  **Preview**: Click the "Update Preview" button to render the combined image.
5.  **Download**: Click "Save Image (PNG)" to download the result.

## 使い方
1.  **画像を追加**: 「画像を追加」エリアにファイルをドラッグ＆ドロップするか、クリックしてファイルを選択します。
    * 対応形式: JPEG, PNG, WebP, BMP, HEIC/HEIF, GIF
2.  **プール管理**: 追加された画像は左側の「メディアプール」リストで確認できます。不要な画像は「x」ボタンで削除可能です。
3.  **設定の変更**: 右側のパネルでキャンバスの設定を行います。
    * **キャンバスサイズ**: 出力する画像の幅と高さを指定します。
    * **並べ方**: 画像の並ぶ方向（横方向/縦方向）を選択します。
    * **サイズを揃える**: 有効にすると、横幅または縦幅を基準に画像のサイズを統一します。
    * **余白・背景色**: 画像間の隙間や背景色を指定します。
4.  **プレビュー**: 「プレビューを更新」ボタンを押すと、設定に基づいて画像が描画されます。
5.  **保存**: 「画像を保存 (PNG)」ボタンを押して、完成した画像をダウンロードします。

## Licenses
Please see below for details.

[License](LICENSE/)

[Third-Party Licenses](THIRD-PARTY-LICENSES.txt/)

## ライセンス
以下を参照してください。

[ライセンス](LICENSE/)

[第三者ライセンス](THIRD-PARTY-LICENSES.txt/)

## Tech Stack
* **HTML5 / CSS3**
* **JavaScript (Vanilla)**
* **Tailwind CSS**
* **heic2any**
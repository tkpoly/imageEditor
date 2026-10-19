# imageEditor.exe



## English



### Overview

This application performs high‑speed image processing using DirectX 11 pixel shaders and compute shaders.
It supports gamma correction, brightness, contrast, saturation, blur, and sharpness adjustments.

Processed results can be copied to a CImage buffer and saved in multiple formats.
The viewer also provides smooth zooming, panning, and perspective transformations between
DirectX coordinates and screen coordinates.


## Features
- Tone‑curve based gamma correction
- Brightness, contrast, saturation, blur, and sharpness adjustments
- Supports JPG / BMP / PNG / TIFF / standard RAW formats
- Loads images up to 16000 × 16000 pixels (larger images are auto‑resized)
- Mouse‑wheel zoom centered on screen
- Mouse‑drag scrolling and clipping (FOV transform)
- Perspective transform between DirectX and screen coordinates
- Format conversion and saving


## Development Environment
- Windows 11
- Visual Studio 2022 (VC++ / MFC)
- GPU with DirectX 11 support required


## Class Structure
- MFC main window
- Button UI class
- Editor class (parameter builder)
- DirectX11 device initialization class
- DirectX11 rendering class
- Compute shader initialization and execution class
- Shared header (device pointer repository)


## Source Code (Paid)
The full source code and Visual Studio solution are available on BOOTH.
BOOTH:
https://vcmfc.booth.pm/items/9014039

## GitHub Version (Free)
This GitHub repository provides the free trial version (exe only, no source code).






## 日本語

## プログラムの概要

DirectX11のピクセルシェーダーとコンピュート・シェーダー（CS）を利用して、 高速でガンマ補正、明度、
コントラスト、彩度、ブラー、シャープネス調整を行います。
また、処理結果をCImageバッファーへコピーし、フォーマット変換セーブも可能です


- トーンカーブによる、ガンマ補正
- 明度、コントラスト、彩度、ブラー、シャープネス調整
- 対応フォーマットは、jpg,bmp,png,tif,標準的なRAW
- ロード可能画像サイズ、16000×16000pixel
- スクリーンのセンター中心の、マウスホイールによるズーム、視点移動（フォブ変換使用）
- マウスドラッグによる、スクロール、クリッピング（フォブ変換使用）
- DirectX座標系から、スクリーン座標系へのフォブ逆透視変換
- スクリーン座標系から、DirectX座標系へのフォブ透視変換
- フォーマット変換セーブ


対応画像フォーマットは、jpg / bmp / png / tif（サイズは16000×16000pixelまで）。
それ以上の画像は、自動でリサイズされます。



## 開発環境

- Windows 11
- Visualstudio 2022    VC++ MFC
- GPUがDirectX11をサポートしている必要があります


## クラス

すべてクラス化しているので、個別の応用も可能です。
- MFCメイン
- ボタンクラス
- エディター（パラメーター作成）クラス
- DirectC11のDeviceのイニシャライズクラス
- DrectX11の描画クラス
- コンピュートシェーダーのイニシャライズおよび実行クラス
- 共有ヘッダー（Deviceポインタの貸出倉庫）


## ソースコード（有料）
ソースコードと Visual Studio ソリューションは BOOTH にて販売しています。
BOOTH：
https://vcmfc.booth.pm/items/9014039

## GitHub版（無料）
この GitHub リポジトリは、ソースコードなしの無料版（exeのみ）です。


📘 GIFSmith – 動画 → GIF 変換 & GIF 最適化ツール  
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Version](https://img.shields.io/badge/Version-1.0-green)
![Build](https://img.shields.io/badge/Build-Python%20%2B%20Tkinter-yellow)  
GIFSmith は、  
**動画から GIF を簡単に作成できるデスクトップアプリ**です。  
トリミング、FPS・サイズ調整、最適化など、  
GIF 作成に必要な機能をひとまとめにしています。

🚀 主な機能  
🎞 1. 動画 → GIF 変換  
・開始位置・終了位置のトリミング  
・FPS / 幅の指定  
・プレビュー表示  
・推定ファイルサイズの算出（やや粗い）  
🧹 2. GIF 最適化（軽量化）  
・カラーパレット最適化  
・既存 GIF の圧縮  
・リサイズ  
・プレビュー表示  
・推定ファイルサイズの算出（高精度）  

🖼スクリーンショット  
動画ファイルを読み込み、トリミング範囲・FPS・幅を設定して GIF を生成する画面です。  
<img src="assets/GIFSmith_GIFConversion.png" width="600">  
既存の GIF を読み込み、色数・圧縮レベル・幅・Lossy などを調整して軽量化する画面です。  
<img src="assets/GIFSmith_GIFOptimization.png" width="600"> 

📦 必要ファイル
GIFSmith.exe の動作には、以下 3 つの exe が同じフォルダに必要です。  
ダウンロードして GIFSmith.exe と同じフォルダに置いてください。  
・ffmpeg.exe（動画 → PNG 抽出）  
　→ https://www.gyan.dev/ffmpeg/builds/  
・ffprobe.exe（動画情報の取得）  
　→ ※上記 FFmpeg ZIP に同梱  
・gifsicle.exe（GIF 最適化）  
　→ https://eternallybored.org/misc/gifsicle/  

📁 フォルダ構成（推奨）  
GIFSmith/  
├─ GIFSmith.exe  
├─ ffmpeg.exe  
├─ ffprobe.exe  
└─ gifsicle.exe  

🖥️ 使い方  
1. GIFSmith.exe を起動  
2. 動画 → GIF 変換  
　「動画 → GIF」タブを開く  
　動画を選択  
　トリミング範囲を指定  
　FPS / 幅を設定  
　「GIF を作成」ボタンを押す  
3. GIF 最適化  
　「GIF 最適化」タブを開く  
　GIF を選択  
　圧縮率やサイズを設定  
　「最適化して保存」ボタンを押す  
 

🔧 動作環境  
Windows 10 / 11  
インストール不要（exe 単体で動作）  
ffmpeg.exe / ffprobe.exe / gifsicle.exe が同じフォルダに必要  

📄 ライセンス  
このアプリは個人利用を想定しています。  
ffmpeg / ffprobe / gifsicle はそれぞれのライセンスに従ってください。  

✨ 作者  
mege  
（GIFSmith 開発者）  

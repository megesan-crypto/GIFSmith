📘GIFSmith – 動画 → GIF 変換 & GIF 最適化ツール
　GIFSmith は、
　動画 から GIF を簡単に作成できるデスクトップアプリです。
　トリミング、FPS・サイズ調整、最適化など、
　GIF 作成に必要な機能をひとまとめにしています。
　Python + Tkinter で作成しました。

🚀 主な機能
　1. 動画 → GIF 変換
　　・開始位置・終了位置のトリミング
　　・FPS / 幅の指定
　　・プレビュー表示
　　・推定ファイルサイズの算出（やや粗い）
　2. GIF 最適化（軽量化）
　　・カラーパレット最適化
　　・既存 GIF の圧縮
　　・リサイズ
　　・プレビュー表示
　　・推定ファイルサイズの算出（高精度）

📦 必要ファイル
　GIFSmith.exe の動作には、以下 3 つの exe が同じフォルダに必要です。
　ダウンロードして GIFSmith.exe と同じフォルダに置いてください。
　　・ffmpeg.exe（動画 → PNG 抽出）
　　　→ FFmpeg 公式ダウンロード（Windows）
　　・ffprobe.exe（動画情報の取得）
　　　→ ※上記 FFmpeg の ZIP に 同梱されています
　　・gifsicle.exe（GIF 最適化）
　　　→ gifsicle（Windows版）

※ GIFSmith.exe と同じフォルダに置けば自動で認識します。
📁 フォルダ構成
　GIFSmith/
　　├─ GIFSmith.exe　本体
　　├─ ffmpeg.exe
　　├─ ffprobe.exe
　　└─ gifsicle.exe

🖥️ 使い方
　0. GIFSmith.exeを起動
　1. 動画 → GIF 変換
　　「動画 → GIF」タブを開く
　　動画 を選択
　　トリミング範囲を指定
　　FPS / 幅を設定
　　「GIF を作成」ボタンを押す

　2. GIF 最適化
　　「GIF 最適化」タブを開く
　　GIF を選択
　　圧縮率やサイズを設定
　　「最適化して保存」ボタンを押す

🔧 動作環境
　Windows 10 / 11
　インストール不要（exe 単体で動作）
　ffmpeg.exe / ffprobe.exe / gifsicle.exe が同じフォルダに必要

📁 フォルダ構成
　GIFSmith/
　　├─ GIFSmith.exe
　　├─ ffmpeg.exe
　　├─ ffprobe.exe
　　└─ gifsicle.exe

📄 ライセンス
　このアプリは個人利用を想定しています。
　ffmpeg / ffprobe / gifsicle はそれぞれのライセンスに従ってください。

✨ 作者
　mege
　（GIFSmith 開発者）

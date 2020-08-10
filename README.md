# my-singing-voice-database

歌唱データベースというものをしてみんとてすなり。

作業進捗晒し用リポジトリです。

## 収録者

CrazY **[twitter](https://twitter.com/crazy_toho)**

## 曲

- 赤とんぼ
- あんたがたどこさ

## 制作ポリシー

- だいたい童謡でやります。
- BPM150でやります。
- 1番、2番、3番 および長い休符でファイルを分割してファイル数を稼ぎます。
- 音声ファイルは 24bit/96kHz の FLAC で扱います。

### ファイル名のメモ

- 00_200000_0000.wav
  - 録音そのままのファイル
  - 24bit/**176.4kHz**
- mucicname_denoise.flac 
  - ノイズ除去&ローカット後のファイル
  - 24bit/96kHz
- musicname_pitch_fixed.flac
  - ピッチ補正後のファイル
  - 24bit/96kHz

## 同梱ファイル

- .ini (setParam)
- .vshp (VocalShifter)
- .ust (UTAU)

## 制作環境

### 録音

- REAPER（DAW）
- AT2035（マイク）
- Scarlett Solo（オーディオインターフェース）

### ラベリング

- setParam 200412
- oto2lab


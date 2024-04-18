# Blago
[![License](https://img.shields.io/badge/License-CC--BY--1.0-green.svg)](https://github.com/Jiro-884/Blago\_flows/blob/main/LICENSE)
どんな形にも圧縮します
## Descripshion
各種圧縮フォーマットを統一的なインタフェースで扱うもの

## Usage
```sh
FlexPress [OPTIONS] <ARGUMENTS...>
OPTIONS
  -m, --mode <MODE>     操作モードを extract, archive, auto から選択する．デフォルトは auto.
  -d, --dest <DEST>     出力先のディレクトリを指定する．デフォルトは current directory.
  -o, --output <FILE>   アーカイブの出力ファイル．デフォルトは FlexPress.zip.
  -h, --help            helpメッセージを表示する．
ARGUMENTS
  extract mode: アーカイブファイルを展開する．
  archive mode: ファイルをアーカイブする.
  auto mode:    引数にアーカイブファイルが指定されている場合, 展開する.
                それ以外の場合, ファイルをアーカイブする．
 ```

# buildtool-installer

様々なコンパイラを極力環境を汚さないように利用するためのスクリプトです。

## サポートするツール

- Go
- OCaml
- Rust

## 利用方法

例えば次のコマンドでRustコンパイラのインストールから実行までを自動的に行います。

```bash
build-tool --prefix=tmp --rust-version=2.30.1 rustc main.rs
```

- `--prefix`: ツールをインストールするディレクトリを指定してください。
- `--rust-version`: Rustのバージョンを指定してください。

## プラットフォーム

主にLinuxとMacが対象です。Windowsの場合はWSLで動作するかもしれません。

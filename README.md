# buildtool-installer

様々なコンパイラを極力環境を汚さないように利用するためのスクリプトです。

## サポートするツール

- Rust
    - `rustup`
    - `cargo`
    - `rustc`

## 利用方法

例えば次のコマンドでRustコンパイラのインストールから実行までを自動的に行います。

```bash
PREFIX=tmp RUST_VERSION=2.30.1 build-tool rustc main.rs
```

- `PREFIX`: ツールをインストールするディレクトリを指定してください。
- `RUST_VERSION`: Rustのバージョンを指定してください。

## プラットフォーム

主にLinuxとMacが対象です。Windowsの場合はWSLで動作するかもしれません。

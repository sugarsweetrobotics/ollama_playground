# Haskell Hello World

このディレクトリにはHaskellのHello Worldプログラムが含まれています。

## 実行方法

### ソースコードの実行（GHCインタープリタ使用）
```bash
runhaskell hello_world.hs
```

### コンパイルして実行（GHCコンパイラ使用）
```bash
ghc -o hello_world hello_world.hs
./hello_world
```

## 前提条件

Haskellの開発環境が必要です。以下のいずれかをインストールしてください：

- GHC (Glasgow Haskell Compiler)
- GHCup（Haskellの公式インストーラ）

GHCupを使用してインストールする場合：
```bash
curl --proto '=https' --tlsv1.2 -sSf https://get-ghcup.haskell.org | sh
```
# distsys

[English](README.md) | [日本語](README.ja.md)

分散システムについての個人的な勉強ノートと実装。

## 構成

```
notes/      分散システムの勉強ノート
my_impl/    自分の実装
```

## 実装 (`my_impl/`)

| ディレクトリ | リポジトリ | 内容 |
|---|---|---|
| raft/ | [TKT-Raft](https://github.com/TKTHdev/TKT-Raft) | Raft 合意アルゴリズム |
| pbft/ | [TKT-VBFT](https://github.com/TKTHdev/TKT-VBFT) | PBFT (実用的ビザンチン障害耐性) |
| chain/ | [TKT-Chain-Replication](https://github.com/TKTHdev/TKT-Chain-Replication) | Chain Replication & CRAQ |
| tsujido/ | [Tsujido](https://github.com/TKTHdev/Tsujido) | 合意層統合用のステートマシンライブラリ |

実装はすべて Go で書かれています。

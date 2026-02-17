# distsys

[English](README.md) | [日本語](README.ja.md)

分散システムについての個人的な勉強ノートと実装。

## 構成

```
notes/      分散システムの勉強ノート
my_impl/    自分の実装
```

## 実装 (`my_impl/`)

| ディレクトリ | 内容 |
|---|---|
| [raft/](my_impl/raft/) | Raft 合意アルゴリズム |
| [pbft/](my_impl/pbft/) | PBFT (実用的ビザンチン障害耐性) |
| [chain/](my_impl/chain/) | Chain Replication & CRAQ |
| [tsujido/](my_impl/tsujido/) | 合意層統合用のステートマシンライブラリ |

実装はすべて Go で書かれています。

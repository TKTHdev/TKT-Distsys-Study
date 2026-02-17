# distsys

[English](README.md) | [日本語](README.ja.md)

Personal study notes and implementations on distributed systems.

## Structure

```
notes/      Study notes on distributed systems
my_impl/    My own implementations
```

## Implementations (`my_impl/`)

| Directory | Repository | Description |
|---|---|---|
| raft/ | [TKT-Raft](https://github.com/TKTHdev/TKT-Raft) | Raft consensus algorithm |
| pbft/ | [TKT-VBFT](https://github.com/TKTHdev/TKT-VBFT) | Practical Byzantine Fault Tolerance (PBFT) |
| chain/ | [TKT-Chain-Replication](https://github.com/TKTHdev/TKT-Chain-Replication) | Chain Replication & CRAQ |
| tsujido/ | [Tsujido](https://github.com/TKTHdev/Tsujido) | State machine library for consensus integration |

All implementations are written in Go.

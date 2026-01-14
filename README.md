# Digcount - 採掘回数カウントプラグイン

シンプルな採掘回数カウンタープラグインです。

---

## 機能

- **自動カウント** - ブロック破壊時に自動でカウント
- **ランキング表示** - 採掘回数の多い順に表示
- **自動保存** - 5分ごとに自動保存
- **永続化** - config.ymlにデータ保存

---

## コマンド

| コマンド | 説明 | 権限 |
|---------|------|------|
| `/digcount list` | ランキング表示 | `digcount.use` |
| `/digcount save` | 手動保存 | `digcount.save` |

---

## 権限

| 権限 | デフォルト |
|------|-----------|
| `digcount.use` | true |
| `digcount.save` | op |

---

## ランキング表示例
```
=== 採掘回数ランキング ===
1. Steve: 12345回
2. Alex: 9876回
3. Notch: 5432回
```

---

## 動作環境

- Spigot/Paper 1.21.x
- Java 17以上
- 前提プラグインなし

## コミュニティ

**Discord:** https://discord.gg/zYY55dzhjd

## ライセンス

All Rights Reserved

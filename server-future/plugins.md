# 插件

## 物品邮箱

竹萌自开发插件（[Repository](https://github.com/ImyvmCircle/ItemMail|)），该插件用于未来世界内玩家之间传送物品或未来世界向永恒世界传送物品。与物品种类无关，费用统一为 2.33 D/个（可能会在未来世界快要换档的时候降价）。

* `/imail send [player]`：发送物品给自己（如果不填写 `[player]`）或其他玩家.
* `/imail get`：从远程箱中取回物品（所有）
* `/imail sendtotal`：发送背包中的所有物品到远程箱
* `/imail open`：打开远程箱（仅查看）

其中为了避免 `/imail send` 和 `/imail sendtotal` 误触（导致不必要的支出），这两个操作均需要通过再执行 `/imail confirm` 来确认。


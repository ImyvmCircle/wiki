# 插件

## 物品邮箱

竹萌自开发插件（[Repository](https://github.com/ImyvmCircle/ItemMail)），该插件用于未来世界向永恒世界传送物品，未来世界不可提取。

传送的物品与物品种类无关，费用统一为 0.23 D/个（~~可能会在未来世界快要换档的时候降价~~）。

* `/imail send`：将手持物品传送至远程物品箱
* `/imail sendtotal`：将背包内的所有物品传送至远程物品箱
* `/imail open`：打开远程物品箱（仅查看）

其中为了避免 `/imail send` 和 `/imail sendtotal` 误触（导致不必要的支出），这些操作均需要通过再执行 `/imail confirm` 来确认。


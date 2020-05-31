# 插件

## 物品邮箱

竹萌自开发插件（[Repository](https://github.com/ImyvmCircle/ItemMail|)），该插件用于未来世界向永恒世界传送物品，未来世界不可提取。与物品种类无关，费用统一为 0.233 D/个（~~可能会在未来世界快要换档的时候降价~~）。

* `/imail send`：发送物品给自己.
* `/imail sendtotal`：发送背包中的所有物品到远程箱
* `/imail merge`：打包背包内的物品
* `/imail open`：打开远程箱（仅查看）

其中为了避免 `/imail send` 、 `/imail sendtotal` 和 `/imail merge` 误触（导致不必要的支出），这两个操作均需要通过再执行 `/imail confirm` 来确认。


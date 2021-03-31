# 常用指令

* 本表格将包含竹萌 Minecraft 服务器的大部分常用指令与说明，没有标明收费的即可免费使用。
* 若需手持物品，如无特殊说明，均为**主手持有**。
* 更多详细指令可查阅竹萌百科的其它相关页面，也可通过在游戏内输入 `/menu` 或 `/help` 的方式获取。
* 待完善。

### 传送类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/spawn` | 回到竹萌默认出生点 |  |
| `/tpa [玩家 ID]` | 请求传送至指定玩家 | 收费 11 D |
| `/tpahere [玩家 ID]` | 请求指定玩家传送至自己 | 收费 11 D |
| `/tpacancel` | 取消传送请求 |  |
| `/back` | 返回至上一个位置 | 收费 22 D |
| `/home` | 传送至家 | 收费 11 D |
| `/home bed` | 传送至上一次使用过的床的位置 | 收费 11 D |
| `/home [家的名称]` | 传送至指定名称的家 | 收费 11 D |
| `/sethome` | 设置一个名称为`home`的家 | 收费 (5+n^2)^2 D |
| `/sethome [家的名称]` | 设置一个指定名称的家 | 收费 (5+n^2)^2 D |
| `/delhome [家的名称]` | 删除一个指定名称的家 |  |
| `/server [世界代号]` | 传送至指定的子服务器 |  |

### 经济类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/balance` | 查询银行余额 | `balance`可简写为`bal` |
| `/pay [玩家 ID] [金额]` | 转账至指定玩家 | 执行后**立即转账**，请慎用 |
| `/market search` | 打开名品市场搜索页面 | `market`可简写为`mp` |
| `/market self` | 打开名品市场个人页面 | `market`可简写为`mp`，`self`可用`my`替代 |
| `/market publish [价格]` | 上架手持物品至名品市场 | `market`可简写为`mp`，`publish`可用`sell`替代 |
| `/shop` | 打开箱子商店菜单 |  |
| `/acquisition sell [数量(可选)]` | 向服务器收购所出售手中物品 | `acquisition`可简写为`acq` |
| `/acquisition buy` | 从服务器收购所购买所需物品 | `acquisition`可简写为`acq` |
| `/auction start` | 发起一场拍卖 | `auction`可简写为`auc`，详细信息可参考[拍卖系统](../server-world/plugins/economy.md#auc) |
| `/auction cancel` | 取消当前拍卖 | `auction`可简写为`auc` |
| `/auction remove` | 取消排队中的拍卖 | `auction`可简写为`auc` |
| `/auction spam` | 屏蔽竞拍消息 | `auction`可简写为`auc` |
| `/auction ignore` | 屏蔽所有拍卖 | `auction`可简写为`auc` |
| `/auction ignoreplayer [玩家 ID]` | 屏蔽指定玩家的拍卖 | `auction`可简写为`auc` |
| `/auction info` | 查看当前拍卖的详情 | `auction`可简写为`auc` |
| `/bid [价格]` | 以指定价格参与拍卖 |  |

### 信息类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/rules` | 查看竹萌基本规则 |  |
| `P 键` | 打开社交界面 |  |
| `/menu` | 打开时钟菜单 |  |
| `/inewbee` | 打开结伴系统 |  |
| `/itown` | 打开村落菜单 |  |
| `/homes` | 查看设置的家 |  |
| `/list` | 显示在线玩家 |  |
| `/ptt` | 查看在线时长 |  |
| `/medals` | 查看拥有的徽章 | `medals`可简写为`medal` |
| `/jobs browse` | 查看各职业详情 | 更多信息可通过在游戏内输入 `/jobs` 查询 |
| `/jobs limit` | 显示职业的报酬限制 | 更多信息可通过在游戏内输入 `/jobs` 查询 |
| `/co inspect` | 开启方块变更查询模式，再次输入以关闭该模式 | `inspect`可简写为`i` |
| `/dynmap webregister` | 获取动态地图注册账号与注册码 |  |
| `/tps:tpsx toggle bar` | 在快捷栏上方显示服务器的`TPS`与`MSTP` | `tps:tpsx`可简写为`tpsx` |
| `/tps:tpsx toggle tab` | 在`tab`玩家列表底部显示服务器的`TPS`与`MSTP` | `tps:tpsx`可简写为`tpsx` |
| `/tps:tpsx toggle disable` | 关闭服务器的`TPS`与`MSTP`显示 | `tps:tpsx`可简写为`tpsx` |

### 娱乐类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/tbc` | 查看故事会规则 |  |
| `/tbc play` | 开始一场故事会 |  |
| `/hat` | 将手持物品佩戴至头部 | 可到物品栏里手动佩戴 |
| `/artmap` | 打开绘画菜单 |  |
| `/artmap save [画作名称]` | 保存创作的绘画 |  |
| `/fq stats` | 查看百万问答统计 |  |
| `/reaction wins` | 查看词语快打获胜次数 |  |
| `/reaction top` | 查看词语快打获胜排行 |  |

### 功能类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/custom add [入服消息] [离服消息]` | 添加自定义入服/离服消息 | 收费，详细信息可参考[自定义消息](../server-world/plugins/entertainment.md#cm)；`custom`可简写为`cm` |
| `/custom revoke` | 删除自定义入服/离服消息 | `custom`可简写为`cm` |
| `/fglock` | 上锁指定的物品展示框 | `fglock`可简写为`fglk` |
| `/fgunlock` | 解锁指定的物品展示框 | `fgunlock`可简写为`fgulk` |
| `/afk` | 将状态转换为离开状态 | `afk`可用`away`替代 |
| `/show` | 将手持物品展示至聊天栏 | `show`可简写为`ss` |
| `/excap store all` | 存取经验值(全部) | 需手持`附魔之瓶` |
| `/excap store [数量]` | 存取经验值(指定数量) | 需手持`附魔之瓶` |
| `/excap restore all` | 提取经验值(全部) | 需手持`附魔之瓶` |
| `/excap restore [数量]` | 提取经验值(指定数量) | 需手持`附魔之瓶` |
| `/xpfly` | 开启经验飞行，再次输入以关闭飞行 | 若经验耗尽，飞行将自动关闭(有摔落伤害) |
| `/checklists` | 打开任务清单 | `checklists`可简写为`cl`，详细信息可参考[任务清单](https://discuss.imyvm.org/d/287-checklists) |
| `/clearchat` | 清空聊天栏 |  |
| `/itemmail send` | 将手持物品传送至远程物品箱 | 收费，详细信息可参考[物品邮箱](../server-world/plugins/survice.md#imail)；`itemmail`可简写为`imail` |
| `/itemmail sendtotal` | 将背包内的所有物品传送至远程物品箱 | 收费，详细信息可参考[物品邮箱](../server-world/plugins/survice.md#imail)；`itemmail`可简写为`imail` |
| `/itemmail send [玩家 ID]` | 将手持物品传送至指定玩家的远程物品箱 | 收费，详细信息可参考[物品邮箱](../server-world/plugins/survice.md#imail)；`itemmail`可简写为`imail` |
| `/itemmail merge` | 打包背包内的所有物品至一起 | 收费，详细信息可参考[物品邮箱](../server-world/plugins/survice.md#imail)；`itemmail`可简写为`imail` |
| `/itemmail get` | 从远程物品箱提取物品 | 执行后将提取远程物品箱内的所有物品，若背包空间不足将导致操作失败；`itemmail`可简写为`imail` |
| `/itemmail open` | 查看远程物品箱(仅查看) | `itemmail`可简写为`imail` |
| `/itemmail release` | 提取打包至一起的所有物品(需手持) | `itemmail`可简写为`imail` |


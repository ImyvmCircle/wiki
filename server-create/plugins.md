# 插件

## PlotSquared

* 本插件为地皮插件，表格内将介绍该插件的大部分指令与说明，所介绍的指令仅限**创造世界**使用。
* 若需位于地皮，如无特殊说明，均需为该地皮的所有者。
* 更多详细指令可查阅[PlotSquared - Minecraft插件百科](https://mineplugin.org/PlotSquared)，也可通过在游戏内输入 `/plot help` 或 `/plot` 的方式获取。
* 如有错误或遗漏，欢迎指出！

### 认领类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/plot claim` | 认领你当前所位于的地皮 |  |
| `/plot auto` | 认领最近的地皮 |  |
| `/plot delete` | 删除你当前所位于的地皮 | `delete`可简写为`del` |

### 传送类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/spawn` | 回到**创造世界**的默认出生点 |  |
| `/plot visit [玩家 ID]` | 参观指定玩家的地皮 | 需要拥有`trusted`或`member`权限组；若`[玩家 ID]`留空，则传送至自己已认领的第一个地皮；`visit`可简写为`v` |
| `/plot visit [地皮 ID]` | 参观指定编号的地皮 | 需要拥有`trusted`或`member`权限组；若`[地皮 ID]`留空，则传送至自己已认领的第一个地皮；`visit`可简写为`v` |
| `/plot kick [玩家 ID]` | 从你当前所位于的地皮中踢出指定玩家 | `kick`可简写为`k` |
| `/plot middle` | 传送你至当前所位于的地皮的中心 | 所有地皮均可使用(不论是否已被玩家认领) |

### 权限类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/plot trust [玩家 ID]` | 允许指定玩家在你当前所位于的地皮上进行建筑(`trusted`权限组) | `trust`可简写为`t` |
| `/plot add [玩家 ID]` | 允许指定玩家在你当前所位于的地皮上进行建筑(`member`权限组) | 若该地皮所有者不位于**创造世界**时，则无权进行建筑 |
| `/plot deny [玩家 ID]` | 拒绝指定玩家进入你当前所位于的地皮(`denied`权限组) | `deny`可简写为`d` |
| `/plot remove [玩家 ID]` | 从你当前所位于的地皮的所有权限组中移除指定玩家 | `remove`可简写为`r` |
| `/plot merge all` | 在你当前所位于的地皮上向所有方向合并地皮，合并后将移除道路 | 合并的地皮需要为该地皮的所有者；`merge`可简写为`m` |
| `/plot merge n` | 在你当前所位于的地皮上向北合并地皮，合并后将移除道路 | 合并的地皮需要为该地皮的所有者；`merge`可简写为`m` |
| `/plot merge e` | 在你当前所位于的地皮上向东合并地皮，合并后将移除道路 | 合并的地皮需要为该地皮的所有者；`merge`可简写为`m` |
| `/plot merge s` | 在你当前所位于的地皮上向南合并地皮，合并后将移除道路 | 合并的地皮需要为该地皮的所有者；`merge`可简写为`m` |
| `/plot merge w` | 在你当前所位于的地皮上向西合并地皮，合并后将移除道路 | 合并的地皮需要为该地皮的所有者；`merge`可简写为`m` |
| `/plot unlink` | 在你当前所位于的大地皮上解除该地皮的合并 | `unlink`可简写为`u` |
| `/plot flag set invincible true` | 标记当前所位于的地皮为开启无敌状态 | 玩家需要为`生存模式`或`冒险模式`方可生效；`flag`可简写为`f` |
| `/plot flag set invincible false` | 标记当前所位于的地皮为关闭无敌状态 | 玩家需要为`生存模式`或`冒险模式`方可生效；`flag`可简写为`f` |
| `/plot flag set fly true` | 标记当前所位于的地皮为允许飞行 | 玩家需要为`创造模式`方可生效；`flag`可简写为`f` |
| `/plot flag set fly false` | 标记当前所位于的地皮为禁止飞行 | 玩家需要为`创造模式`方可生效；`flag`可简写为`f` |
| `/plot flag set gamemode creative` | 标记当前所位于的地皮为创造模式，玩家进入后将强制切换 | `flag`可简写为`f` |
| `/plot flag set gamemode survival` | 标记当前所位于的地皮为生存模式，玩家进入后将强制切换 | `flag`可简写为`f` |
| `/plot flag set gamemode adventure` | 标记当前所位于的地皮为冒险模式，玩家进入后将强制切换 | `flag`可简写为`f` |
| `/plot flag set pvp true` | 标记当前所位于的地皮为允许pvp | 玩家需要为`生存模式`或`冒险模式`方可生效；`flag`可简写为`f` |
| `/plot flag set pvp false` | 标记当前所位于的地皮为禁止pvp | 玩家需要为`生存模式`或`冒险模式`方可生效；`flag`可简写为`f` |
| `/plot done` | 标记当前所位于的地皮为已完成 |  |
| `/plot continue` | 标记当前所位于的地皮为未完成 |  |
| `/plot sethome` | 设置家为当前所位于的地皮 |  |

### 装饰类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/plot clear` | 清除你当前所位于的地皮 |  |
| `/plot music` | 设置你当前所位于的地皮将要播放的音乐 |  |

### 信息类

| 指令 | 说明 | 备注 |
| :--- | :--- | :--- |
| `/plot confirm` | 确定你当前的行为 |  |
| `/plot info [地皮 ID]` | 显示指定编号的地皮的信息 |  |
| `/plot list all` | 显示**创造世界**内所有的地皮数量 | `list`可简写为`l` |
| `/plot list unknown` | 显示**创造世界**内所有者为未知的地皮数量 | `list`可简写为`l` |
| `/plot list shared` | 显示**创造世界**内自己(被)共享的地皮数量 | `list`可简写为`l` |
| `/plot list mine` | 显示**创造世界**内自己的地皮数量 | `list`可简写为`l` |
| `/plot plugin` | 显示该插件的信息 |  |
---
ns: PLAYER
---
## GET_PLAYER_PED

```c
// 0x43A66C31C68491C0 0x6E31E993
Ped GET_PLAYER_PED(Player playerId);
```

從指定的玩家單位中獲得其ped實體.

## 參數
* **playerId**: 玩家單位, 若是 -1 則獲得本地玩家ped實體。

## 返回值
被指定的玩家ped實體, 若是無效則為0。

## 例子
```lua
local playerIdx = GetPlayerFromServerId(source)
local ped = GetPlayerPed(playerIdx)

-- 對ped的操作
```

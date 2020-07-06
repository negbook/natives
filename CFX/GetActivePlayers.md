---
ns: CFX
apiset: client
---
## GET_ACTIVE_PLAYERS

```c
object GET_ACTIVE_PLAYERS();
```

返回其客戶端知道的所有'在線'玩家的目錄。
數據遵循下列格式:
```
[127, 42, 13, 37]
```

## 返回值
一個Object數據，包含所有玩家目錄列表。

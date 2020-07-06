---
ns: CFX
apiset: server
---
## GET_ALL_VEHICLES

```c
object GET_ALL_VEHICLES();
```

返回所有服務端知道的vehicle實體目錄列表.
數據遵循下列格式:
```
[127, 42, 13, 37]
```

## 返回值
一個Object數據，包含所有vehicle實體目錄列表.

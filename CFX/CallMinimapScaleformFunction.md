---
ns: CFX
apiset: client
---
## CALL_MINIMAP_SCALEFORM_FUNCTION

```c
BOOL CALL_MINIMAP_SCALEFORM_FUNCTION(int miniMapOverlayID, char* fnName);
```

與PushScaleformMovieFunction 母函數相似, 不同的是它是調用minimap圖層的`TIMELINE` .

## 參數
* **miniMapOverlayID**: minimap圖層ID.
* **fnName**: 一個圖層中TIMELINE的函數名.

## 返回值

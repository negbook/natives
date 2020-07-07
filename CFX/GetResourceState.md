---
ns: CFX
apiset: shared
---
## GET_RESOURCE_STATE

```c
char* GET_RESOURCE_STATE(char* resourceName);
```

Returns the current state of the specified resource.

## 參數
* **resourceName**: The name of the resource.

## 返回值
The resource state. One of `"missing", "started", "starting", "stopped", "stopping", "uninitialized" or "unknown"`.

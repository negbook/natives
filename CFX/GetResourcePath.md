---
ns: CFX
apiset: server
---
## GET_RESOURCE_PATH

```c
char* GET_RESOURCE_PATH(char* resourceName);
```

Returns the physical on-disk path of the specified resource.

## 參數
* **resourceName**: The name of the resource.

## 返回值
The resource directory name, possibly without trailing slash.

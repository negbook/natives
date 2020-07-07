---
ns: CFX
apiset: client
---
## CREATE_RUNTIME_TXD

```c
long CREATE_RUNTIME_TXD(char* name);
```

Creates a runtime texture dictionary with the specified name.
Example:
```lua
local txd = CreateRuntimeTxd('meow')
```

## 參數
* **name**: The name for the runtime TXD.

## 返回值
A handle to the runtime TXD.

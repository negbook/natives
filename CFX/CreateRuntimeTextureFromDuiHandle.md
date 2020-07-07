---
ns: CFX
apiset: client
---
## CREATE_RUNTIME_TEXTURE_FROM_DUI_HANDLE

```c
long CREATE_RUNTIME_TEXTURE_FROM_DUI_HANDLE(long txd, long txn, char* duiHandle);
```

Creates a runtime texture from a DUI handle.

## 參數
* **txd**: A handle to the runtime TXD to create the runtime texture in.
* **txn**: The name for the texture in the runtime texture dictionary.
* **duiHandle**: The DUI handle returned from GET\_DUI\_HANDLE.

## 返回值
The runtime texture handle.

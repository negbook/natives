---
ns: CFX
apiset: client
---
## CREATE_RUNTIME_TEXTURE

```c
long CREATE_RUNTIME_TEXTURE(long txd, char* txn, int width, int height);
```

Creates a blank runtime texture.

## 參數
* **txd**: A handle to the runtime TXD to create the runtime texture in.
* **txn**: The name for the texture in the runtime texture dictionary.
* **width**: The width of the new texture.
* **height**: The height of the new texture.

## 返回值
A runtime texture handle.

---
ns: CFX
apiset: client
---
## CREATE_DUI

```c
long CREATE_DUI(char* url, int width, int height);
```

建立一個DUI瀏覽器。可利用於 CREATE\_RUNTIME\_TEXTURE\_FROM\_DUI\_HANDLE 繪於運行時動態紋理

## 參數
* **url**: 瀏覽器之初始網址。
* **width**: 回傳版面寬度。
* **height**: 回傳版面高度。

## 返回值
一個 DUI object.

---
ns: OBJECT
aliases: ["0x899BA936634A322E", "_GET_DES_OBJECT_STATE"]
---
## GET_STATE_OF_RAYFIRE_MAP_OBJECT

```c
// 0x899BA936634A322E 0xF1B8817A
int GET_STATE_OF_RAYFIRE_MAP_OBJECT(Object object);
```

```
Get a destructible object's state.  
Substract 1 to get the real state.  
See SET_STATE_OF_RAYFIRE_MAP_OBJECT to see the different states  
For example, if the object just spawned (state 2), the native will return 3.  
```

## 參數
* **object**: 

## 返回值

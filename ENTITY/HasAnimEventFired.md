---
ns: ENTITY
---
## HAS_ANIM_EVENT_FIRED

```c
// 0xEAF4CD9EA3E7E922 0x66571CA0
BOOL HAS_ANIM_EVENT_FIRED(Entity entity, Hash actionHash);
```

```
if (ENTITY::HAS_ANIM_EVENT_FIRED(PLAYER::PLAYER_PED_ID(), GAMEPLAY::GET_HASH_KEY("CreateObject")))  
```

## 參數
* **entity**: 
* **actionHash**: 

## 返回值

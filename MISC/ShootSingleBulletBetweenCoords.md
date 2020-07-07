---
ns: MISC
---
## SHOOT_SINGLE_BULLET_BETWEEN_COORDS

```c
// 0x867654CBC7606F2C 0xCB7415AC
void SHOOT_SINGLE_BULLET_BETWEEN_COORDS(float x1, float y1, float z1, float x2, float y2, float z2, int damage, BOOL p7, Hash weaponHash, Ped ownerPed, BOOL isAudible, BOOL isInvisible, float speed);
```

```
this is what p7 does in disassembly  
__int8 var = 32;  
if (isInvisible)  
{  
   var = 16;  
}  
int v110 = var | 2 * p7;  
```

## 參數
* **x1**: 
* **y1**: 
* **z1**: 
* **x2**: 
* **y2**: 
* **z2**: 
* **damage**: 
* **p7**: 
* **weaponHash**: 
* **ownerPed**: 
* **isAudible**: 
* **isInvisible**: 
* **speed**: 


---
ns: WEAPON
---
## GIVE_DELAYED_WEAPON_TO_PED

```c
// 0xB282DC6EBD803C75 0x5868D20D
void GIVE_DELAYED_WEAPON_TO_PED(Ped ped, Hash weaponHash, int ammoCount, BOOL equipNow);
```

```
Gives a weapon to PED with a delay, example:  
WEAPON::GIVE_DELAYED_WEAPON_TO_PED(PED::PLAYER_PED_ID(), GAMEPLAY::GET_HASH_KEY("WEAPON_PISTOL"), 1000, false)  
----------------------------------------------------------------------------------------------------------------------------------------  
Translation table:  
pastebin.com/a39K8Nz8  
```

## 參數
* **ped**: 
* **weaponHash**: 
* **ammoCount**: 
* **equipNow**: 


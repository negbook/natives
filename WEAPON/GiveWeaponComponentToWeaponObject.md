---
ns: WEAPON
---
## GIVE_WEAPON_COMPONENT_TO_WEAPON_OBJECT

```c
// 0x33E179436C0B31DB 0xF7612A37
void GIVE_WEAPON_COMPONENT_TO_WEAPON_OBJECT(Object weaponObject, Hash addonHash);
```

```
addonHash:  
(use WEAPON::GET_WEAPON_COMPONENT_TYPE_MODEL() to get hash value)  
^ Wrong.  
AddonHash is NOT a model hash, it's the weapon component hash.  
${component_at_ar_flsh}, ${component_at_ar_supp}, ${component_at_pi_flsh}, ${component_at_scope_large}, ${component_at_ar_supp_02}  
```

## 參數
* **weaponObject**: 
* **addonHash**: 


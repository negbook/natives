---
ns: CFX
apiset: client
---
## GET_PED_HAIR_COLOR

```c
int GET_PED_HAIR_COLOR(Ped ped);
```

A getter for [_SET_PED_HAIR_COLOR](#_0x4CFFC65454C93A49). Returns -1 if fails to get.

## Examples

```lua
local primaryColour = GetPedHairColor(PlayerPedId())
if primaryColour == 18 then
  print("You have red hair!")
end
```

## 參數
* **ped**: The target ped

## 返回值
Returns ped's primary hair colour.

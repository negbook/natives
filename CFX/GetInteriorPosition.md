---
ns: CFX
apiset: client
---
## GET_INTERIOR_POSITION

```c
void GET_INTERIOR_POSITION(int interiorId, float* posX, float* posY, float* posZ);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)

if interiorId ~= 0 then
  local x, y, z = GetInteriorPosition(interiorId)
  print("current interior " .. interiorId .. " position is: " .. vec(x, y, z))
end
```

## 參數
* **interiorId**: The target interior.

## 返回值
Interior position.
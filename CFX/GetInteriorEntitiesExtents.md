---
ns: CFX
apiset: client
---
## GET_INTERIOR_ENTITIES_EXTENTS

```c
void GET_INTERIOR_ENTITIES_EXTENTS(int interiorId, float* bbMinX, float* bbMinY, float* bbMinZ, float* bbMaxX, float* bbMaxY, float* bbMaxZ);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)

if interiorId ~= 0 then
  local minX, minY, minZ, maxX, maxY, maxZ = GetInteriorEntitiesExtents(interiorId, roomId)
  print("current entities extents is: " .. vec(minX, minY, minZ) .." / " .. vec(maxX, maxY, maxZ))
end
```

## 參數
* **interiorId**: The target interior.

## 返回值
Interior entities extents.

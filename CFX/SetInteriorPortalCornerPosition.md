---
ns: CFX
apiset: client
---
## SET_INTERIOR_PORTAL_CORNER_POSITION

```c
void SET_INTERIOR_PORTAL_CORNER_POSITION(int interiorId, int portalIndex, int cornerIndex, float posX, float posY, float posZ);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)

if interiorId ~= 0 then
  for cornerIndex = 0, 3 do -- 4 corners
    SetInteriorPortalCornerPosition(interiorId, cornerIndex, 0.0, 0.0, 0.0) -- rip portals
  end

  RefreshInterior(interiorId)
end
```

## 參數
* **interiorId**: The target interior.
* **portalIndex**: Interior portal index.
* **cornerIndex**: Interior corner index.
* **posX**:
* **posY**:
* **posZ**:

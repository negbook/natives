---
ns: CFX
apiset: client
---
## GET_INTERIOR_PORTAL_COUNT

```c
int GET_INTERIOR_PORTAL_COUNT(int interiorId);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)

if interiorId ~= 0 then
  local count = GetInteriorPortalCount(interiorId)
  print("interior " .. interiorId .. "has " .. count .. " portals")
end
```

## 參數
* **interiorId**: The target interior.

## 返回值
The amount of portals in interior.
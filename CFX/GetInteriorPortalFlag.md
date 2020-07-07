---
ns: CFX
apiset: client
---
## GET_INTERIOR_PORTAL_FLAG

```c
int GET_INTERIOR_PORTAL_FLAG(int interiorId, int portalIndex);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)

if interiorId ~= 0 then
  local portalFlag = GetInteriorPortalFlag(interiorId, 0)
  print("portal 0 flag is: " .. portalRoomFrom)
end
```

## 參數
* **interiorId**: The target interior.
* **portalIndex**: Interior portal index.

## 返回值
Portal's flag.
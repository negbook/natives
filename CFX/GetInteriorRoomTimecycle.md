---
ns: CFX
apiset: client
---
## GET_INTERIOR_ROOM_TIMECYCLE

```c
int GET_INTERIOR_ROOM_TIMECYCLE(int interiorId, int roomIndex);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)
local roomHash = GetRoomKeyFromEntity(playerPed)
local roomId = GetInteriorRoomIndexByHash(interiorId, roomHash)

if roomId ~= -1 then
  local roomTimecycle = GetInteriorRoomTimecycle(interiorId, roomId)
  print("current room timecycle hash is: " .. roomTimecycle)
end
```

## 參數
* **interiorId**: The target interior.
* **roomIndex**: Interior room index.

## 返回值
Room's timecycle hash.

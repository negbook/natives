---
ns: CFX
apiset: client
---
## GET_INTERIOR_ROOM_INDEX_BY_HASH

```c
int GET_INTERIOR_ROOM_INDEX_BY_HASH(int interiorId, int roomHash);
```

## Examples

```lua
local playerPed = PlayerPedId()
local interiorId = GetInteriorFromEntity(playerPed)
local roomHash = GetRoomKeyFromEntity(playerPed)
local roomId = GetInteriorRoomIndexByHash(interiorId, roomHash)

if roomId ~= -1 then
  print("current room index is: " .. roomId)
end
```

## 參數
* **interiorId**: The target interior.
* **roomHash**: Interior room hash.

## 返回值
Room index, -1 if failed.

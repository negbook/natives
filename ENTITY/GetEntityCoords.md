---
ns: ENTITY
apiset: client
---
## GET_ENTITY_COORDS

```c
// 0x3FEF770D40960D5A 0x1647F1CB
Vector3 GET_ENTITY_COORDS(Entity entity, BOOL alive);
```

Gets the current coordinates for a specified entity.

## 參數
* **entity**: The entity to get the coordinates from.
* **alive**: Unused by the game, potentially used by debug builds of GTA in order to assert whether or not an entity was alive.

## 返回值
The current entity coordinates.

## Examples
```lua
local playerCoords = GetEntityCoords(PlayerPedId())
print(playerCoords) -- vector3(...)
```

```js
const [playerX, playerY, playerZ] = GetEntityCoords(PlayerPedId());
console.log(`${playerX}, ${playerY}, ${playerZ}`);
```

```cs
using static CitizenFX.Core.API;
// ...
Vector3 playerCoords = GetEntityCoords(PlayerPedId());

// or

Vector3 playerCoords = Game.PlayerPed.Position;
```

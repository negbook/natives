---
ns: CFX
apiset: client
---
## GET_VEHICLE_WHEELIE_STATE

```c
int GET_VEHICLE_WHEELIE_STATE(Vehicle vehicle);
```

List of known states:
```
1: Not wheeling.
65: Vehicle is ready to do wheelie (burnouting).
129: Vehicle is doing wheelie.
```

## Examples

```lua
Citizen.CreateThread(function()
  while true do
    Wait(1)

    local veh = GetVehiclePedIsUsing(PlayerPedId())
    if veh ~= 0 then
      local wheelieState = GetVehicleWheelieState(veh)
      if wheelieState == 1 then
        print("Nothing")
      elseif wheelieState == 65 then
        print("Ready to wheelie!")
      elseif wheelieState == 129 then
        print("Doing wheelie!")
      end
    end
  end
end)
```

## 參數
* **vehicle**: Vehicle

## 返回值
Vehicle's current wheelie state.

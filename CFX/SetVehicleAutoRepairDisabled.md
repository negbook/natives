---
ns: CFX
apiset: client
---
## SET_VEHICLE_AUTO_REPAIR_DISABLED

```c
void SET_VEHICLE_AUTO_REPAIR_DISABLED(Vehicle vehicle, BOOL value);
```

Disables the vehicle from being repaired when a vehicle extra is enabled.

## 參數
* **vehicle**: The vehicle to set disable auto vehicle repair.
* **value**: Setting the value to  true prevents the vehicle from being repaired when a extra is enabled. Setting the value to false allows the vehicle from being repaired when a extra is enabled.


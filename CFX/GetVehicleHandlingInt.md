---
ns: CFX
apiset: client
---
## GET_VEHICLE_HANDLING_INT

```c
int GET_VEHICLE_HANDLING_INT(Vehicle vehicle, char* class_, char* fieldName);
```

Returns the effective handling data of a vehicle as an integer value.
Example: `local modelFlags = GetVehicleHandlingInt(vehicle, 'CHandlingData', 'strModelFlags')`

## 參數
* **vehicle**: The vehicle to obtain data for.
* **class_**: The handling class to get. Only "CHandlingData" is supported at this time.
* **fieldName**: The field name to get. These match the keys in `handling.meta`.

## 返回值
An integer.

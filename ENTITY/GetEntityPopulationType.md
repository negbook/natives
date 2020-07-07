---
ns: ENTITY
---
## GET_ENTITY_POPULATION_TYPE

```c
// 0xF6F5161F4534EDFF 0xFC30DDFF
int GET_ENTITY_POPULATION_TYPE(Entity entity);
```

Gets an entity's population type.

**Valid population types:**

```cpp
enum ePopulationType
{
	POPTYPE_UNKNOWN = 0,
	POPTYPE_RANDOM_PERMANENT,
	POPTYPE_RANDOM_PARKED,
	POPTYPE_RANDOM_PATROL,
	POPTYPE_RANDOM_SCENARIO,
	POPTYPE_RANDOM_AMBIENT,
	POPTYPE_PERMANENT,
	POPTYPE_MISSION,
	POPTYPE_REPLAY,
	POPTYPE_CACHE,
	POPTYPE_TOOL
};
```

## 參數
* **entity**: The entity to obtain the population type from.

## 返回值
A population type, from the enumeration above.
---
ns: CFX
apiset: server
---
## REGISTER_CONSOLE_LISTENER

```c
void REGISTER_CONSOLE_LISTENER(func listener);
```

Registers a listener for console output messages.

## 參數
* **listener**: A function of `(channel: string, message: string) => void`. The message might contain `\n`.


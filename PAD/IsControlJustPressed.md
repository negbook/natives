---
ns: PAD
---
## IS_CONTROL_JUST_PRESSED

```c
// 0x580417101DDB492F 0x4487F579
BOOL IS_CONTROL_JUST_PRESSED(int inputGroup, int control);
```

Returns whether a [control](https://docs.fivem.net/game-references/controls/) was newly pressed since the last check.

## 參數
* **inputGroup**: The control system instance to use. Usually set to 0.
* **control**: The control ID to check.

## 返回值
True if the control was pressed.
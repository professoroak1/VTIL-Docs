---
description: XORs a register or immediate value to a register.
---


# XOR

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| XOR | Reg | Reg/Imm | OP1 ^= OP2 |


```cpp
// Creates a temporary register and loads [REG_SP+0] into it.
auto value = block->tmp(8);
block->ldd(value, REG_SP, 0);
```


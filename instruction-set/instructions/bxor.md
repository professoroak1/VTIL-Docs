---
description: XORs a register or immediate value on a register.
---


# BXOR

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| XOR | Reg | Reg/Imm | OP1 ^= OP2 |


```cpp
block->bxor(value, REG_SP, 1);
```


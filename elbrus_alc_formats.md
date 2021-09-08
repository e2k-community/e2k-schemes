|Execution Unit              |Command            |      Channels   ||||||
|----------------------------|:-----------------:|:-:|:-:|:-:|:-:|:-:|:-:|
|                            |                   | 0 | 1 | 2 | 3 | 4 | 5 |
|Integer ALU, Logical, Shifts|two-operand        | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ |
|                            |three-operand      |   | ☑️ |   |   | ☑️ |   |
|                            |cmp                | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |                   |   |   |   |   |   |   |
|Integer MUL                 |mul d/s            | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |                   |   |   |   |   |   |   |
|Integer DIV                 |div                |   |   |   |   |   | ☑️ |
|                            |                   |   |   |   |   |   |   |
|Load/Store Address          |ld                 | ☑️ |   | ☑️ | ☑️ |   | ☑️ |
|                            |st                 |   |   | ☑️ |   |   | ☑️ |
|                            |                   |   |   |   |   |   |   |
|Address transformation      |Address transformation|☑️| ☑️|   | ☑️ | ☑️ |   |
|                            |Load/Store State Registers|☑️|  |   |   |   |
|                            |                   |   |   |   |   |   |   |
|Float-point  ALU            |add/sub d/s/pack   | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ |
|                            |add/sub ex         | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |convert d/s/pack/ex| ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |cmp d/s/ex         | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |                   |   |   |   |   |   |   |
|Float-point  MUL            |d/s/pack           | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ |
|                            |ex                 | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |                   |   |   |   |   |   |   |
|Float-point three-operand   |FP d/s/pack, fma   | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ |
|                            |                   |   |   |   |   |   |   |
|Float-point DIV, SQRT       |fdiv s/d           |   |   |   |   |   | ☑️ |
|                            |remainder          |   |   |   |   |   | ☑️ |
|                            |sqrt s/d           |   |   |   |   |   | ☑️ |
|                            |fdiv ex            |   |   |   |   |   | ☑️ |
|                            |                   |   |   |   |   |   |   |
|Integer VEC                 |shift              | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |logic              | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |add/sub            | ☑️ |   |   | ☑️ |   |   |
|                            |mul                |   | ☑️ |   |   | ☑️ |   |
|                            |                   |   |   |   |   |   |   |
|Float-point VEC             |add/sub            | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ |
|                            |mul                | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ | ☑️ |
|                            |cmp                | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |FMA                | ☑️ | ☑️ |   | ☑️ | ☑️ |   |
|                            |                   |   |   |   |   |   |   |

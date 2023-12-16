### 半加器

A、B 加数，S和，C进位

| A    | B    | S(Sum) | C(Carry) |
| ---- | ---- | ------ | -------- |
| 0    | 0    | 0      | 0        |
| 0    | 1    | 1      | 0        |
| 1    | 0    | 1      | 0        |
| 1    | 1    | 0      | 1        |

逻辑操作表达式：
$$
\begin{aligned}
    S =& \overline{A}B + A\overline{B} \\
    C =& AB
\end{aligned}
$$

逻辑电路

![half-adder-analog-design](assets/half-adder-analog-design.png)

### 全加器

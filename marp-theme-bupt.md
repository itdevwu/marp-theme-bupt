---
marp: true
theme: bupt
math: katex
size: 16:9
paginate: true
---

<!-- _class: milestone -->

# Marp Theme BUPT

<img src='./assets/BUPT_Logo.svg' width='20%' style='margin: auto; padding-top: 1em'>

Author: [itdevwu](https://www.itdevwu.com/)

License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)

---

## Computer Science 计算机科学

这是一门复杂的学科。是现代学科中最年轻的学科之一。

This is a complex subject. It is one of the youngest subjects in modern science.

> This is fabulous!       --I

---

### CS 学科特点

特点：

- 发展快
- 用途广

Features:

- Fast development
- Wide application

---

### Code auto scale supported

Code example: `a funtion returns a lambda funtion`

```C++
#include <iostream>
#include <functional>

// Function returns a lambda function
std::function<int(int)> add(int x)
{
    return [x](int y) { return x + y; };
}

int main()
{
    std::cout << "Hello BUPT!" << std::endl;
    return 0;
}
```

---

## Mathematics 数学

古老而强大。

万物的基础。

Old and powerful.

The foundation of everything.

---

### 学科特色

公式多，太多了！

$\KaTeX$ syntax or mathjax syntax supported

Most famuous equation:

$$
e^{i\pi}+1=0
$$

--- 

### 复杂一点的公式

A more complex equation:

$$
\begin{aligned}
    &A = \oint_C (L \ \mathbf{d}x + M \ \mathbf{d}y) \\
    \mathbf{s.t.}& \\
    &\frac{\partial M}{\partial x} - \frac{\partial L}{\partial y} = 1
\end{aligned}
$$

---

## 来一点点数据？

Data (fake):

|PatchTST|Informer|FEDformer|DLinear|
|-|-|-|-
|1|2|3|4|

数据很好哦！

---

## Acknowledgement 致谢

- [Marp](https://marp.app/)
- [Logo drawn by ipid](https://github.com/ipid)

Reference Themes:

- gaia
- BUAA
- NL

---

<!-- _class: milestone -->

Thank You!
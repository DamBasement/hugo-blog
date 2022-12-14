---
title: DeadCode Manifesto
description: The execution of dead code wastes computation time and memory.
---

In some areas of computer programming, dead code is a section in the source code of a program which is executed but whose result is never used in any other computation. The execution of dead code wastes computation time and memory

```c
int foo (int iX, int iY)
{
	int iZ = iX/iY;

	return iX*iY;
}
```

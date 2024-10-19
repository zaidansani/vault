---
publish: true
title: Pure Functions
---
>[!summary] A function that does not have side effects.

Ideally, we prefer side-effect-free programming - where functions are similar to functions in mathematics, where given an input, a function computes and returns something without affecting anything else.

> [!example] A pure function:
```Java
int square(int i) {
	return i * i;
}
```
> [!example] A impure function:
```Java
int square(int i) {
	i * i;
}
```


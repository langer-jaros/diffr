# diffr - Diff Revisited

Diff recognizing reordering.

## Character Descriptions

* Modified
* Moved
* Changed
* Edited
* Added
* Removed

**Examples**

```py
grades = [67, 100, 87, 56]
```

```py
grades = [100, 67, 87, 56]
```

```
< grades = [67, 100, 87, 56]
---
> grades = [100, 67, 87, 56]
~~~~~~~~~~~~MMMMM~~~~~~~~~~~
```

## Line Description

* Added
* Removed
* Edited
* Moved
* In-moved
* Out-moved

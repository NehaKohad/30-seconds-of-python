---
title: filter_unique
tags: list,beginner
---

Filters out the unique values in a list.

Use list comprehension and `list.count()` to create a list containing only the non-unique values.

```py
def filter_unique(lst):
  return [x for x in set(item for item in lst if lst.count(item) > 1)]
```

```py
filter_unique([1, 2, 2, 3, 4, 4, 5]) # [2, 4]
```

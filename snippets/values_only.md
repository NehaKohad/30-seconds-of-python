---
title: values_only
tags: object,list,beginner
---

Returns a flat list of all the values in a flat dictionary.

Use `dict.values()` to return the values in the given dictionary.
Return a `list()` of the previous result.

```py
def values_only(dict):
  return list(dict.values())
```

```py
ages = {
  "Peter": 10,
  "Isabel": 11,
  "Anna": 9,
}
values_only(ages) # [10, 11, 9]
```

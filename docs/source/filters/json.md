---
title: json
---

Convert values to string via `JSON.stringify()`, for debug purpose.

Input
```liquid
{% assign arr = "foo bar coo" | split: " " %}
{{ arr | json }}
```

Output
```text
["foo","bar","coo"]
```

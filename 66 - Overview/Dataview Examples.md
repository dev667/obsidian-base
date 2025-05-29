---
tags:
  - overview
---

# TABLE all daily notes

```dataview
TABLE file.link AS "Name", file.etags AS "Tags"
FROM #daily AND -"88 - Templates"

```

---

# LIST all daily notes
```dataview
LIST
FROM #daily AND -"88 - Templates"

```

---

# TASKS uncompleted
```dataview
TASK
WHERE !completed
GROUP BY file.link 
```

# TASKS completed
```dataview
TASK
WHERE completed
GROUP BY file.link
```

---

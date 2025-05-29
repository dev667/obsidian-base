---
tags:
  - daily
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
cssclasses:
  - daily 
  - <% tp.date.now("dddd").toLowerCase() %>
---

# DAILY NOTE
## <%tp.date.now("dddd DD MMMM YYYY")%>

<% tp.web.daily_quote() %>




### Academic notes today:
```dataview
LIST
WHERE contains(file.tags, "math") OR contains(file.tags, "digSys") OR contains(file.tags, "algoDat")
AND (file.cday = date(today) OR file.mday = date(today))
```
---

### Notes created today
```dataview
LIST  
WHERE file.cday = date(this.file.name)
```

---

### Notes last edited today:
```dataview
LIST  
WHERE file.mday = date(this.file.name)
```
---

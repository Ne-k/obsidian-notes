---
tag: MOC
desc: 
---

links: [[000 Permaculture]]

# Directory
```dataview
TABLE without ID file.link as "Title", file.mday as "Last modified"
FROM "<% tp.file.folder(true) %>" WHERE file.name != "<% tp.file.title %>"
SORT file.name asc

```



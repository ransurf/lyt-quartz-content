---
created: 2024-05-30T02:51:02
---
## Most backlinks
```dataview
TABLE length(file.outlinks) + length(file.inlinks) as "Total Links", length(file.outlinks) as Out, length(file.inlinks) as In FROM "" SORT length(file.inlinks) desc LIMIT 50
```
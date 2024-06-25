---
created: 2024-05-30T02:51:02
---
## Most backlinks
```dataview
TABLE length(file.outlinks) + length(file.inlinks) as "Total Links", length(file.outlinks) as Outgoing, length(file.inlinks) as Backlists FROM "" SORT length(file.inlinks) desc LIMIT 50
```
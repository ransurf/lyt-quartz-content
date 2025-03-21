---
up:
  - "[[home|home]]"
related:
  - "[[Relate|Relate]]"
  - "[[Communicate|Communicate]]"
created: 2023-08-29T06:52:36
obsidianUIMode: preview
tags:
  - map_view
---
This **Add** note isn't just an inbox. It's a cooling pad 🧊.

Thoughts come in hot. But after a few days, they cool down.

When cooler thoughts prevail, you can better prioritize. Cool? 

> [!activity]+ ## Added Stuff
> This view looks at the 10 newest notes in your **+** folder. As you process each note: add a link, add details, move them to the best folder, and delete everything that no longer sparks ✨. 
> 
> ``` dataview
> TABLE WITHOUT ID
>  file.link as "",
>  (date(today) - file.cday).day as "Days alive"
> 
> FROM "+" and -#x/readme 
> 
> SORT file.cday desc
> 
> LIMIT 10
> ```

---

If you want to encounter some new things, check out: [🐦](https://www.twitter.com) or [📚](https://readwise.io/lyt/)
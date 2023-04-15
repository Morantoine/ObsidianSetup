### Side-Channel
```dataview
table author as "Author", year as "Year", tags as "Tags", contribution as "Contribution"
from "03 - Papers"
WHERE contains(tags, "example")
```

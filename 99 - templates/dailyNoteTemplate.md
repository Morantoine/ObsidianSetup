# Daily Note <% tp.file.title %>

<< [[<% tp.date.now("DD-MM-YYYY", -1, tp.file.title, "DD-MM-YYYY") %>]] | [[<% tp.date.now("DD-MM-YYYY", 1, tp.file.title, "DD-MM-YYYY") %>]]>>
**Tags**:: #DailyNote/<% tp.file.title %>

## Tasks

#### Over Due
```tasks
not done
due before <% tp.date.now("YYYY-MM-DD") %>
```

#### Due Today
```tasks
not done
due on <% tp.date.now("YYYY-MM-DD") %>
```

#### Due within a Week
```tasks
not done
due between <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "DD-MM-YYYY") %> and <% tp.date.now("YYYY-MM-DD", 7, tp.file.title, "DD-MM-YYYY") %>
```

#### New Today
- []

## Other Tasks

#### No Due Date
```tasks
not done
no due date
```

#### Done Today
```tasks
done on <% tp.date.now("YYYY-MM-DD") %>
```

## Notes

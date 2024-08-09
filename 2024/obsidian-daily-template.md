---
aliases:
  - <% tp.date.now("YYYY-MM-DD") %>
Brot: 
Kochen: 
Sudoku: 0
TV: 
---
# <% tp.date.now("YYYY-MM-DD") %>

« [[<% tp.date.now("YYYY-MM-DD", -1) %>]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>]] »

## Allgemeines

- 

## Work

- 

### Heute erstellt

> [!info]+ Heute erstellte Notes
>
> ```dataview
> List FROM "" WHERE file.cday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.ctime asc
> ```

### Heute geänderte Notes

> [!info]- Heute geänderte Notes
>
>```dataview
>List FROM "" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc
>```

## Time Tracking

```simple-time-tracker
```

## Früher

Vor einem Monat: [[<% tp.date.now("YYYY-MM-DD", "P-1M") %>]]
Vor drei Monaten: [[<% tp.date.now("YYYY-MM-DD", "P-3M") %>]]
Vor sechs Monaten: [[<% tp.date.now("YYYY-MM-DD", "P-6M") %>]]
Vor einem Jahr: [[<% tp.date.now("YYYY-MM-DD", "P-1Y") %>]]
Vor zwei Jahren: [[<% tp.date.now("YYYY-MM-DD", "P-2Y") %>]]

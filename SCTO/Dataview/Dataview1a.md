```dataview 
LIST file.ctime
```

```dataview 
LIST FROM "1∩╕ÅΓâú Primary Sources" where rating = "5/5"
```

```dataview
LIST
FROM "≡ƒôå Activity"
```

```dataview
LIST
WHERE file.mtime >= date(today) - dur(1 week)
```

```dataview
TABLE workout
FROM "2∩╕ÅΓâú Collections"
SORT file.ctime DESC
LIMIT 14
```

```dataview 
TABLE DOI, Title FROM "1∩╕ÅΓâú Primary Sources" where rating = "5/5"
```

```dataview
TASK
WHERE !completed
LIMIT 10
GROUP BY file.link
SORT rows.file.ctime ASC
```

```dataview
CALENDAR file.mtime
FROM ""
```

```dataview
TASK
```
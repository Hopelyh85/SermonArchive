```dataview
TABLE
    성경본문 AS "본문",
    설교자 AS "설교자",
FROM "01_Sermons"
WHERE 성경본문 != null
SORT file.mtime DESC
LIMIT 50
```
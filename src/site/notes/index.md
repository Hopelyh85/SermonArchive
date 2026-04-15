---
{"dg-publish":true,"dg-permalink":"index","permalink":"/index/","dg-note-properties":{}}
---


# ⛪ 설교 아카이브

반갑습니다.

이곳은 성경 각 권에 대한 설교들을 정리하여 모아놓은 설교 아카이브입니다.

```dataview
TABLE 
    성경본문 AS "본문", 
    설교자 AS "설교자", 
    상태 AS "상태",
    원문출처 AS "출처"
FROM "01_Sermons"
WHERE 성경본문 != null
SORT 성경본문 ASC
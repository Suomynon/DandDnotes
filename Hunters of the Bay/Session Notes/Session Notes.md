
```dataview
TABLE WITHOUT ID
file.link AS "Session", Date, Player
FROM #Notes 
SORT date desc
WHERE file.name != "Session Notes Template"
```
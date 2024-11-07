
```dataview
TABLE WITHOUT ID
file.link AS "Location", Contains, InLocation
FROM #Location  
WHERE file.name != "Location Template"
```
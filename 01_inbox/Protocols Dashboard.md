
```dataview
TABLE tags
FROM "_templates" AND #protocol 
WHERE !contains(file.name, "protocol template")
```





```dataview
table file.mtime as "Modifié au cours des 5 derniers jours" where file.mtime>=date(today) - dur(5 days) 
sort file.mtime asc
```



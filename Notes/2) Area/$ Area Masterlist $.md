## MasterList

```dataview
table
WHERE contains(file.folder, this.file.folder) 
WHERE file.name != "$ Area Masterlist $"
WHERE file.name != "$ Area Sorted $"
```


```dataview
table
WHERE contains(file.folder, this.file.folder) 
WHERE file.name != "$ Area Masterlist $"
WHERE file.name != "$ Area Sorted $"
SORT file.ctime ASC
```
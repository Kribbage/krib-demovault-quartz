File last modified: `=this.file.mtime`


# Task Matrix
## Urgent and important
```tasks
(happens before tomorrow) AND (priority is above none) AND (status.type is not DONE)
sort by due
```


## Urgent and less important

```tasks
(due today or scheduled today) AND (priority is below medium) AND (status.type is not DONE)
sort by due
```

## Defer and important

```tasks
(due in the next 7 days OR scheduled in the next 7 days) AND (priority is above none) 
sort by due
```

## Defer and less important
      
```tasks
(due in the next 7 days) AND (priority is none)
sort by due
```

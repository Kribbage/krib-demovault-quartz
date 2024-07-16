---
cssClasses: wide-dataview
---


# ToDo

## Tasks

```tasks
(status.type is not IN_PROGRESS) AND (status.type is TODO) AND (no due date)
sort by due date
group by tags
```


## Tasks with Due Date
>[!Todo]+ Tasks with a Due Date
>```tasks
> (status.type is not IN_PROGRESS) AND (status.type is TODO) AND (has due date) AND (due after today) OR (due today)
 >sort by due date
> ```




>[!Warning]+ Overdue Tasks
>```tasks
> (status.type is not IN_PROGRESS) AND (status.type is TODO) AND (has due date) AND (due before today)
 >sort by due date
> ```

## Tasks Due Today

## Task Layout 2 

### Due Today

### Overdue

### Upcoming

### Reminders


### Tasks Calendar

`dataviewjs
await dv.view("tasksCalendar", {pages: "", view: "week", firstDayOfWeek: "1", options: "style3 noFilename noCellNameEvent"})
```



^511458


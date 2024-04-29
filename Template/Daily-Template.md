

## Agenda

> [!todo]+ Today
> ```tasks
> not done
> happens {{date:DD-MM-YYYY}}
> hide recurrence rule
> hide due date
> hide scheduled date
> sort by priority
> ```

> [!danger]+ Overdue 
> ```tasks
> not done
> (due before {{date:DD-MM-YYYY}}) OR ((happens before {{date:DD-MM-YYYY}}) AND (priority is above none))
> hide recurrence rule
> sort by due date
> ```

> [!tip]- Next two weeks
> ```tasks
> not done
> happens after {{date:DD-MM-YYYY}}
> happens before {{date+14d:DD-MM-YYYY}}
> hide recurrence rule
> hide due date
> hide scheduled date
> group by happens
> ```
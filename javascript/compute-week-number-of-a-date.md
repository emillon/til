# Compute the week number of a date

The ISO week date system associates a number to each week in the year.
For example, August 5th 2020 is in week 32 of 2020.

In some cases, the week year is in a different year than the date's year! For
example, December 30th 2019 is in week 1 of 2020.

To compute these using [momentjs], one can use the `.isoWeek()` and
`.isoWeekYear()` functions:

```javascript
const moment = require("moment");

const now = moment();

const year = now.isoWeekYear();
const week = now.isoWeek();
```

[momentjs]: https://momentjs.com/

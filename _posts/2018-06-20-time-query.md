---
title: "Understanding Time Queries"
date: 2018-06-20
---

Understanding Time Queries

Time range query could be confusing. For certain records with date it is easy

For example:
`select * from records where date='2018-06-01'`
gives you the records of that day.

Also, if you would like to get data for multiple days, you could simply use
`select * from records where date>='2018-06-01' AND date<='2018-06-07'`
which would return the records for the first seven days of June.

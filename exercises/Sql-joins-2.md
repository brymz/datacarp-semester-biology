---
layout: exercise
title: Joins 2
subtitle: JOIN for Non-rodents
language: SQL
---

You are curious about what other kinds of animals get caught in the Sherman
traps used to census the rodents. Write a query that returns a list of the
`scientific names` and `Taxa` (from the species table) for non-rodent 
individuals that are caught on the control plots. None rodents are indicated by 
a `0` in the `rodent` column of the `species` table. You are only interested in 
which species are captured, so make this list unique (only one line for each
species). Save this query as `Non-rodents On Controls`.
# 02 - Flattened Lists

## Problem Statement
You have an interview that collects information about `companies`. Each `Company` object contains two variables: `name`, which is a single text value representing the name of the company, and `members`, which is a list of text representing - you guessed it - all of the members of that company. In the provided record, the `companies` list will contain 3 `Company` objects, as follows:
1. Company 1
   1. `name` : `"Avengers"`
   2. `members` : `["Spider-Man", "Iron Man", "Black Widow", "The Winter Soldier", "Hawkeye"]`
2. Company 2
   1. `name` : `"S.H.I.E.L.D."`
   2. `members` : `["Black Widow", "Nick Fury", "Hawkeye", "Alexander Pierce"]`
3. Company 3
   1.  `name` : `"HYDRA"`
   2.  `members` : `["Red Skull", "Alexander Pierce", "Crossbones"]`

## Goal
Create a single list of text that combines the names of all members across all companies. Have the interview display those names as a bulleted list.

## Bonus Goals
### Unique shareholders
Can you get the list of text to exclude duplicate members, both within a single company and across all companies?

## What is Provided
* `problem.zip` - The actual problem to import into your Knackly tenancy.
* `record.json` - The record to be used for this problem. This contains the pre-populated `names` list.
* `solution.zip` - A solution to this problem. Importable into a Knackly tenancy.
* `solution-bonus.zip` - The solution to the bonus problem. Importable into a Knackly tenancy.
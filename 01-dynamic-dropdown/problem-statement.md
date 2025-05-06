# 01 - Dynamic Dropdown

## Problem Statement
You have an interview which collects a list of text (`names`) representing various parties associated with a transaction. In the provided record, this list will contain 5 people: Alice, Bob, Charlie, David, and Emily. You also have a list of `House` objects (`houses`), which each contain two variables: `streetAddress`, which is text (largely irrelevant for this problem), and `owner`, which is a selection (dropdown) variable.

## Goal
Change the behavior of the interview such that the `owner` dropdown is populated with the list of people entered into the `names` list. In the resulting answer file, the value stored for the dropdown selection should be the name of the person.

## Bonus Goals
### Out of Bounds
For any element in the `houses` list beyond the length of the `names` list, can you get it to hide both the `streetAddress` and `owner` variables and instead just display a warning/error message (akin to an indexOutOfBounds error)?

## What is Provided
* `problem.zip` - The actual problem to import into your Knackly tenancy.
* `record.json` - The record to be used for this problem. This contains the pre-populated `names` list.
* `solution.zip` - A solution to this problem. Importable into a Knackly tenancy.
* `solution-bonus.zip` - The solution to the bonus problem. Importable into a Knackly tenancy.
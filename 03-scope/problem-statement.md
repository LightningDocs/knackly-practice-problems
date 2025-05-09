# 03 - Scope

## Problem Statement
You are given an interview that contains two variables: `foo`, which is a number variable, and `bar`, which is an object variable of type `Bar`. `bar` also contains two variables: `foo`, which is a number variable, and `baz` which is an object variable of type `Baz`. `baz` contains one variable: `foo`, which is a number variable. Another way to represent this hierarchy is as follows.

- foo [number]
- bar [Bar]
  - foo [number]
  - baz [Baz]
    - foo [number]

In the provided record, the "top level" `foo` will have a value of `314`, the "middle level" `foo` (the one associated with `bar`) will have a value of `159`, and the "bottom level" `foo` (the one associated with `baz`) will have a value of `265`.

## Goal
Create a text template/formula **on the `Baz` model** that displays the following: `The top level foo is three hundred fourteen. The middle level foo is one hundred fifty-nine. The bottom level foo is two hundred sixty-five.`. Show the result of this text template/formula within the interview.

## What is Provided
* `problem.zip` - The actual problem to import into your Knackly tenancy.
* `record.json` - The record to be used for this problem. This contains the pre-populated `names` list.
* `solution.zip` - A solution to this problem. Importable into a Knackly tenancy.
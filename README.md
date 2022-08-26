# Assignment 7 –   Functions

## Introduction

Functions are a nice abstraction mechanism. They take arguments and return values or tables based on argument values.

## SQL UDF

UDFs abstracts complex queries that depend on parameter values, or complex business logic that can be applied in queries. UDFs are also efficient because they are compiled into database engines before use.

## Scalar, Inline, and Multi-statement Functions

Scalar functions return scalar values. Scalar functions must include scheme names.
Inline functions return a table of values. Inline functions may return different tables depending on parameter values.
Multi-statement functions are like inline functions in that they return a table, but unlike inline inline functions,  multi-statement functions may run different queries depending on parameter values. This means table widths may change in different calls of multi-statement functions.

## Summary

Functions are part of procedural programming extension of SQL that are extremely powerful in practical use.

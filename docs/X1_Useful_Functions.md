---
title: "Ref - Useful Functions"
author: "Jonny Saunders"
date: "October 5, 2017"
output: 
  md_document:
    preserve_yaml: true
    toc: true
    toc_depth: 2
order: 100
---

# Workspace

Function | Function function
---------- | ----------
`getwd()`  | Return your working directory
`setwd()`  | Assign a working directory to use for the current session
`ls()`     | List the objects in an environment
`rm(x)`     | Remove an object from the workspace (in this example, `x`)
`rm(list=ls())` | Remove all objects from the workspace
`history()` | Show the last 25 commands


# Objects
Function | Function function
---------- | ----------
typeof | Get object's base type
pryr::otype | Get object's type system (base, S3, S4, RC)

# Iteration

Function | Function function
--------- | ------------
`txtProgressBar` | Keep track of how things are going


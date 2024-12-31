# Lua Pairs Iterator and Table Modification

This repository demonstrates a subtle bug related to Lua's `pairs` iterator and table modification during iteration.  The provided code (`bug.lua`) recursively iterates through a nested table.  Under certain conditions, this can lead to unexpected behavior or even a stack overflow if the table structure is deeply nested.

The solution (`bugSolution.lua`) illustrates a safer approach to iterating and modifying nested tables.
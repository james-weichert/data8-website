---
layout: page
title: Python Reference
description: >-
    Python Reference Guide
---

# Python Reference
Created by Nishant Kheterpal and Jessica Hu

## Table Functions and Methods
In the examples in the left column, np refers to the NumPy module, as usual. Everything else is a function, a method, an example of an argument to a function or method, or an example of an object we might call the method on. For example, tbl refers to a table, array refers to an array, and num refers to a number. array.item(0) is an example call for the method item, and in that example, array is the name previously given to some array.

| **Name** | **Chapter** | **Description** | **Input** | **Output** |
| `Table()` | 6 | 	Create an empty table, usually to extend with data | None | An empty **Table** |
| `Table().read_table(filename)` | 6 | Create a table from a data file | **string**: the name of the file | 	**Table** with the contents of the data file |
| `tbl.with_columns(name, values)` <br> `tbl.with_columns(n1, v1, n2, v2,...)` | 6 | A table with an additional or replaced column or columns. `name` is a string for the name of a column, `values` is an array | 1. **string**: the name of the new column; <br> 2. **array**: the values in that column | **Table**: a copy of the original Table with the new columns added |
| `tbl.column(column_name_or_index)` | 6 | The values of a column (an array) | **string** or **int**: the column name or index | **array**: the values in that column |

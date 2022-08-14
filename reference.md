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

| **Name** | **Description** | **Input** | **Output** |
| `Table()` | Create an empty table, usually to extend with data (Ch 6) | None | An empty **Table** |
| `Table().read_table(filename)` | Create a table from a data file (Ch 6) | **string**: the name of the file | 	**Table** with the contents of the data file |
| `tbl.with_columns(name, values)` <br> `tbl.with_columns(n1, v1, n2, v2,...)` | A table with an additional or replaced column or columns. `name` is a string for the name of a column, `values` is an array (Ch 6) | 1. **string**: the name of the new column; <br> 2. **array**: the values in that column | **Table**: a copy of the original Table with the new columns added |
| `tbl.column(column_name_or_index)` | The values of a column (an array) (Ch 6) | **string** or **int**: the column name or index | **array**: the values in that column |
| `tbl.num_rows` | Compute the number of rows in a table (Ch 6) | None | **int**: the number of rows in the table |
| `tbl.num_columns` | Compute the number of columns in a table (Ch 6) | None | **int**: the number of columns in the table |
| `tbl.labels` | Lists the column labels in a table (Ch 6) | None | **array**: the names of each column (as strings) in the table |
| `tbl.select(col1, col2, ...)` | Create a copy of a table with only some of the columns. Each column is the column name or index. (Ch 6) | **string** _or_ **int**: column name(s) or index(es) | **Table** with the selected columns|
| `tbl.drop(col1, col2, ...)` | Create a copy of a table without some of the columns. Each column is the column name or index. (Ch 6) | **string** _or_ **int**: column name(s) or index(es) | **Table** without the selected columns |
| `tbl.relabeled(old_label, new_label)` |	Creates a new table, changing the column name specified by the old label to the new label, and leaves the original table unchanged. (Ch 6) | 1. **string**: the old column name <br> 2. **string**: the new column name | **Table**: a new Table |
| `tbl.show(n)` | Display n rows of a table. If no argument is specified, defaults to displaying the entire table. (Ch 6.1)

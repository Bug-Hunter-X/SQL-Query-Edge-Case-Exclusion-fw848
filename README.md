# SQL Query Edge Case Exclusion

This repository demonstrates a common SQL query error where an edge case is unintentionally excluded.

The `bug.sql` file contains a query that selects employees from the 'Sales' department with a salary greater than 100000.  However, this query does not include employees with a salary exactly equal to 100000.

The `bugSolution.sql` file provides a corrected query that addresses this issue.
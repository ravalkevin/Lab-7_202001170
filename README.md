# Lab-7_202001170

# **Section A**

## **equivalence classes:** <br>

1. Valid dates: such as (3, 4, 1995).
2. Invalid dates: such as (31, 2, 2022) or (29, 2, 1900).
3. Out of range dates: such as (0, 5, 2010) or (15, 13, 2005).
Based on these equivalence classes, we can design the following test cases:

**Input Data and Expected Outcome**<br>

**Valid dates:**<br>
| Current date     | Previous date     |
| ------------- | :---: |
| 15, 10, 2022 | 14, 10, 2022 |
| 1, 1, 2015 | 31, 12, 2014 |
| 31, 3, 2000 | 30, 3, 2000|

**Invalid dates:**<br>

| Current date |
| ------------- |
| 31, 4, 2010 |
| 29, 2, 2022 |
| 30, 2, 2000 |

**Out of range dates:**<br>

| Current date |
| ------------- |
| 0, 5, 2009|
| 15, 13, 2005 |
| 31, 6, 1899 |
| 31, 12, 2018 |


# Course 1: Data Analysis & Visualization with Excel, Power BI & SQL

## Course Description

This comprehensive course is designed for aspiring data analysts, business intelligence professionals, and anyone looking to harness the power of data. We will journey through the essential tools and techniques for collecting, cleaning, analyzing, and visualizing data. Starting with the versatile capabilities of Microsoft Excel for data manipulation and basic visualization, we then move to Microsoft Power BI for creating interactive dashboards and reports. Finally, we delve into SQL for powerful data querying and management from relational databases. By the end of this course, you will be equipped with the skills to transform raw data into actionable insights.

## Prerequisites

*   Basic computer literacy.
*   No prior experience in data analysis, Excel, Power BI, or SQL is required.
*   A willingness to learn and engage with hands-on exercises.

## Course Outline

### Module 1: Foundations of Data Analysis & Excel Fundamentals (Expanded)

This module lays the groundwork for data analysis, introducing core concepts and then diving into Microsoft Excel as a foundational tool for data handling, now expanded for greater depth and breadth.

*   **Lesson 1.1: The World of Data: An Introduction**
    *   What is Data? Defining raw facts, figures, and statistics.
    *   The Data Deluge: Understanding the exponential growth of data in various sectors (business, science, social media, etc.).
    *   Data vs. Information vs. Knowledge vs. Wisdom (DIKW Pyramid).
    *   Real-world examples of how data is generated and used daily.
    *   The impact of data on modern society and decision-making.
    *   <YouTube videoId="g_k9Hk0n0Yg" title="What is Data? by Khan Academy" />
    *   <YouTube videoId="6tB01jCjXgE" title="The Value of Data in the 21st Century by TEDx Talks" />

*   **Lesson 1.2: What is Data Analysis? Core Tenets**
    *   Defining Data Analysis: The process of inspecting, cleansing, transforming, and modeling data to discover useful information, inform conclusions, and support decision-making.
    *   Key Objectives of Data Analysis:
        *   Describing current states (Descriptive Analytics).
        *   Diagnosing reasons for past outcomes (Diagnostic Analytics).
        *   Predicting future trends (Predictive Analytics).
        *   Prescribing actions for optimal outcomes (Prescriptive Analytics).
    *   The iterative nature of data analysis.
    *   Ethical considerations in data collection and analysis (privacy, bias).
    *   <YouTube videoId="JxgmHe2NleY" title="What Is Data Analysis? - An Introduction (Full Guide) by CareerFoundry" />
    *   <YouTube videoId="djqqk5j-00A" title="Types of Data Analytics by Simplilearn" />

*   **Lesson 1.3: The Data Analysis Lifecycle/Process**
    *   A detailed walkthrough of the typical stages:
        1.  **Problem Definition/Asking the Right Questions:** Clearly defining the objective of the analysis.
        2.  **Data Collection/Acquisition:** Identifying and gathering data from various sources (databases, APIs, surveys, files).
        3.  **Data Cleaning/Preprocessing:** Handling missing values, errors, inconsistencies, and formatting issues.
        4.  **Data Exploration & Understanding (EDA):** Initial investigation to understand patterns, anomalies, and relationships.
        5.  **Data Transformation/Manipulation:** Preparing data for analysis (e.g., aggregating, filtering, creating new features).
        6.  **Data Modeling/Analysis:** Applying statistical techniques or algorithms.
        7.  **Data Interpretation & Drawing Conclusions:** Making sense of the results.
        8.  **Data Visualization & Communication:** Presenting findings effectively.
        9.  **Action/Decision Making:** Using insights to drive actions.
    *   The importance of each stage and how they interlink.
    *   <YouTube videoId="7NU_gNBp3gA" title="The Data Analysis Process by Alex The Analyst" />
    *   <YouTube videoId="p_FcbK0uPqY" title="Data Analysis Full Course for Beginners by Simplilearn" /> (Focus on process sections)

*   **Lesson 1.4: Types of Data - Understanding Your Variables**
    *   **Qualitative (Categorical) Data:** Describes qualities or characteristics.
        *   Nominal Data: Categories with no intrinsic order (e.g., colors, gender, country).
        *   Ordinal Data: Categories with a meaningful order (e.g., education level, satisfaction rating).
    *   **Quantitative (Numerical) Data:** Represents measurable quantities.
        *   Discrete Data: Countable, whole numbers (e.g., number of students, defects per hour).
        *   Continuous Data: Measurable, can take any value within a range (e.g., height, temperature, time).
            *   Interval Data: Ordered, constant scale, but no true zero (e.g., temperature in Celsius/Fahrenheit, IQ scores).
            *   Ratio Data: Ordered, constant scale, and a true zero (e.g., weight, height, age, sales figures).
    *   Importance of identifying data types for appropriate analysis and visualization.
    *   Examples of each data type in business contexts.
    *   <YouTube videoId="knszC39K09Q" title="Types of Data: Nominal, Ordinal, Interval, Ratio - Statistics Help by statisticsfun" />
    *   <YouTube videoId="dwlikR_g2fM" title="Qualitative vs Quantitative Data by DATAtab" />

*   **Lesson 1.5: Introduction to Microsoft Excel - Your First Data Tool**
    *   Why Excel is still relevant for data analysis (accessibility, widespread use, versatility for smaller datasets).
    *   Overview of Excel's capabilities for data entry, calculation, visualization, and basic analysis.
    *   Strengths and limitations of Excel for data tasks.
    *   When to consider moving beyond Excel (large datasets, complex statistical modeling, automation needs).
    *   <YouTube videoId="Vl0H-qTclOg" title="Excel Tutorial for Beginners by Teacher's Tech" /> (Recap)
    *   <YouTube videoId="xvmR9GiaS0Y" title="Why Learn Excel for Data Analysis? by Alex The Analyst" />

*   **Lesson 1.6: Navigating the Excel Interface - Ribbon, Worksheets, Cells**
    *   Detailed exploration of the Excel User Interface:
        *   The Ribbon: Tabs (File, Home, Insert, Page Layout, Formulas, Data, Review, View, Help), Groups within Tabs, Command Buttons.
        *   Quick Access Toolbar: Customization.
        *   Formula Bar: Viewing and editing cell contents and formulas.
        *   Name Box: Displaying cell address or named ranges.
        *   Worksheet Area: Grid of rows and columns.
        *   Sheet Tabs: Managing multiple worksheets within a workbook.
        *   Status Bar: Information like Sum, Average, Count of selected cells.
    *   Understanding Workbooks (.xlsx, .xls, .csv) vs. Worksheets.
    *   Rows (numbered), Columns (lettered), and Cells (intersection, e.g., A1).
    *   Selecting cells, ranges, rows, and columns.
    *   <YouTube videoId="rWpW2hOCldI" title="Microsoft Excel Tutorial - Beginners Level 1 by Teacher's Tech" /> (Focus on interface tour)

*   **Lesson 1.7: Efficient Data Entry and Management in Excel**
    *   Best practices for manual data entry: consistency, avoiding merged cells for data, one data point per cell.
    *   Entering different data types: Text, Numbers, Dates, Times, Percentages.
    *   Using AutoFill and Flash Fill for speeding up data entry.
        *   **AutoFill Example:** Typing "Jan" then dragging the fill handle to get "Feb", "Mar", etc.
        *   **Flash Fill Example:** If you have "John Smith" in A1 and type "John" in B1, then "Jane Doe" in A2, starting to type "Jane" in B2 might trigger Flash Fill to extract first names.
    *   Editing cell contents (F2 key, formula bar).
    *   Inserting, Deleting, Hiding, and Unhiding Rows and Columns.
    *   Adjusting Column Width and Row Height (AutoFit).
    *   Freezing Panes for navigating large datasets.
    *   Splitting screen to view different parts of a worksheet.
    *   <YouTube videoId="2KEEZ3g0YkE" title="Excel Data Entry Tips and Tricks by Leila Gharani" />
    *   <YouTube videoId="O0KymgI87gY" title="Excel Flash Fill and AutoFill by Microsoft Excel" />

*   **Lesson 1.8: Cell Formatting for Clarity and Presentation**
    *   Importance of formatting for readability and professionalism.
    *   **Number Formatting:** General, Number, Currency, Accounting, Date, Time, Percentage, Fraction, Scientific, Text.
        *   Custom Number Formats.
        *   **Example:** Formatting 0.25 as "25%". Formatting 45320 as "$45,320.00".
    *   **Font Formatting:** Font type, size, color, bold, italics, underline.
    *   **Alignment Formatting:** Horizontal (left, center, right, justify), Vertical (top, middle, bottom), Wrap Text, Merge & Center (use with caution for data, good for titles).
    *   **Borders and Fill:** Adding cell borders, background colors for emphasis.
    *   Using the Format Painter to quickly copy formatting.
    *   Conditional Formatting (Introduction - deeper dive later).
    *   <YouTube videoId="5cNBTA4qNEM" title="Excel Formatting Tips to Make Your Spreadsheets Look Professional by Leila Gharani" />

*   **Lesson 1.9: Introduction to Excel Tables for Structured Data**
    *   What is an Excel Table? (Previously known as "Lists").
    *   Converting a range of data into an Excel Table (Insert > Table or Ctrl+T).
    *   Benefits of using Excel Tables:
        *   Structured references (e.g., `Table1[SalesAmount]`).
        *   Automatic expansion for new rows/columns.
        *   Built-in filtering and sorting controls.
        *   Banded rows/columns for readability.
        *   Calculated columns with automatic formula fill-down.
        *   Easy creation of slicers (covered later).
        *   Total Row feature for quick summaries (Sum, Average, Count, etc.).
    *   Table Design options and styles.
    *   <YouTube videoId="0vL03-vY8Z4" title="Excel Tables Tutorial - A Beginner's Guide by Technology for Teachers and Students" />
    *   <YouTube videoId="pkY2mnk6nL8" title="10 Benefits of Using Excel Tables by Excel Campus - Jon Acampora" />

*   **Lesson 1.10: Writing Your First Excel Formulas - Syntax and Operators**
    *   What is a Formula? An expression that calculates a value in a cell.
    *   All formulas begin with an equals sign (`=`).
    *   Excel Operators:
        *   Arithmetic Operators: `+` (Addition), `-` (Subtraction), `*` (Multiplication), `/` (Division), `^` (Exponentiation), `%` (Percentage - often used with multiplication).
        *   Comparison Operators: `=` (Equal to), `>` (Greater than), `<` (Less than), `>=` (Greater than or equal to), `<=` (Less than or equal to), `<>` (Not equal to).
        *   Text Concatenation Operator: `&` (joins strings).
        *   Reference Operators: `:` (Range, e.g., `A1:A10`), `,` (Union, combines multiple ranges), ` ` (Space - Intersection, rarely used by beginners).
    *   Order of Operations (PEMDAS/BODMAS): Parentheses, Exponents, Multiplication/Division, Addition/Subtraction.
    *   **Example:** `= (A1 + B1) * C1 / 2`
    *   Entering and editing formulas in the formula bar.
    *   <YouTube videoId="pvM0KjRoO0k" title="Excel Formulas for Beginners - Basic Operators and Order of Operations by Simon Sez IT" />

*   **Lesson 1.11: Understanding Cell References - Relative, Absolute, and Mixed**
    *   **Relative References (e.g., `A1`):** Adjust automatically when a formula is copied to other cells. Default behavior.
        *   **Example:** If `=A1+B1` in C1 is copied to C2, it becomes `=A2+B2`.
    *   **Absolute References (e.g., `$A$1`):** Remain constant no matter where the formula is copied. Use `$` before column letter and row number. (F4 key shortcut to toggle).
        *   **Example:** If `=A1*$B$1` (where B1 is a fixed tax rate) is copied down, B1 will always refer to cell B1.
    *   **Mixed References (e.g., `A$1` or `$A1`):** Either the row or the column is fixed, while the other part is relative.
        *   `A$1`: Column is relative, row is absolute.
        *   `$A1`: Column is absolute, row is relative.
        *   **Example:** Creating a multiplication table where row headers and column headers are fixed in parts of the formula.
    *   Practical examples demonstrating the use of each type.
    *   <YouTube videoId="NmVMj9n733E" title="Excel Cell References Explained: Relative, Absolute & Mixed by Leila Gharani" />

*   **Lesson 1.12: Essential Excel Functions - SUM, AVERAGE, COUNT, MAX, MIN**
    *   What is a Function? Predefined formulas that perform specific calculations.
    *   Function Syntax: `FUNCTIONNAME(argument1, argument2, ...)`
    *   **`SUM()`:** Adds all numbers in a range of cells.
        *   **Example:** `=SUM(A1:A10)` adds values in cells A1 through A10.
        *   **Example:** `=SUM(A1, B5, C3:C7)` adds specific cells and a range.
    *   **`AVERAGE()`:** Calculates the arithmetic mean of numbers in a range.
        *   **Example:** `=AVERAGE(B1:B20)` finds the average of values in B1 to B20.
    *   **`COUNT()`:** Counts the number of cells in a range that contain numbers.
        *   **Example:** `=COUNT(C1:C100)` counts how many cells in C1 to C100 have numeric data.
    *   **`COUNTA()`:** Counts the number of non-empty cells in a range (includes text, numbers, errors).
        *   **Example:** `=COUNTA(D1:D50)` counts all cells in D1 to D50 that are not blank.
    *   **`MAX()`:** Returns the largest value in a set of values.
        *   **Example:** `=MAX(E1:E30)` finds the highest value in E1 to E30.
    *   **`MIN()`:** Returns the smallest value in a set of values.
        *   **Example:** `=MIN(F1:F40)` finds the lowest value in F1 to F40.
    *   Using the Insert Function dialog box and AutoSum feature.
    *   <YouTube videoId="2k96y9n04k0" title="Excel Formulas and Functions Tutorial by Simplilearn" /> (Recap and expansion)
    *   <YouTube videoId="RvjBo2z938U" title="Excel Basic Functions - SUM, AVERAGE, MAX, MIN, COUNT by Technology for Teachers and Students" />

*   **Lesson 1.13: Basic Data Sorting Techniques in Excel**
    *   Importance of sorting for organizing and analyzing data.
    *   Single-Level Sorting:
        *   Sort A to Z / Smallest to Largest.
        *   Sort Z to A / Largest to Smallest.
        *   Sorting by Text, Numbers, Dates.
    *   Using the Sort buttons on the Data tab.
    *   Custom Sort (Multi-Level Sorting): Sorting by multiple columns in a specific order.
        *   **Example:** Sorting sales data first by 'Region' (A-Z) and then by 'Sales Amount' (Largest to Smallest) within each region.
    *   Sorting by Cell Color, Font Color, or Cell Icons (used with Conditional Formatting).
    *   Potential pitfalls: Sorting only a selection and not the entire related data.
    *   <YouTube videoId="jxvR-_wzN0Y" title="How to Sort Data in Excel - Simple & Multi-Level Sorting by Excel Easy" />

*   **Lesson 1.14: Basic Data Filtering with AutoFilter in Excel**
    *   Purpose of filtering: Displaying only the rows that meet specific criteria, hiding others.
    *   Enabling AutoFilter (Data tab > Filter, or from an Excel Table).
    *   Filtering by specific values in a column (checkboxes).
    *   Text Filters (Equals, Does Not Equal, Begins With, Ends With, Contains, etc.).
    *   Number Filters (Equals, Greater Than, Less Than, Between, Top 10, Above/Below Average, etc.).
    *   Date Filters (Specific dates, Before, After, Between, This Week, Next Month, Year-to-Date, etc.).
    *   Filtering by Cell Color or Font Color.
    *   Clearing filters from a column or all columns.
    *   Difference between sorting and filtering.
    *   <YouTube videoId="PcvYQ3iN0xM" title="How to Use Filters in Excel - A Beginner's Guide by Excel Campus - Jon Acampora" />

*   **Lesson 1.15: Introduction to Basic Excel Charts for Visualization**
    *   Why visualize data? To identify trends, patterns, and outliers more easily than looking at raw numbers.
    *   Selecting data for a chart.
    *   Creating common chart types using the Insert tab:
        *   **Column Charts:** Comparing values across categories.
        *   **Bar Charts:** Similar to column charts, but horizontal (good for long category names).
        *   **Line Charts:** Showing trends over time or continuous data.
        *   **Pie Charts:** Showing proportions of a whole (use with caution, best for few categories).
    *   Understanding basic Chart Elements: Chart Title, Axis Titles, Data Labels, Legend, Gridlines.
    *   Moving and resizing charts.
    *   Switching Row/Column data.
    *   Very basic chart formatting (changing colors, styles - deeper dive later).
    *   <YouTube videoId="K_7D3hdOP3E" title="Introduction to Excel Charts and Graphs by Technology for Teachers and Students" /> (Recap and expansion)
    *   <YouTube videoId="0yLTwA1a4p4" title="Creating Basic Charts in Excel 2019 by Simon Sez IT" />

---
### Module 2: Advanced Excel for Data Analysis (Expanded)

This module explores more sophisticated Excel features for data cleaning, manipulation, and deeper analysis, expanded to cover more ground.

*   **Lesson 2.1: Advanced Data Cleaning: TRIM, CLEAN, and Handling Duplicates**
    *   Recap: Importance of clean data for accurate analysis.
    *   `TRIM()`: Removing leading/trailing and extra internal spaces from text.
        *   **Example:** `TRIM("  Product A  ")` results in `"Product A"`.
    *   `CLEAN()`: Removing non-printable characters from text (often from imported data).
    *   Finding and Removing Duplicate Rows:
        *   Using the built-in "Remove Duplicates" feature (Data tab).
        *   Understanding how it identifies duplicates (based on selected columns).
        *   Creating a unique list using advanced filters or formulas (e.g., `UNIQUE()` function in newer Excel).
    *   Strategies for handling duplicates (remove, flag, investigate).
    *   <YouTube videoId="cagD79yCRkU" title="Excel Data Cleaning - Full Tutorial by Simplilearn" /> (Focus on TRIM, CLEAN, Duplicates)
    *   <YouTube videoId="AKkNB-y-c78" title="How to Remove Duplicates in Excel by Excel Easy" />

*   **Lesson 2.2: Text Manipulation Functions - LEFT, RIGHT, MID, LEN, FIND, SEARCH**
    *   `LEN()`: Returns the number of characters in a text string.
        *   **Example:** `LEN("Excel")` returns 5.
    *   `LEFT()`: Extracts a specified number of characters from the beginning of a text string.
        *   **Syntax:** `LEFT(text, num_chars)`
        *   **Example:** `LEFT("ProductID-123", 9)` returns "ProductID".
    *   `RIGHT()`: Extracts a specified number of characters from the end of a text string.
        *   **Syntax:** `RIGHT(text, num_chars)`
        *   **Example:** `RIGHT("ProductID-123", 3)` returns "123".
    *   `MID()`: Extracts a substring from the middle of a text string, given a starting position and length.
        *   **Syntax:** `MID(text, start_num, num_chars)`
        *   **Example:** `MID("Data-Analysis-Course", 6, 8)` returns "Analysis".
    *   `FIND()`: Locates one text string within another (case-sensitive) and returns its starting position.
        *   **Syntax:** `FIND(find_text, within_text, [start_num])`
        *   **Example:** `FIND("-", "Data-Analysis")` returns 5.
    *   `SEARCH()`: Similar to `FIND` but case-insensitive. Supports wildcards (`*`, `?`).
    *   Combining these functions to extract complex patterns.
        *   **Example:** Extracting the first name from "Smith, John" using `LEFT`, `FIND`.
    *   <YouTube videoId="3Yl4jC5rZhY" title="Excel Text Functions: LEFT, RIGHT, MID, LEN, FIND, SEARCH by Leila Gharani" />

*   **Lesson 2.3: Text Manipulation Functions - REPLACE, SUBSTITUTE, CONCATENATE, TEXTJOIN**
    *   `REPLACE()`: Replaces part of a text string, based on position, with a different text string.
        *   **Syntax:** `REPLACE(old_text, start_num, num_chars, new_text)`
        *   **Example:** `REPLACE("Excel 2019", 7, 4, "365")` returns "Excel 365".
    *   `SUBSTITUTE()`: Replaces specific text in a text string with new text (can replace all occurrences or a specific instance).
        *   **Syntax:** `SUBSTITUTE(text, old_text, new_text, [instance_num])`
        *   **Example:** `SUBSTITUTE("Sales Report-Jan", "-", " ")` returns "Sales Report Jan".
    *   `CONCATENATE()` or `&` operator: Joins several text strings into one string.
        *   **Example:** `CONCATENATE(A1, " ", B1)` or `A1 & " " & B1` to combine first and last names.
    *   `TEXTJOIN()` (Newer Excel): Joins text from multiple ranges and/or strings, with a specified delimiter and option to ignore empty cells.
        *   **Syntax:** `TEXTJOIN(delimiter, ignore_empty, text1, [text2], ...)`
        *   **Example:** `TEXTJOIN(", ", TRUE, A1:A3)` joins text in A1, A2, A3 with a comma and space, ignoring blanks.
    *   Practical data cleaning examples using these functions.
    *   <YouTube videoId="QUohYyHVIQ" title="Excel REPLACE vs SUBSTITUTE Functions by Leila Gharani" />
    *   <YouTube videoId="fGsFEv99jBU" title="Excel CONCATENATE, CONCAT, TEXTJOIN Functions by Technology for Teachers and Students" />

*   **Lesson 2.4: Data Type Conversion and Error Checking Functions**
    *   `VALUE()`: Converts a text string that represents a number into an actual number.
        *   **Example:** If A1 contains text "123", `=VALUE(A1)` returns the number 123.
    *   `TEXT()`: Converts a value to text in a specific number format.
        *   **Syntax:** `TEXT(value, format_text)`
        *   **Example:** `TEXT(TODAY(), "MMMM DD, YYYY")` returns current date as "October 26, 2023".
    *   `DATEVALUE()`: Converts a date stored as text to a serial number that Excel recognizes as a date.
    *   Error Checking Functions:
        *   `ISBLANK()`: Checks if a cell is empty. Returns TRUE or FALSE.
        *   `ISNUMBER()`: Checks if a value is a number.
        *   `ISTEXT()`: Checks if a value is text.
        *   `ISLOGICAL()`: Checks if a value is a logical value (TRUE/FALSE).
        *   `ISERROR()`: Checks if a cell contains any error value (e.g., #N/A, #VALUE!, #DIV/0!).
        *   `ISNA()`: Checks specifically for the #N/A error.
        *   `IFERROR()`: Returns a value you specify if a formula evaluates to an error; otherwise, returns the result of the formula.
            *   **Syntax:** `IFERROR(value, value_if_error)`
            *   **Example:** `IFERROR(A1/B1, "Cannot divide by zero")`
    *   <YouTube videoId="jGgYiL_4qzk" title="Excel Data Type Conversion & Error Handling Functions (VALUE, TEXT, IS Functions, IFERROR) by ExcelIsFun" />

*   **Lesson 2.5: Logical Functions - IF, AND, OR, NOT (Deep Dive)**
    *   Recap `IF()`: `IF(logical_test, value_if_true, value_if_false)`
    *   Nested `IF()` statements for multiple conditions (up to 64 levels, but becomes complex).
        *   **Example:** `IF(A1>90, "A", IF(A1>80, "B", IF(A1>70, "C", "D")))`
    *   `AND(logical1, [logical2], ...)`: Returns TRUE if all arguments are TRUE.
        *   **Example:** `IF(AND(A1="Shipped", B1>100), "Eligible for Bonus", "Not Eligible")`
    *   `OR(logical1, [logical2], ...)`: Returns TRUE if any argument is TRUE.
        *   **Example:** `IF(OR(C1="USA", C1="Canada"), "North America", "Other")`
    *   `NOT(logical)`: Reverses the logical value of its argument.
        *   **Example:** `IF(NOT(ISBLANK(D1)), "Data Present", "Data Missing")`
    *   Combining logical functions for complex criteria.
    *   Alternative to deeply nested IFs: `IFS()` function (newer Excel).
    *   <YouTube videoId="3u5N0L1n_yM" title="Excel IF Formula: Simple to Advanced (multiple criteria, nested IF, AND, OR functions) by Leila Gharani" /> (Recap and expansion)

*   **Lesson 2.6: Conditional Aggregation - SUMIF(S), COUNTIF(S), AVERAGEIF(S)**
    *   `SUMIF(range, criteria, [sum_range])`: Sums cells that meet a given criteria.
        *   **Example:** `SUMIF(A1:A10, ">50", B1:B10)` sums values in B1:B10 where corresponding A1:A10 is >50.
    *   `COUNTIF(range, criteria)`: Counts cells that meet a given criteria.
        *   **Example:** `COUNTIF(C1:C100, "Completed")`
    *   `AVERAGEIF(range, criteria, [average_range])`: Averages cells that meet a given criteria.
    *   `SUMIFS(sum_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)`: Sums cells based on multiple criteria.
    *   `COUNTIFS(criteria_range1, criteria1, [criteria_range2, criteria2], ...)`: Counts cells based on multiple criteria.
        *   **Example:** `COUNTIFS(A1:A10, "Fruits", B1:B10, ">100")` counts items that are "Fruits" AND have sales >100.
    *   `AVERAGEIFS(average_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)`: Averages cells based on multiple criteria.
    *   Using wildcards (`*`, `?`) in criteria.
    *   <YouTube videoId="1hsj2fMwF9o" title="Excel SUMIF, COUNTIF, AVERAGEIF, SUMIFS, COUNTIFS, AVERAGEIFS Functions by ExcelIsFun" />

*   **Lesson 2.7: Lookup Functions - VLOOKUP Deep Dive (Limitations and Best Practices)**
    *   Recap `VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])`.
    *   Understanding `range_lookup`:
        *   `TRUE` or omitted: Approximate match (table_array must be sorted by the first column).
        *   `FALSE`: Exact match. (Almost always use FALSE for data lookups).
    *   Common VLOOKUP Errors:
        *   `#N/A`: Lookup value not found (or data type mismatch).
        *   `#REF!`: Invalid `col_index_num` or `table_array`.
        *   `#VALUE!`: Incorrect arguments.
    *   Limitations of VLOOKUP:
        *   Only looks to the right.
        *   `col_index_num` is static (breaks if columns are inserted/deleted).
        *   Can be slow on large datasets.
    *   Best Practices: Use with Excel Tables, error handling with `IFERROR()`.
    *   Alternative: `HLOOKUP()` for horizontal lookups (less common).
    *   <YouTube videoId="E7gQ-PgYkMc" title="Excel VLOOKUP For Beginners (and common errors) by Technology for Teachers and Students" /> (Focus on deep dive and errors)

*   **Lesson 2.8: Advanced Lookups - INDEX and MATCH Functions**
    *   Why INDEX and MATCH are often preferred over VLOOKUP.
    *   `MATCH(lookup_value, lookup_array, [match_type])`: Returns the relative position of an item in an array.
        *   `match_type`: 0 for exact match, 1 for less than, -1 for greater than.
    *   `INDEX(array, row_num, [column_num])`: Returns a value or reference of the cell at the intersection of a particular row and column, in a given range.
    *   Combining INDEX and MATCH: `INDEX(return_range, MATCH(lookup_value, lookup_column, 0))`
        *   Benefits: Can look left, more robust to column changes, generally faster.
    *   Two-way lookups (INDEX with two MATCH functions).
    *   <YouTube videoId="F264FpNBODE" title="Excel INDEX MATCH (the right way) by Leila Gharani" />

*   **Lesson 2.9: The XLOOKUP Function (Modern Excel)**
    *   `XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode])`
    *   Benefits over VLOOKUP/INDEX-MATCH:
        *   Simpler syntax.
        *   Defaults to exact match.
        *   Can look left or right without changing formula.
        *   Built-in `if_not_found` argument.
        *   Can return multiple columns/rows.
        *   Search modes (first-to-last, last-to-first).
    *   Practical examples demonstrating its versatility.
    *   Availability: Microsoft 365 and newer Excel versions.
    *   <YouTube videoId="4h0IdyqHkIA" title="XLOOKUP Excel Function - Better than VLOOKUP & HLOOKUP by Leila Gharani" />

*   **Lesson 2.10: Data Validation for Controlled Input**
    *   Purpose: Restrict the type of data or the values that users can enter into a cell.
    *   Setting up Data Validation rules (Data tab > Data Validation):
        *   Allow: Whole Number, Decimal, List, Date, Time, Text Length, Custom (using a formula).
        *   Input Message: Guidance for the user before they enter data.
        *   Error Alert: Warning, Stop, or Information message if invalid data is entered.
    *   Creating dropdown lists using Data Validation (Allow > List).
    *   **Example:** Restricting a cell to only accept dates within a specific range. Restricting product category input to a predefined list.
    *   Using formulas for custom validation rules.
    *   Circle Invalid Data feature.
    *   <YouTube videoId="RA009uA40gU" title="Excel Data Validation - Comprehensive Tutorial by Excel Campus - Jon Acampora" />

*   **Lesson 2.11: Advanced Conditional Formatting**
    *   Recap: Basic conditional formatting.
    *   Using formulas to determine which cells to format.
        *   **Example:** Highlighting entire rows where 'Sales' > 1000. Formula: `=$C2>1000` (applied to range A2:E100, assuming Sales is in column C).
    *   Highlighting cells based on comparison with other cells.
    *   Data Bars, Color Scales, and Icon Sets in more detail.
    *   Managing rules (order of precedence, stop if true).
    *   Using Conditional Formatting for dashboards and visual analysis.
    *   <YouTube videoId="W_vG6y-vN1c" title="Advanced Conditional Formatting in Excel (Using Formulas) by Leila Gharani" />

*   **Lesson 2.12: What-If Analysis Tools - Goal Seek and Scenario Manager**
    *   **Goal Seek:** Finds the input value needed to achieve a specific goal for a formula.
        *   **Example:** If you want a final grade of 85, and you know your current grades and the weighting of the final exam, Goal Seek can tell you what score you need on the final exam.
        *   Setup: Set cell (formula cell), To value (target goal), By changing cell (input cell).
    *   **Scenario Manager:** Creates and compares different sets of input values (scenarios) to see how they affect formula results.
        *   **Example:** Comparing profit outcomes for "Best Case," "Worst Case," and "Most Likely Case" sales scenarios by changing variables like units sold, price, and costs.
        *   Creating scenarios, showing scenarios, generating summary reports.
    *   <YouTube videoId="Sopb2hN1P9c" title="Excel What-If Analysis: How to Use Goal Seek, Scenario Manager & Data Tables by Simon Sez IT" /> (Focus on Goal Seek & Scenario Manager)

*   **Lesson 2.13: What-If Analysis Tools - Data Tables**
    *   **Data Tables (One-Variable):** Shows how changing one input variable in a formula affects the results.
        *   Structure: Input values in a column (or row), formula referencing the input cell at the top (or side).
        *   **Example:** Seeing how different interest rates affect a monthly loan payment.
    *   **Data Tables (Two-Variable):** Shows how changing two input variables in a formula affects the results.
        *   Structure: Input values for one variable in a column, input values for the other in a row, formula in the top-left corner cell.
        *   **Example:** A table showing how different interest rates AND loan terms affect monthly mortgage payments.
    *   Using the Data Table feature (Data tab > What-If Analysis > Data Table).
    *   <YouTube videoId="yH3iUKB4R5k" title="Excel Data Tables for What-If Analysis (One and Two Variable) by Excel Campus - Jon Acampora" />

*   **Lesson 2.14: Introduction to Power Query (Get & Transform Data) in Excel**
    *   What is Power Query? A data connection and transformation tool built into Excel (and Power BI).
    *   Its role in the ETL (Extract, Transform, Load) process.
    *   Accessing Power Query Editor (Data tab > Get Data).
    *   Importing Data from Various Sources:
        *   From Excel Workbooks (current or external).
        *   From Text/CSV files.
        *   From Web (e.g., HTML tables).
        *   From Databases (brief mention, more later).
    *   The Power Query Editor Interface: Ribbon, Queries Pane, Data Preview, Applied Steps.
    *   Basic Transformations (UI-driven): Removing Columns/Rows, Changing Data Types, Filtering, Sorting, Splitting Columns.
    *   Understanding "Applied Steps" and the query refresh process.
    *   Loading transformed data back to an Excel Table or PivotTable.
    *   <YouTube videoId="L4x_gH4x5jI" title="Introduction to Power Query in Excel by ExcelIsFun" /> (Recap and expansion)
    *   <YouTube videoId="wzId9T6v00A" title="Excel Power Query for Beginners by Leila Gharani" />

*   **Lesson 2.15: Introduction to PivotTables for Data Summarization**
    *   What is a PivotTable? An interactive way to quickly summarize, analyze, explore, and present large amounts of data.
    *   Creating PivotTables from a data range or an Excel Table.
    *   Understanding the PivotTable Fields Pane:
        *   Filters Area
        *   Columns Area
        *   Rows Area
        *   Values Area (for calculations like Sum, Count, Average).
    *   Arranging fields to create different summary views.
    *   Summarizing data by different functions (Sum, Count, Average, Max, Min, etc.).
    *   Changing value field settings (Show Values As % of Grand Total, % of Column Total, etc.).
    *   Refreshing PivotTable data when the source data changes.
    *   Basic formatting of PivotTables.
    *   <YouTube videoId="3nbvDem_C08" title="Excel Pivot Tables EXPLAINED in 10 Minutes (Productivity tips included!) by Leila Gharani" /> (Recap and expansion)
    *   <YouTube videoId="quj4n-ySY3A" title="Excel Pivot Tables for Beginners - Full Tutorial by Technology for Teachers and Students" />

---
### Module 3: Introduction to Power BI for Data Visualization (Expanded)

This module introduces Microsoft Power BI, a powerful business analytics service for creating interactive visualizations and business intelligence dashboards, now with more detailed lessons.

*   **Lesson 3.1: The Rise of Business Intelligence and Self-Service BI**
    *   Defining Business Intelligence (BI): Technologies, applications, and practices for the collection, integration, analysis, and presentation of business information.
    *   Evolution of BI: From static IT-led reports to dynamic, interactive dashboards.
    *   What is Self-Service BI? Enabling end-users (business users) to access and analyze data themselves, without requiring deep IT involvement.
    *   Benefits of Self-Service BI: Faster insights, data democratization, increased agility.
    *   Role of tools like Power BI in the Self-Service BI landscape.
    *   <YouTube videoId="P2uBKfUCRQY" title="What is Business Intelligence? BI Explained by Simplilearn" />
    *   <YouTube videoId="2Y0h4kRkcqI" title="Self-Service BI: What it is and Why it Matters by Tableau" /> (Tableau focused, but concepts are general)

*   **Lesson 3.2: What is Power BI? Ecosystem Overview**
    *   Recap: Power BI as a suite of business analytics tools.
    *   Key Components of the Power BI Ecosystem:
        *   **Power BI Desktop:** Free Windows application for data connection, transformation, modeling, and report creation. (Primary focus for development).
        *   **Power BI Service (app.powerbi.com):** Cloud-based service for publishing, sharing, and managing reports and dashboards. Collaboration features.
        *   **Power BI Mobile Apps:** Native apps for iOS, Android, and Windows to view reports and dashboards on the go.
        *   **Power BI Report Server:** On-premises solution for organizations that need to keep reports within their firewall.
        *   **Power BI Embedded:** APIs for embedding Power BI visuals and reports into custom applications.
    *   How these components work together in a typical BI workflow.
    *   Licensing: Power BI Free, Pro, Premium Per User (PPU), Premium Per Capacity.
    *   <YouTube videoId="APvMr0t1S0A" title="What is Power BI? | Introduction to Microsoft Power BI by Simplilearn" /> (Recap)
    *   <YouTube videoId="mNAwQ-s2O94" title="Power BI Full Course - Learn Power BI in 4 Hours by Edureka" /> (Focus on ecosystem overview sections)

*   **Lesson 3.3: Installing and Navigating Power BI Desktop**
    *   System requirements for Power BI Desktop.
    *   Downloading and installing Power BI Desktop (from Microsoft Store or web).
    *   First look at the Power BI Desktop interface:
        *   Ribbon (Home, Insert, Modeling, View, Help tabs).
        *   Report View (Canvas for creating visuals).
        *   Data View (For inspecting and managing data tables).
        *   Model View (For creating relationships between tables).
        *   Fields Pane (Lists available tables and columns).
        *   Visualizations Pane (For selecting and configuring visuals).
        *   Filters Pane (For applying filters at different levels).
    *   Understanding the main workflow areas within Power BI Desktop.
    *   <YouTube videoId="3LqhJyl3mXw" title="Install Power BI Desktop & First Look at the Interface by Pragmatic Works" />

*   **Lesson 3.4: Connecting to Data Sources - Excel Workbooks & CSV Files**
    *   The "Get Data" experience in Power BI Desktop.
    *   Connecting to Excel Workbooks:
        *   Selecting specific sheets or Excel Tables within the workbook.
        *   Navigator window options (Load vs. Transform Data).
    *   Connecting to CSV (Comma Separated Values) and Text Files:
        *   Specifying delimiters, file origin, data type detection.
    *   Understanding the difference between importing data vs. DirectQuery (covered later).
    *   Previewing data before loading.
    *   **Example:** Connecting to a sample sales Excel file and a product list CSV.
    *   <YouTube videoId="gtQWX1gNBG4" title="Power BI - How to Get Data from Different Sources by BI Gorilla" /> (Focus on Excel & CSV)
    *   <YouTube videoId="UrrEzq5kht8" title="Getting Data from Excel into Power BI by Curbal" />

*   **Lesson 3.5: Connecting to Data Sources - Web Content & Other Common Sources**
    *   Getting Data from Web:
        *   Connecting to web pages that contain HTML tables.
        *   Power BI's table suggestion feature.
        *   **Example:** Extracting a table of country populations from a Wikipedia page.
    *   Brief overview of connecting to other common sources:
        *   Folders (to combine multiple files).
        *   SQL Server Databases (more detail in SQL module).
        *   OData Feeds.
        *   SharePoint Folders/Lists.
    *   Understanding data source settings and permissions.
    *   <YouTube videoId="e9G3R099u7k" title="Power BI Get Data from Web Tutorial by Learnit Training" />
    *   <YouTube videoId="rZxShLv03hA" title="Power BI Get Data from Folder (Multiple Excel or CSV Files) by ExcelFort" />

*   **Lesson 3.6: Introduction to Power Query Editor in Power BI**
    *   What is Power Query Editor? (Same engine as in Excel, but integrated into Power BI Desktop).
    *   Accessing Power Query Editor ("Transform Data" button).
    *   The Power Query Editor Interface:
        *   Ribbon with transformation tools (Home, Transform, Add Column, View tabs).
        *   Queries Pane (listing all imported data sources/queries).
        *   Data Preview Area.
        *   Applied Steps Pane (tracks all transformations).
        *   Formula Bar (for viewing/editing M code - introduction).
    *   Understanding the concept of "Queries" as data transformation workflows.
    *   <YouTube videoId="YczU7Cwwx4U" title="Power BI Power Query Tutorial for Beginners by Pragmatic Works" /> (Recap and Interface Focus)

*   **Lesson 3.7: Basic Data Cleaning in Power Query - Removing Rows/Columns, Filtering**
    *   Removing Unnecessary Columns (Choose Columns, Remove Columns).
    *   Removing Rows:
        *   Remove Top/Bottom Rows.
        *   Remove Alternate Rows.
        *   Remove Duplicates.
        *   Remove Blank Rows.
        *   Remove Errors.
    *   Filtering Rows based on criteria (similar to Excel's AutoFilter but more powerful).
        *   Text Filters, Number Filters, Date Filters.
        *   **Example:** Filtering a sales dataset to include only sales from a specific year or product category.
    *   The importance of the order of applied steps.
    *   <YouTube videoId="eN0oW24pLCo" title="Power BI Power Query - Basic Data Cleaning (Removing, Filtering) by BI Elite" />

*   **Lesson 3.8: Changing Data Types and Handling Errors in Power Query**
    *   Importance of correct data types for analysis and visualization.
    *   Common Data Types in Power Query: Text, Whole Number, Decimal Number, Date, Date/Time, True/False, etc.
    *   Changing Data Types using the UI or right-click options.
    *   Power Query's automatic data type detection (and when to override it).
    *   Identifying and Handling Data Errors:
        *   Errors appear as `[Error]` in cells.
        *   Options: Remove Errors, Replace Errors, Keep Errors (for investigation).
        *   Using "Try...Otherwise" in custom columns for more robust error handling (advanced).
    *   **Example:** Converting a "Sales Amount" column stored as text to a decimal number. Handling errors if some text values cannot be converted.
    *   <YouTube videoId="AgAYsSHeCSk" title="Power BI Data Types and Error Handling in Power Query by Curbal" />

*   **Lesson 3.9: Splitting and Merging Columns in Power Query**
    *   **Splitting Columns:**
        *   By Delimiter (e.g., splitting "First Name,Last Name" into two columns).
        *   By Number of Characters.
        *   By Positions.
        *   From Digit to Non-Digit (and vice-versa).
        *   **Example:** Splitting a 'Product Code' like "ABC-123-XYZ" into three separate columns based on the hyphen delimiter.
    *   **Merging Columns:**
        *   Combining data from multiple columns into a single new column.
        *   Option to add a separator.
        *   **Example:** Merging 'FirstName' and 'LastName' columns into a 'FullName' column.
    *   <YouTube videoId="s9k5M30Y83o" title="Split and Merge Columns in Power BI Power Query by Learnit Training" />

*   **Lesson 3.10: Replacing Values and Using Fill Down/Up in Power Query**
    *   **Replacing Values:**
        *   Finding specific text or numeric values and replacing them with others.
        *   Useful for standardizing data (e.g., replacing "USA" and "United States" with "United States of America").
        *   Advanced options (match entire cell contents, special characters).
    *   **Fill Down/Up:**
        *   Propagating the value from a non-null cell downwards (or upwards) to fill null/blank cells below (or above) it.
        *   Very useful for unstacking data or filling gaps in time series where values are carried forward.
        *   **Example:** If a report has a category name only on the first row of a group, Fill Down can populate that category for all rows in that group.
    *   <YouTube videoId="j0B9CsVlwj0" title="Power BI Power Query - Replace Values & Fill Down/Up by BI Gorilla" />

*   **Lesson 3.11: Grouping and Aggregating Data in Power Query**
    *   The "Group By" transformation.
    *   Grouping data by one or more columns.
    *   Performing aggregate calculations on the grouped data:
        *   Sum, Average, Median, Min, Max, Count Rows, Count Distinct Rows.
    *   **Example:** Grouping a sales dataset by 'Product Category' and calculating the 'Total Sales Amount' and 'Average Order Quantity' for each category.
    *   Advanced grouping options (e.g., grouping all rows).
    *   <YouTube videoId="CF0uXqlmf9Y" title="Group Data in Power BI Power Query by Curbal" />

*   **Lesson 3.12: Pivoting and Unpivoting Columns in Power Query**
    *   **Unpivoting Columns:** Transforming data from a wide format (cross-tab) to a tall/long format.
        *   Select columns to unpivot.
        *   Result: Attribute column (original column headers) and Value column.
        *   Essential for making data suitable for many Power BI visuals.
        *   **Example:** Unpivoting columns like "Jan Sales", "Feb Sales", "Mar Sales" into two columns: "Month" and "Sales".
    *   **Pivoting Columns:** Transforming data from a tall format to a wide format.
        *   Select the column whose values will become new column headers.
        *   Select the column whose values will populate the new pivoted columns.
        *   Choose an aggregation function (Sum, Average, Don't Aggregate, etc.).
    *   <YouTube videoId="upmL0tk4j0xM" title="Pivot and Unpivot Data in Power BI Power Query by Pragmatic Works" />

*   **Lesson 3.13: Creating Conditional Columns in Power Query**
    *   Adding a new column whose values are determined by one or more conditions (IF-THEN-ELSE logic).
    *   Using the Conditional Column UI:
        *   Defining clauses (If column [operator] value Then output Else If... Else...).
    *   **Example:** Creating a 'Sales Performance' column based on 'Sales Amount': "High" if >1000, "Medium" if >500, "Low" otherwise.
    *   Creating conditional columns using custom M code for more complex logic (brief introduction).
    *   <YouTube videoId="ot2nL935Rz7Q" title="Power BI Conditional Columns in Power Query by Learnit Training" />

*   **Lesson 3.14: Appending and Merging Queries in Power Query**
    *   **Appending Queries:** Stacking data from two or more tables (with similar column structures) on top of each other to create one larger table.
        *   **Example:** Appending monthly sales tables (Jan_Sales, Feb_Sales) into a single 'All_Sales' table.
    *   **Merging Queries:** Joining two tables based on one or more common columns (similar to SQL JOINs).
        *   Select left table, right table, and matching columns.
        *   Join Kinds: Left Outer, Right Outer, Full Outer, Inner, Left Anti, Right Anti.
        *   Expanding the merged table to include columns from the related table.
        *   **Example:** Merging a 'Sales' table with a 'Products' table using 'ProductID' to bring product details into the sales data.
    *   <YouTube videoId="kOh1L0h20zHg" title="Append vs Merge in Power BI Power Query by Curbal" />

*   **Lesson 3.15: Understanding M Language Basics (Power Query Formula Language)**
    *   Brief introduction to M as the language behind Power Query transformations.
    *   Viewing M code in the Formula Bar or Advanced Editor.
    *   Basic M syntax: `let ... in` expressions, steps, variables, functions.
    *   How UI actions generate M code.
    *   When you might need to edit or write simple M code (e.g., custom columns with complex logic, modifying existing steps).
    *   This is an awareness lesson, not a deep dive into M programming.
    *   <YouTube videoId="FWkZ2c45qMo" title="Introduction to M Language in Power Query for Power BI by BI Elite" />
    *   <YouTube videoId="nWhnDEENTNQ" title="Power Query M Language for Beginners by ExcelIsFun" />
---
### Module 4: Data Modeling and DAX Fundamentals in Power BI (Expanded)

This module focuses on creating robust data models and introducing Data Analysis Expressions (DAX) for creating calculations in Power BI.

*   **Lesson 4.1: Introduction to Data Modeling in Power BI**
    *   What is a Data Model? A collection of tables and the relationships defined between them.
    *   Why is Data Modeling Crucial?
        *   Ensures accurate calculations and analysis.
        *   Improves report performance.
        *   Simplifies DAX formula writing.
        *   Enables intuitive report building for end-users.
    *   The Model View in Power BI Desktop.
    *   Entities (Tables) and Attributes (Columns).
    *   <YouTube videoId="p2SN_g32L2I" title="Power BI Data Modeling - Relationships, Star Schema, & More by Curbal" /> (Recap)
    *   <YouTube videoId="AVVYq0gA0PI" title="The Importance of a Good Data Model in Power BI by Guy in a Cube" />

*   **Lesson 4.2: Understanding Tables, Columns, and Data Types in the Model**
    *   Reviewing loaded tables in the Data View and Model View.
    *   Best practices for column naming (clear, concise, no spaces if possible).
    *   Assigning appropriate Data Types and Formatting for columns in the Model View (e.g., Currency, Percentage, Date).
    *   Setting Default Summarization for numeric columns (Sum, Average, Don't Summarize, etc.).
    *   Creating Hierarchies (e.g., Date Hierarchy: Year > Quarter > Month > Day).
    *   Hiding columns from Report View if they are not needed for direct visualization (e.g., key columns used only for relationships).
    *   <YouTube videoId="YapyOhn0g80" title="Power BI Data Modeling Best Practices - Tables & Columns by Pragmatic Works" />

*   **Lesson 4.3: Fact Tables vs. Dimension Tables (Star Schema Basics)**
    *   **Dimension Tables:** Describe business entities (the "who, what, where, when, why").
        *   Contain descriptive attributes (e.g., Product Name, Customer City, Date).
        *   Typically have fewer rows, wider tables.
        *   Primary keys (unique identifiers for each dimension record).
        *   Examples: Products Table, Customers Table, Dates Table, Geography Table.
    *   **Fact Tables:** Contain measurable facts or events (the "how much, how many").
        *   Contain numeric measures and foreign keys that link to dimension tables.
        *   Typically have many rows, narrower tables.
        *   Examples: Sales Transactions Table, Order Details Table, Web Page Views Table.
    *   **Star Schema:** A common data modeling approach where a central fact table is surrounded by dimension tables (looks like a star).
        *   Benefits: Simplicity, query performance, ease of understanding.
    *   Snowflake Schema (brief introduction - normalized dimension tables).
    *   <YouTube videoId="tEJU4B0Y0Co" title="Power BI Star Schema Explained by Enterprise DNA" />
    *   <YouTube videoId="1Kjhr302QkI" title="Fact Tables and Dimension Tables in Power BI by BI Elite" />

*   **Lesson 4.4: Creating Relationships Between Tables in Power BI**
    *   Why create relationships? To filter and aggregate data across multiple tables.
    *   Creating relationships in the Model View (drag-and-drop or "Manage Relationships" dialog).
    *   Understanding Cardinality:
        *   One-to-Many (1:\*): Most common (e.g., One Product can have Many Sales).
        *   Many-to-One (\*:1): Reverse of one-to-many.
        *   One-to-One (1:1): Less common, often indicates tables could be merged.
        *   Many-to-Many (\*:\*): Requires careful consideration, often resolved with a bridge table. Power BI supports direct many-to-many relationships but use with caution.
    *   Cross-Filter Direction: Single vs. Both.
        *   Understanding how filters propagate through relationships.
    *   Active vs. Inactive Relationships (and using `USERELATIONSHIP` DAX function).
    *   **Example:** Creating a 1:* relationship between 'Products'[ProductID] (one side) and 'Sales'[ProductID] (many side).
    *   <YouTube videoId="9Y7P4Y0gT0A" title="Power BI Relationships - Cardinality & Cross Filter Direction by Pragmatic Works" />

*   **Lesson 4.5: Best Practices for Data Modeling in Power BI**
    *   Strive for a Star Schema where possible.
    *   Use numeric surrogate keys for dimension tables if available.
    *   Avoid bidirectional relationships unless absolutely necessary (can cause ambiguity and performance issues).
    *   Hide foreign key columns in fact tables from the Report View (use related dimension columns instead).
    *   Create a dedicated Date Table (very important for time intelligence).
    *   Optimize column data types (e.g., use Whole Number instead of Decimal if no decimals are needed).
    *   Reduce cardinality of columns where possible.
    *   Keep the model as simple as possible while meeting requirements.
    *   <YouTube videoId="JkfpR37xQ8w" title="Power BI Data Modeling Best Practices by Guy in a Cube" />

*   **Lesson 4.6: Introduction to DAX (Data Analysis Expressions)**
    *   What is DAX? A formula language used to create calculated columns, measures, and tables in Power BI (also in SSAS Tabular and Excel Power Pivot).
    *   DAX is NOT M (Power Query language). M is for data ingestion/transformation, DAX is for calculations on the data model.
    *   Key Concepts:
        *   Syntax: Similar to Excel formulas but operates on entire columns and tables.
        *   Functions: DAX has a rich library of functions (Aggregate, Text, Date, Logical, Filter, Time Intelligence, etc.).
        *   Evaluation Context: Row Context and Filter Context (crucial for understanding DAX behavior).
    *   Where DAX is used: Calculated Columns, Measures, Calculated Tables.
    *   <YouTube videoId="uJGajPSqg4k" title="DAX in Power BI: A Beginner's Guide to Getting Started by Avi Singh - PowerBIPro" /> (Recap)
    *   <YouTube videoId="vjMOTg40Fak" title="What is DAX? (And Why You Need To Learn It) by Enterprise DNA" />

*   **Lesson 4.7: Calculated Columns in DAX**
    *   What are Calculated Columns? Columns added to a table in your data model, with values calculated row by row based on a DAX formula.
    *   Calculated columns are computed during data refresh and consume memory (stored in the model).
    *   When to use Calculated Columns:
        *   For static values based on other columns in the same row (e.g., 'FullName' = [FirstName] & " " & [LastName]).
        *   For creating categories or flags to be used in slicers, filters, or visual axes.
        *   When the calculation needs to be performed at the row level before aggregation.
    *   Creating a Calculated Column in the Data View or Model View.
    *   **Example:** Creating a 'LineTotal' column in a Sales table: `Sales[LineTotal] = Sales[OrderQuantity] * Sales[UnitPrice]`
    *   **Example:** Creating a 'PriceCategory' column: `Products[PriceCategory] = IF(Products[ListPrice] < 50, "Low", IF(Products[ListPrice] < 200, "Medium", "High"))`
    *   <YouTube videoId="r0srgj9hXQ8" title="Power BI Calculated Columns vs Measures by Curbal" /> (Focus on Calculated Columns part)

*   **Lesson 4.8: Introduction to Measures in DAX**
    *   What are Measures? Dynamic calculations performed at query time, based on the current filter context (slicers, visuals, etc.).
    *   Measures are NOT stored in the model; they are calculated on the fly.
    *   When to use Measures:
        *   For aggregations (Sum, Average, Count, etc.) that respond to filters.
        *   For complex business logic and KPIs.
        *   When you need calculations that change based on user interaction.
    *   Creating a Measure (typically in the Report View or Model View).
    *   Implicit Measures (Power BI automatically creates these for numeric fields, e.g., Sum of SalesAmount) vs. Explicit Measures (you write the DAX formula). Explicit measures are highly recommended.
    *   **Example (Explicit Measure):** `Total Sales = SUM(Sales[SalesAmount])`
    *   **Example:** `Average Price = AVERAGE(Products[ListPrice])`
    *   <YouTube videoId="r0srgj9hXQ8" title="Power BI Calculated Columns vs Measures by Curbal" /> (Focus on Measures part)
    *   <YouTube videoId="MG2gV1L0L7Q" title="Creating Your First DAX Measures in Power BI by Pragmatic Works" />

*   **Lesson 4.9: Common DAX Aggregation Functions (SUM, AVERAGE, COUNT, DISTINCTCOUNT, MIN, MAX)**
    *   `SUM(<column>)`: Adds all the numbers in a column.
    *   `AVERAGE(<column>)`: Returns the arithmetic mean of the values in a column.
    *   `COUNT(<column>)`: Counts the number of cells in a column that contain numbers, text, or dates (ignores blanks unless they are text blanks).
    *   `COUNTA(<column>)`: Counts non-blank cells.
    *   `COUNTROWS(<table>)`: Counts the number of rows in a table.
    *   `DISTINCTCOUNT(<column>)`: Counts the number of distinct (unique) values in a column.
        *   **Example:** `Unique Customers = DISTINCTCOUNT(Sales[CustomerID])`
    *   `MIN(<column>)` or `MINX(<table>, <expression>)`: Returns the smallest numeric value.
    *   `MAX(<column>)` or `MAXX(<table>, <expression>)`: Returns the largest numeric value.
    *   Using these functions to create basic measures.
    *   <YouTube videoId="NU1xfgz7YmY" title="DAX Aggregation Functions - SUM, AVERAGE, COUNT, MIN, MAX by BI Elite" />

*   **Lesson 4.10: Understanding Evaluation Context - Row Context vs. Filter Context**
    *   **Row Context:** Exists when a DAX formula is evaluated for each row of a table (e.g., in a calculated column, or inside an iterator function like `SUMX`).
        *   The formula can "see" the values of other columns in the current row.
    *   **Filter Context:** The set of filters applied to the data model before a DAX measure is evaluated.
        *   Filters can come from visuals (axes, legends), slicers, other visuals (cross-filtering), or DAX filter functions.
        *   Measures are evaluated within the current filter context.
    *   This is a fundamental concept for writing correct and efficient DAX.
    *   Simple examples illustrating how measures react to filters on a report page.
    *   <YouTube videoId="Kz8NJKs94hQ" title="DAX Evaluation Context Explained (Row, Filter, Query Context) by SQLBI" /> (SQLBI are DAX masters)
    *   <YouTube videoId="ZzY8mwA59dY" title="Power BI DAX Filter Context and Row Context by Curbal" />

*   **Lesson 4.11: The CALCULATE Function - The Most Important DAX Function**
    *   `CALCULATE(<expression>, <filter1>, <filter2>, ...)`
    *   Purpose: Evaluates an expression in a modified filter context.
    *   It allows you to override or add filters to the existing filter context.
    *   Key uses:
        *   Applying specific filters (e.g., `CALCULATE([Total Sales], Products[Color] = "Red")`).
        *   Removing filters (e.g., using `ALL()`, `ALLEXCEPT()`).
        *   Time intelligence calculations (e.g., Year-to-Date sales).
    *   Understanding context transition (when row context is converted to filter context within `CALCULATE`).
    *   **Example:** `Red Product Sales = CALCULATE([Total Sales], Products[Color] = "Red")`
    *   **Example:** `All Product Sales = CALCULATE([Total Sales], ALL(Products))` (removes filters from Products table)
    *   <YouTube videoId="Si3h2B0kLqE" title="CALCULATE function in Power BI and DAX by SQLBI" />

*   **Lesson 4.12: DAX Filter Functions - ALL, ALLEXCEPT, FILTER, KEEPFILTERS**
    *   Functions used (often within `CALCULATE`) to modify the filter context.
    *   `ALL(<table> or <column1>, [<column2>...])`: Returns all rows in a table or all values in columns, ignoring any filters that might have been applied.
        *   Used to calculate percentages of grand total.
    *   `ALLEXCEPT(<table>, <column1>, [<column2>...])`: Removes filters from all columns in a table except for those specified.
    *   `FILTER(<table>, <filter_expression>)`: Returns a table that has been filtered.
        *   Often used as a filter argument in `CALCULATE`.
    *   `KEEPFILTERS(<expression>)`: Modifies how filters are applied, ensuring existing filters are preserved rather than overridden by `CALCULATE`'s filter arguments.
    *   <YouTube videoId="scuyGaA7n60" title="Understanding ALLSELECTED, ALL, ALLEXCEPT in Power BI by Curbal" />
    *   <YouTube videoId="wAYt199KNo" title="DAX Functions ALL, ALLEXCEPT, ALLSELECTED Explained by SQLBI Marco Russo" />

*   **Lesson 4.13: Basic Time Intelligence DAX Functions (TOTALYTD, SAMEPERIODLASTYEAR)**
    *   Importance of a proper Date Table (marked as a date table).
    *   `TOTALYTD(<expression>, <dates_column>, [filter])`: Calculates Year-to-Date values.
        *   **Example:** `Sales YTD = TOTALYTD([Total Sales], 'Date'[Date])`
    *   `SAMEPERIODLASTYEAR(<dates_column>)`: Returns a table of dates shifted one year back in time from the dates in the specified dates column.
        *   Used with `CALCULATE` to get prior year values.
        *   **Example:** `Sales PY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date]))`
    *   Calculating Year-over-Year (YoY) growth.
        *   **Example:** `Sales YoY Growth % = DIVIDE([Total Sales] - [Sales PY], [Sales PY])`
    *   Other common time intelligence functions (e.g., `PREVIOUSMONTH`, `DATEADD` - brief mention).
    *   <YouTube videoId="kb9QG0oPOLI" title="Time Intelligence in Power BI - The Big Picture by Enterprise DNA" />
    *   <YouTube videoId="uGIdulxV0U" title="Power BI Time Intelligence DAX Functions for Beginners by Pragmatic Works" />

*   **Lesson 4.14: Creating a Dedicated Date Table (Importance and Methods)**
    *   Why a separate Date table is crucial for robust time intelligence.
    *   Characteristics of a good Date table:
        *   Covers full range of dates in your data.
        *   No missing dates.
        *   Includes useful columns (Year, Quarter, Month Name, Month Number, Day of Week, etc.).
        *   Marked as "Date Table" in Power BI.
    *   Methods for creating a Date Table:
        *   Using DAX: `CALENDAR()` or `CALENDARAUTO()` functions to generate the base date column, then adding calculated columns for Year, Month, etc.
        *   Using Power Query: Generating a list of dates, then adding columns.
        *   Importing from an external source (e.g., a data warehouse).
    *   Connecting the Date Table to fact tables (e.g., 'Date'[DateKey] to 'Sales'[OrderDateKey]).
    *   <YouTube videoId="PVjK2Yqr0wY" title="Creating a Date Table in Power BI (DAX and Power Query Methods) by Curbal" />

*   **Lesson 4.15: DAX Best Practices and Debugging Tips**
    *   Formatting DAX code for readability (use a DAX formatter).
    *   Using variables (VAR...RETURN) to break down complex formulas and improve performance.
    *   Avoiding iterators (`SUMX`, `AVERAGEX`) over entire large tables if possible (use simple aggregations first).
    *   Understanding implicit vs. explicit measures (prefer explicit).
    *   Using `DIVIDE()` for safe division (handles divide by zero).
    *   Commenting your DAX code.
    *   Debugging DAX:
        *   Using `CALCULATE` with simple filters to test parts of a formula.
        *   Creating tables with `SUMMARIZECOLUMNS` or `ROW` to inspect intermediate results.
        *   Using DAX Studio (external tool) for advanced debugging and performance tuning (mention).
    *   <YouTube videoId="pzw8QdObeY" title="DAX Best Practices for Power BI by Guy in a Cube" />
    *   <YouTube videoId="sfPZJSOY5qs" title="Debugging DAX in Power BI by Enterprise DNA" />

---
### Module 5: SQL Fundamentals for Data Analysis (Expanded)

This module introduces SQL (Structured Query Language), the standard language for managing and querying relational databases, with a focus on data retrieval for analysis.

*   **Lesson 5.1: Introduction to Relational Databases and SQL**
    *   What is a Database? An organized collection of data.
    *   Relational Databases (RDBMS): Storing data in structured tables with predefined relationships.
        *   Key Concepts: Tables (Entities), Rows (Records/Tuples), Columns (Attributes/Fields).
        *   Schema: The logical structure of the database.
    *   Primary Keys: Uniquely identify each row in a table.
    *   Foreign Keys: Link rows in one table to rows in another table, enforcing relationships.
    *   Referential Integrity.
    *   What is SQL? (Structured Query Language) - The standard language for interacting with RDBMS.
    *   SQL Categories: DQL (Data Query Language - SELECT), DML (Data Manipulation Language - INSERT, UPDATE, DELETE), DDL (Data Definition Language - CREATE, ALTER, DROP), DCL (Data Control Language - GRANT, REVOKE). This course focuses primarily on DQL.
    *   <YouTube videoId="27Ewfs5qW_s" title="SQL Tutorial - Full Database Course for Beginners by freeCodeCamp.org" /> (Focus on Intro to DBs and SQL parts)
    *   <YouTube videoId="z2k2mIDkIzs" title="What is a Relational Database? by IBM Technology" />

*   **Lesson 5.2: Setting Up Your SQL Environment (Choosing a DBMS and Client)**
    *   Overview of popular RDBMS: MySQL, PostgreSQL, SQL Server, Oracle, SQLite.
    *   For learning purposes:
        *   **SQLite:** Serverless, file-based, easy to set up. Good for standalone practice. Tools: DB Browser for SQLite.
        *   **MySQL/PostgreSQL:** More robust, client-server architecture. Tools: MySQL Workbench, pgAdmin, DBeaver.
        *   **Online SQL Editors/Sandboxes:** SQL Fiddle, DB-Fiddle, Mode Analytics SQL School (for practice without local installation).
    *   Installing a chosen DBMS (e.g., MySQL Community Server or PostgreSQL).
    *   Installing a SQL client tool.
    *   Connecting to a database.
    *   Using sample databases (e.g., Sakila for MySQL, Pagila for PostgreSQL, Northwind).
    *   <YouTube videoId="u_hYgK0g7Q" title="How to Install MySQL on Windows (and MySQL Workbench) by Programming with Mosh" />
    *   <YouTube videoId="hMwO0s1Y4Qc" title="DB Browser for SQLite - Getting Started by David Bombal" />

*   **Lesson 5.3: Basic SQL Syntax, Data Types, and Comments**
    *   SQL Statement Structure: Clauses (e.g., SELECT, FROM, WHERE), Keywords, Identifiers (table/column names).
    *   Case Sensitivity: SQL keywords are generally case-insensitive, but table/column name sensitivity depends on the DBMS and OS. Best practice: be consistent.
    *   Semicolons (`;`) to terminate SQL statements (required by some clients, good practice).
    *   Common SQL Data Types:
        *   `INT` or `INTEGER`: Whole numbers.
        *   `DECIMAL(precision, scale)` or `NUMERIC(p,s)`: Fixed-point numbers (e.g., currency).
        *   `FLOAT`, `REAL`, `DOUBLE PRECISION`: Approximate-number data values.
        *   `VARCHAR(n)`: Variable-length character strings (up to n characters).
        *   `CHAR(n)`: Fixed-length character strings.
        *   `TEXT` or `CLOB`: Large text objects.
        *   `DATE`: Stores date values (YYYY-MM-DD).
        *   `TIME`: Stores time values (HH:MM:SS).
        *   `TIMESTAMP` or `DATETIME`: Stores date and time values.
        *   `BOOLEAN` (or `BOOL`): TRUE or FALSE.
    *   Comments in SQL:
        *   Single-line comments: `-- This is a comment`
        *   Multi-line comments: `/* This is a
           multi-line comment */`
    *   <YouTube videoId="yTvH99hPhcE" title="SQL Data Types by Programming with Mosh" />
    *   <YouTube videoId_ SQL_BASICS_SYNTAX_KEYWORDS_by_Socratica title="SQL Basics: Syntax & Keywords by Socratica" /> (Placeholder)

*   **Lesson 5.4: The `SELECT` Statement - Retrieving Data**
    *   Purpose: To query or retrieve data from one or more tables.
    *   Basic Syntax: `SELECT column1, column2, ... FROM tablename;`
    *   Selecting all columns: `SELECT * FROM tablename;` (Use with caution on large tables in production).
    *   Using `AS` to create column aliases (for readability or renaming calculated fields).
        *   **Example:** `SELECT ProductName, UnitPrice * 1.1 AS PriceWithTax FROM Products;`
    *   The `DISTINCT` keyword: To return only unique (different) values for a column.
        *   **Example:** `SELECT DISTINCT Country FROM Customers;`
    *   Simple calculations within `SELECT`.
        *   **Example:** `SELECT ProductName, UnitPrice, UnitsInStock, UnitPrice * UnitsInStock AS TotalValue FROM Products;`
    *   <YouTube videoId="HXV3zeQKqGY" title="SQL SELECT Statement - Tutorial for Beginners by Programming with Mosh" /> (Recap)
    *   <YouTube videoId="J_hczDjq3tk" title="SQL Aliases (AS) and DISTINCT keyword by Caleb Curry" />

*   **Lesson 5.5: The `WHERE` Clause - Filtering Rows**
    *   Purpose: To filter rows based on specified conditions.
    *   Syntax: `SELECT column_list FROM tablename WHERE condition;`
    *   Comparison Operators: `=`, `!=` or `<>`, `>`, `<`, `>=`, `<=`.
        *   **Example:** `SELECT ProductName, UnitPrice FROM Products WHERE UnitPrice > 50;`
        *   **Example:** `SELECT OrderID, CustomerID FROM Orders WHERE ShipCountry = 'USA';` (Note: string literals usually in single quotes).
    *   Logical Operators: `AND`, `OR`, `NOT`.
        *   **Example:** `SELECT * FROM Customers WHERE Country = 'Germany' AND City = 'Berlin';`
        *   **Example:** `SELECT * FROM Products WHERE CategoryID = 1 OR CategoryID = 2;`
    *   Operator precedence (`AND` before `OR` - use parentheses to control order).
    *   <YouTube videoId="p3OM9W2w8YI" title="SQL WHERE Clause by Programming with Mosh" />
    *   <YouTube videoId_ SQL_LOGICAL_OPERATORS_AND_OR_NOT_by_Caleb_Curry title="SQL Logical Operators (AND, OR, NOT) by Caleb Curry" /> (Placeholder)

*   **Lesson 5.6: Advanced Filtering with `BETWEEN`, `IN`, `LIKE`, `IS NULL`**
    *   `BETWEEN ... AND ...`: Selects values within a given range (inclusive).
        *   **Example:** `SELECT ProductName, UnitPrice FROM Products WHERE UnitPrice BETWEEN 20 AND 30;`
    *   `IN (value1, value2, ...)`: Selects values that match any value in a list.
        *   **Example:** `SELECT * FROM Customers WHERE Country IN ('UK', 'USA', 'Canada');`
    *   `LIKE`: Pattern matching in strings using wildcards:
        *   `%`: Matches any sequence of zero or more characters.
        *   `_`: Matches any single character.
        *   **Example:** `SELECT ProductName FROM Products WHERE ProductName LIKE 'Ch%';` (starts with "Ch")
        *   **Example:** `SELECT ProductName FROM Products WHERE ProductName LIKE '_a%';` (second letter is "a")
    *   `NOT LIKE`, `NOT IN`, `NOT BETWEEN`.
    *   `IS NULL`: Selects rows where a column value is NULL (missing or unknown).
    *   `IS NOT NULL`: Selects rows where a column value is not NULL.
        *   **Example:** `SELECT CustomerName, Fax FROM Customers WHERE Fax IS NULL;`
    *   <YouTube videoId="fgjEUQ09ovA" title="SQL LIKE, IN, BETWEEN, IS NULL by Programming with Mosh" />
    *   <YouTube videoId_ SQL_WILDCARDS_PERCENT_UNDERSCORE_by_kudvenkat title="SQL Wildcards (%) and (_) by kudvenkat" /> (Placeholder)

*   **Lesson 5.7: The `ORDER BY` Clause - Sorting Results**
    *   Purpose: To sort the result set by one or more columns.
    *   Syntax: `SELECT column_list FROM tablename [WHERE condition] ORDER BY column1 [ASC|DESC], column2 [ASC|DESC], ...;`
    *   `ASC`: Ascending order (default).
    *   `DESC`: Descending order.
    *   Sorting by multiple columns.
        *   **Example:** `SELECT CustomerName, City, Country FROM Customers ORDER BY Country ASC, City DESC;`
    *   Sorting by column position (less readable, avoid if possible): `ORDER BY 3, 2 DESC;`
    *   Sorting NULL values (behavior can vary by DBMS - `NULLS FIRST` / `NULLS LAST`).
    *   <YouTube videoId="CW-OKcWUqS0" title="SQL ORDER BY Clause by Programming with Mosh" />
    *   <YouTube videoId_ SQL_SORTING_NULL_VALUES_by_WiseOwlTutorials title="SQL Sorting NULL values by WiseOwlTutorials" /> (Placeholder)

*   **Lesson 5.8: Limiting Results - `LIMIT`, `TOP`, `ROWNUM`**
    *   Purpose: To restrict the number of rows returned by a query. Useful for pagination or sampling.
    *   Syntax varies by DBMS:
        *   **MySQL / PostgreSQL / SQLite:** `LIMIT row_count`
            *   `OFFSET offset_value` (to skip rows): `LIMIT row_count OFFSET offset_value`
            *   **Example:** `SELECT ProductName, UnitPrice FROM Products ORDER BY UnitPrice DESC LIMIT 10;` (Top 10 most expensive products)
        *   **SQL Server:** `TOP n [PERCENT] [WITH TIES]`
            *   **Example:** `SELECT TOP 10 ProductName, UnitPrice FROM Products ORDER BY UnitPrice DESC;`
        *   **Oracle:** `ROWNUM <= n` (used in a subquery or `FETCH FIRST n ROWS ONLY` in newer versions).
    *   Combining `LIMIT` with `ORDER BY` is very common.
    *   <YouTube videoId="0dgPUEq0EwA" title="SQL LIMIT Clause (and OFFSET) by Amigoscode" /> (Example for MySQL/Postgres style)
    *   <YouTube videoId_ SQL_SERVER_TOP_CLAUSE_by_kudvenkat title="SQL Server TOP Clause by kudvenkat" /> (Placeholder)

*   **Lesson 5.9: SQL Aggregate Functions - `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`**
    *   Purpose: Perform calculations on a set of values and return a single summary value.
    *   `COUNT(*)`: Counts the total number of rows in the result set (or table if no WHERE clause).
    *   `COUNT(column_name)`: Counts non-NULL values in the specified column.
    *   `COUNT(DISTINCT column_name)`: Counts unique non-NULL values in the column.
        *   **Example:** `SELECT COUNT(DISTINCT Country) AS NumberOfCountries FROM Customers;`
    *   `SUM(column_name)`: Calculates the sum of numeric values.
        *   **Example:** `SELECT SUM(OrderAmount) AS TotalRevenue FROM Orders WHERE OrderDate >= '2023-01-01';`
    *   `AVG(column_name)`: Calculates the average of numeric values.
    *   `MIN(column_name)`: Finds the minimum value.
    *   `MAX(column_name)`: Finds the maximum value.
    *   Aggregate functions ignore NULL values (except `COUNT(*)`).
    *   Usually used with the `GROUP BY` clause (next lesson).
    *   <YouTube videoId="p3qvj9hO_Bo" title="SQL Aggregate Functions (COUNT, SUM, AVG, MIN, MAX) & GROUP BY by Caleb Curry" /> (Recap Aggregates part)

*   **Lesson 5.10: The `GROUP BY` Clause - Grouping Rows for Aggregation**
    *   Purpose: Groups rows that have the same values in specified columns into summary rows.
    *   Used with aggregate functions to calculate metrics for each group.
    *   Syntax: `SELECT column1, aggregate_function(column2) FROM tablename GROUP BY column1;`
    *   Any non-aggregated column in the `SELECT` list must be included in the `GROUP BY` clause.
    *   **Example:** `SELECT CategoryID, AVG(UnitPrice) AS AveragePrice FROM Products GROUP BY CategoryID;`
    *   Grouping by multiple columns.
        *   **Example:** `SELECT ShipCountry, ShipCity, COUNT(*) AS NumberOfOrders FROM Orders GROUP BY ShipCountry, ShipCity;`
    *   Interaction with `WHERE` clause (filters rows *before* grouping).
    *   <YouTube videoId="D9ISr59G4q8" title="SQL GROUP BY Clause by Programming with Mosh" />
    *   <YouTube videoId_ SQL_GROUP_BY_MULTIPLE_COLUMNS_by_Alex_The_Analyst title="SQL GROUP BY Multiple Columns by Alex The Analyst" /> (Placeholder)

*   **Lesson 5.11: The `HAVING` Clause - Filtering Groups**
    *   Purpose: To filter groups created by the `GROUP BY` clause based on aggregate conditions.
    *   Syntax: `SELECT column1, aggregate_function(column2) FROM tablename GROUP BY column1 HAVING condition_on_aggregate;`
    *   `WHERE` filters rows *before* grouping, `HAVING` filters groups *after* grouping.
    *   **Example:** `SELECT CategoryID, COUNT(*) AS NumberOfProducts FROM Products GROUP BY CategoryID HAVING COUNT(*) > 10;` (Find categories with more than 10 products)
    *   Cannot use column aliases defined in `SELECT` directly in `HAVING` (in most DBMS, repeat the aggregate function).
    *   <YouTube videoId="6r9elq0K3Wk" title="SQL HAVING Clause by Programming with Mosh" />
    *   <YouTube videoId_ SQL_HAVING_CLAUSE_EXAMPLES_by_kudvenkat title="SQL HAVING Clause Examples by kudvenkat" /> (Placeholder)

*   **Lesson 5.12: SQL `JOIN` Operations - Combining Data from Multiple Tables**
    *   Purpose: To combine rows from two or more tables based on a related column between them.
    *   Understanding Primary Key - Foreign Key relationships.
    *   `INNER JOIN` (or just `JOIN`): Returns rows when there is at least one match in both tables.
        *   Syntax: `SELECT t1.col, t2.col FROM table1 t1 INNER JOIN table2 t2 ON t1.common_column = t2.common_column;`
        *   Using table aliases (`t1`, `t2`) for brevity and clarity.
        *   **Example:** `SELECT Orders.OrderID, Customers.CustomerName FROM Orders INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID;`
    *   Joining multiple tables.
    *   <YouTube videoId="2n1SDt6_X8g" title="SQL Joins Explained | INNER, LEFT, RIGHT, FULL Joins by kudvenkat" /> (Focus on INNER JOIN first)
    *   <YouTube videoId="0VGgq062qYI" title="SQL INNER JOIN by Programming with Mosh" />

*   **Lesson 5.13: `LEFT JOIN`, `RIGHT JOIN`, and `FULL OUTER JOIN`**
    *   `LEFT JOIN` (or `LEFT OUTER JOIN`): Returns all rows from the left table (table1), and the matched rows from the right table (table2). The result is NULL from the right side if there is no match.
        *   **Example:** `SELECT Customers.CustomerName, Orders.OrderID FROM Customers LEFT JOIN Orders ON Customers.CustomerID = Orders.CustomerID;` (Shows all customers, even those with no orders).
    *   `RIGHT JOIN` (or `RIGHT OUTER JOIN`): Returns all rows from the right table, and the matched rows from the left table. NULL from the left if no match. (Less common, can often be rewritten as a LEFT JOIN).
    *   `FULL OUTER JOIN` (or `FULL JOIN`): Returns all rows when there is a match in one of the tables. If there is no match, the result is NULL on the side that does not have a match.
    *   Understanding when to use each type of outer join.
    *   <YouTube videoId="D0l4kK0r_wA" title="SQL OUTER JOIN (Left, Right, Full) by Programming with Mosh" />
    *   <YouTube videoId_ SQL_SELF_JOIN_EXPLAINED_by_Alex_The_Analyst title="SQL SELF JOIN Explained by Alex The Analyst" /> (Placeholder - Self Join is also important)

*   **Lesson 5.14: `UNION` and `UNION ALL` - Combining Result Sets**
    *   Purpose: To combine the result sets of two or more `SELECT` statements.
    *   Rules for `UNION`:
        *   Each `SELECT` statement within `UNION` must have the same number of columns.
        *   The columns must also have similar data types.
        *   The columns in each `SELECT` statement must be in the same order.
    *   `UNION`: Removes duplicate rows from the combined result set.
    *   `UNION ALL`: Includes all rows, including duplicates (faster if duplicates are acceptable or known not to exist).
    *   **Example:** `SELECT City, Country FROM Customers UNION SELECT City, Country FROM Suppliers ORDER BY City;`
    *   Difference from `JOIN` (UNION appends rows, JOIN combines columns).
    *   <YouTube videoId="LOhkJjUnVOw" title="SQL UNION Operator by Programming with Mosh" />
    *   <YouTube videoId_ SQL_INTERSECT_AND_EXCEPT_MINUS_OPERATORS_by_kudvenkat title="SQL INTERSECT and EXCEPT/MINUS Operators by kudvenkat" /> (Placeholder - good to mention these set operators too)

*   **Lesson 5.15: Introduction to Subqueries (Nested Queries)**
    *   What is a Subquery? A query embedded inside another SQL query.
    *   Can be used in `SELECT`, `FROM`, `WHERE`, or `HAVING` clauses.
    *   Types of Subqueries:
        *   Scalar Subquery: Returns a single value.
        *   Multi-row Subquery: Returns multiple rows (often used with `IN`, `ANY`, `ALL`).
        *   Correlated Subquery: Inner query depends on the outer query for its values.
    *   **Example (in WHERE clause):** `SELECT ProductName FROM Products WHERE UnitPrice > (SELECT AVG(UnitPrice) FROM Products);`
    *   **Example (with IN):** `SELECT CustomerName FROM Customers WHERE CustomerID IN (SELECT CustomerID FROM Orders WHERE OrderDate = '2023-10-26');`
    *   Readability and performance considerations. Often, JOINs can be more efficient than correlated subqueries.
    *   <YouTube videoId="Y00AvwYn9gA" title="SQL Subqueries Tutorial by kudvenkat" /> (Recap)
    *   <YouTube videoId="gBkiLdK9SfI" title="SQL Subqueries by Programming with Mosh" />

---
### Module 6: Advanced SQL, Tool Integration & Capstone Project (Expanded)

This module focuses on more advanced SQL techniques, integrating the learned tools, and culminates in a capstone project applying all acquired skills.

*   **Lesson 6.1: Common Table Expressions (CTEs) with the `WITH` Clause**
    *   What are CTEs? Temporary, named result sets that you can reference within a single SQL statement (SELECT, INSERT, UPDATE, DELETE, or MERGE).
    *   Syntax: `WITH CteName AS (SELECT ... FROM ... WHERE ...) SELECT ... FROM CteName ...;`
    *   Benefits:
        *   Improved readability of complex queries.
        *   Modularity: Break down complex logic into smaller, understandable parts.
        *   Recursion (Recursive CTEs for hierarchical data - advanced topic, brief mention).
    *   **Example:**
        ```sql
        WITH RegionalSales AS (
            SELECT Region, SUM(SalesAmount) AS TotalSales
            FROM Sales
            GROUP BY Region
        )
        SELECT rs.Region, rs.TotalSales, (rs.TotalSales * 100.0 / (SELECT SUM(TotalSales) FROM RegionalSales)) AS PercentageOfGrandTotal
        FROM RegionalSales
        ORDER BY rs.TotalSales DESC;
        ```
    *   Multiple CTEs in a single query.
    *   <YouTube videoId="0r2e_qj3c5A" title="SQL CTEs (Common Table Expressions) Explained by Caleb Curry" />
    *   <YouTube videoId_ ADVANCED_SQL_CTES_COMMON_TABLE_EXPRESSIONS_by_Alex_The_Analyst title="Advanced SQL: CTEs (Common Table Expressions) by Alex The Analyst" /> (Placeholder)

*   **Lesson 6.2: SQL Window Functions - Overview and Use Cases**
    *   What are Window Functions? Functions that perform calculations across a set of table rows that are somehow related to the current row (a "window" or partition).
    *   Unlike aggregate functions with `GROUP BY`, window functions do not collapse rows. Each row maintains its identity.
    *   Common Use Cases: Ranking, running totals, moving averages, comparing row values within a partition.
    *   Syntax: `FUNCTION_NAME() OVER (PARTITION BY column_list ORDER BY column_list [ROWS/RANGE frame_clause])`
        *   `PARTITION BY`: Divides rows into partitions (optional).
        *   `ORDER BY`: Orders rows within each partition (often required for ranking/running totals).
        *   Frame clause (e.g., `ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW` - for running totals).
    *   This is an introduction; specific window functions will be covered next.
    *   <YouTube videoId="0u65RX408a4" title="SQL Window Functions - The Ultimate Guide by Alex The Analyst" />

*   **Lesson 6.3: SQL Window Functions - Ranking (`ROW_NUMBER`, `RANK`, `DENSE_RANK`, `NTILE`)**
    *   `ROW_NUMBER() OVER (ORDER BY ...)`: Assigns a unique sequential integer to each row within its partition.
    *   `RANK() OVER (ORDER BY ...)`: Assigns a rank to each row within its partition. Gaps in rank occur if there are ties.
    *   `DENSE_RANK() OVER (ORDER BY ...)`: Assigns a rank without gaps. Rows with the same value get the same rank.
    *   `NTILE(n) OVER (ORDER BY ...)`: Divides rows into `n` ranked groups (quintiles, deciles, etc.).
    *   **Example:** Ranking products by sales within each category.
        ```sql
        SELECT
            ProductName,
            CategoryID,
            SalesAmount,
            RANK() OVER (PARTITION BY CategoryID ORDER BY SalesAmount DESC) AS CategoryRank
        FROM ProductSales;
        ```
    *   <YouTube videoId_ SQL_RANKING_FUNCTIONS_ROW_NUMBER_RANK_DENSE_RANK_NTILE_by_kudvenkat title="SQL Ranking Functions (ROW_NUMBER, RANK, DENSE_RANK, NTILE) by kudvenkat" /> (Placeholder)
    *   <YouTube videoId="P5X4kL75HhA" title="SQL Ranking Window Functions: ROW_NUMBER, RANK, DENSE_RANK, NTILE by Programming with Mosh" />

*   **Lesson 6.4: SQL Window Functions - Aggregate (`SUM`, `AVG`, `COUNT` as Window Functions)**
    *   Using aggregate functions with the `OVER()` clause.
    *   Calculating running totals:
        *   **Example:** `SELECT OrderDate, SalesAmount, SUM(SalesAmount) OVER (ORDER BY OrderDate ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW) AS RunningTotalSales FROM DailySales;`
    *   Calculating moving averages.
    *   Calculating percentages of total within a partition.
        *   **Example:** `SELECT ProductName, CategoryID, SalesAmount, SalesAmount * 100.0 / SUM(SalesAmount) OVER (PARTITION BY CategoryID) AS PctOfCategorySales FROM ProductSales;`
    *   <YouTube videoId_ SQL_WINDOW_FUNCTIONS_AGGREGATES_OVER_PARTITIONS_by_Alex_The_Analyst title="SQL Window Functions - Aggregates Over Partitions by Alex The Analyst" /> (Placeholder)
    *   <YouTube videoId_ SQL_RUNNING_TOTALS_AND_MOVING_AVERAGES_WITH_WINDOW_FUNCTIONS_by_Caleb_Curry title="SQL Running Totals and Moving Averages with Window Functions by Caleb Curry" /> (Placeholder)

*   **Lesson 6.5: SQL Window Functions - Value (`LAG`, `LEAD`, `FIRST_VALUE`, `LAST_VALUE`)**
    *   `LAG(column, [offset], [default]) OVER (ORDER BY ...)`: Accesses data from a previous row in the same result set without a self-join.
    *   `LEAD(column, [offset], [default]) OVER (ORDER BY ...)`: Accesses data from a subsequent row.
        *   **Example:** Calculating day-over-day sales difference: `SalesAmount - LAG(SalesAmount, 1, 0) OVER (ORDER BY OrderDate)`.
    *   `FIRST_VALUE(column) OVER (PARTITION BY ... ORDER BY ...)`: Returns the value of the specified column from the first row of the window frame.
    *   `LAST_VALUE(column) OVER (PARTITION BY ... ORDER BY ... [frame_clause])`: Returns the value from the last row (requires careful frame definition).
    *   <YouTube videoId_ SQL_LAG_LEAD_WINDOW_FUNCTIONS_by_kudvenkat title="SQL LAG and LEAD Window Functions by kudvenkat" /> (Placeholder)
    *   <YouTube videoId_ SQL_FIRST_VALUE_LAST_VALUE_WINDOW_FUNCTIONS_by_Essential_SQL title="SQL FIRST_VALUE and LAST_VALUE Window Functions by Essential SQL" /> (Placeholder)

*   **Lesson 6.6: Connecting Excel to SQL Databases (via Get & Transform / Power Query)**
    *   Recap: Power Query in Excel.
    *   Using "Get Data" > "From Database" > "From SQL Server Database" (or other DBMS options like MySQL, PostgreSQL).
    *   Specifying Server and Database names.
    *   Authentication methods (Windows, Database credentials).
    *   Navigator Pane: Selecting tables or views to import.
    *   Writing a native SQL query directly in the connection dialog for more control over imported data.
        *   **Example:** `SELECT CustomerID, CompanyName, Country FROM Customers WHERE Country = 'UK';`
    *   Importing data into an Excel Table or Data Model (Power Pivot).
    *   Refreshing data from the SQL source.
    *   <YouTube videoId="xG9SvA9OVAY" title="Connect Excel to SQL Server Database by Leila Gharani" /> (Recap)
    *   <YouTube videoId_ EXCEL_POWER_QUERY_IMPORT_DATA_FROM_SQL_SERVER_by_MyOnlineTrainingHub title="Excel Power Query - Import Data from SQL Server by MyOnlineTrainingHub" /> (Placeholder)

*   **Lesson 6.7: Connecting Power BI to SQL Databases (Import vs. DirectQuery vs. Live Connection)**
    *   "Get Data" > "SQL Server Database" (or other DBMS).
    *   Data Connectivity modes:
        *   **Import:** Copies data into Power BI Desktop (.pbix file). Data is refreshed periodically. Good for performance, allows full Power Query and DAX capabilities.
        *   **DirectQuery:** Power BI sends queries directly to the source database in real-time. Data is not stored in Power BI. Good for very large datasets or near real-time data. Limitations on Power Query transformations and some DAX functions.
        *   **Live Connection:** (Primarily for SQL Server Analysis Services - SSAS). Similar to DirectQuery but for SSAS models.
    *   Choosing the right connectivity mode based on data volume, freshness requirements, and performance needs.
    *   Writing native SQL queries during connection.
    *   <YouTube videoId="76XFXhg6gPM" title="Power BI Connect to SQL Server - Import vs DirectQuery by Pragmatic Works" /> (Recap)
    *   <YouTube videoId_ POWER_BI_DIRECTQUERY_VS_IMPORT_MODE_DEEP_DIVE_by_Guy_in_a_Cube title="Power BI DirectQuery vs Import Mode Deep Dive by Guy in a Cube" /> (Placeholder)

*   **Lesson 6.8: Data Storytelling - Principles and Best Practices**
    *   What is Data Storytelling? Communicating insights from data in a compelling and understandable narrative.
    *   Key elements: Data, Visuals, and Narrative.
    *   Understanding your audience and their needs.
    *   Defining the key message or insight you want to convey.
    *   Choosing the right visuals to support your story.
    *   Structuring your narrative (e.g., problem/situation, analysis, insights, recommendations/call to action).
    *   Using annotations, color, and emphasis effectively.
    *   Avoiding clutter and focusing on clarity.
    *   Ethical considerations in data storytelling (avoiding misrepresentation).
    *   <YouTube videoId="ylg_3Ac_5YI" title="Storytelling with Data | Cole Nussbaumer Knaflic | Talks at Google" />
    *   <YouTube videoId_ DATA_STORYTELLING_TIPS_FOR_EFFECTIVE_COMMUNICATION_by_HubSpot title="Data Storytelling Tips for Effective Communication by HubSpot" /> (Placeholder)

*   **Lesson 6.9: Capstone Project - Defining the Scope and Objectives**
    *   **Project Introduction:** Students will analyze a provided dataset (e.g., AdventureWorks sample database, a public dataset on sales, movies, healthcare, etc.) using Excel, SQL, and Power BI.
    *   **Phase 1: Problem Definition & Planning**
        *   Understanding the dataset: Exploring its structure, tables, and potential variables.
        *   Defining 3-5 key business questions or analytical objectives for the project.
            *   **Example Questions:** What are the top-selling products? Which regions have the highest customer growth? What are the sales trends over time? Is there a correlation between marketing spend and sales?
        *   Planning the approach: Which tools will be used for which tasks? What analyses are needed?
        *   Deliverable: A short project proposal outlining the objectives and plan.
    *   <YouTube videoId_ HOW_TO_START_A_DATA_ANALYSIS_PROJECT_by_Alex_The_Analyst title="How to Start a Data Analysis Project by Alex The Analyst" /> (Placeholder)

*   **Lesson 6.10: Capstone Project - Data Acquisition and Initial Exploration (SQL & Excel/Power Query)**
    *   **Phase 2: Data Collection & Initial Exploration**
        *   If using a SQL database: Students will write SQL queries to extract relevant data based on their objectives.
            *   Focus on `SELECT`, `FROM`, `WHERE`, `JOIN`, `GROUP BY`.
        *   If using CSV/Excel files: Importing data into Excel/Power Query.
        *   Initial Data Profiling:
            *   Using SQL `COUNT(*)`, `DISTINCT`, basic aggregates to understand data volumes and distributions.
            *   Using Excel's descriptive statistics or Power Query's column profiling features.
        *   Identifying potential data quality issues (missing values, outliers, inconsistencies) for the next phase.
        *   Deliverable: SQL scripts (if applicable), initial data profiling notes.
    *   <YouTube videoId_ EXPLORATORY_DATA_ANALYSIS_EDA_WITH_SQL_by_StrataScratch title="Exploratory Data Analysis (EDA) with SQL by StrataScratch" /> (Placeholder)

*   **Lesson 6.11: Capstone Project - Data Cleaning and Transformation (SQL & Excel/Power Query)**
    *   **Phase 3: Data Cleaning & Transformation**
        *   Using SQL:
            *   Handling NULLs (e.g., `COALESCE`, `CASE` statements).
            *   Transforming data types (`CAST`, `CONVERT`).
            *   Creating new calculated fields.
            *   Filtering out irrelevant data.
        *   Using Excel/Power Query:
            *   Applying transformations learned in Modules 1 & 2 (Text functions, logical functions, Power Query steps like splitting, merging, conditional columns, etc.).
        *   Documenting the cleaning and transformation steps.
        *   Aiming for a clean, analysis-ready dataset.
        *   Deliverable: Cleaned dataset (or SQL view definition), summary of cleaning steps.
    *   <YouTube videoId_ DATA_CLEANING_IN_SQL_TUTORIAL_by_Alex_The_Analyst title="Data Cleaning in SQL Tutorial by Alex The Analyst" /> (Placeholder)

*   **Lesson 6.12: Capstone Project - In-depth Analysis (SQL & Excel PivotTables/DAX)**
    *   **Phase 4: Data Analysis**
        *   Using Advanced SQL:
            *   Complex JOINs, subqueries, CTEs, Window Functions to answer defined business questions.
            *   Aggregating data to find trends, patterns, and insights.
        *   Using Excel PivotTables:
            *   Summarizing cleaned data, creating different views, using slicers.
        *   (Optional, if covered deeply enough) Using Power BI DAX for more complex measures if data is loaded into Power BI at this stage.
        *   Focus on deriving meaningful insights from the data.
        *   Deliverable: Key analytical queries/PivotTable setups, initial findings.
    *   <YouTube videoId_ ADVANCED_SQL_FOR_DATA_ANALYSIS_PROJECTS_by_Tina_Huang title="Advanced SQL for Data Analysis Projects by Tina Huang" /> (Placeholder)

*   **Lesson 6.13: Capstone Project - Data Visualization and Dashboard Creation (Power BI)**
    *   **Phase 5: Visualization & Dashboarding**
        *   Importing the cleaned and analyzed (or pre-analyzed) data into Power BI.
        *   Creating a data model in Power BI (if multiple tables are used).
        *   Developing appropriate DAX measures for KPIs and visuals.
        *   Building an interactive Power BI dashboard with 3-5 visuals that clearly communicate the answers to the defined business questions.
        *   Applying principles of effective data visualization and report design.
        *   Using slicers, tooltips, and bookmarks for enhanced interactivity.
        *   Deliverable: Power BI .pbix file.
    *   <YouTube videoId_ BUILD_A_POWER_BI_DASHBOARD_FROM_SCRATCH_by_Avi_Singh_PowerBIPro title="Build a Power BI Dashboard From Scratch by Avi Singh - PowerBIPro" /> (Placeholder)

*   **Lesson 6.14: Capstone Project - Interpretation, Storytelling, and Presentation**
    *   **Phase 6: Interpretation & Communication**
        *   Interpreting the findings from the analysis and visualizations.
        *   Crafting a narrative or story around the key insights.
        *   Preparing a short presentation (e.g., PowerPoint or using Power BI's storytelling features) summarizing:
            *   Project Objectives.
            *   Methodology (briefly).
            *   Key Findings and Visualizations.
            *   Conclusions and Potential Recommendations (if applicable).
        *   Practicing clear and concise communication of technical findings to a non-technical audience.
        *   Deliverable: Presentation slides and a brief written report/summary.
    *   <YouTube videoId_ HOW_TO_PRESENT_DATA_ANALYSIS_RESULTS_by_Jeff_Su title="How to Present Data Analysis Results by Jeff Su" /> (Placeholder)

*   **Lesson 6.15: Course Review, Further Learning, and Career Resources**
    *   Recap of key concepts learned across Excel, Power BI, and SQL.
    *   The synergy between these tools in a data analyst's workflow.
    *   Paths for further learning:
        *   Advanced DAX and Power Query.
        *   More advanced SQL (database design, performance tuning, specific DBMS features).
        *   Introduction to Python/R for data analysis.
        *   Cloud data services (Azure Synapse, AWS Redshift, Google BigQuery).
        *   Certifications (e.g., Microsoft PL-300 Power BI Data Analyst).
    *   Resources for job searching in data analytics (job boards, communities, networking).
    *   Building a portfolio of data analysis projects.
    *   <YouTube videoId_ DATA_ANALYST_CAREER_PATH_AND_HOW_TO_GET_A_JOB_by_Alex_The_Analyst title="Data Analyst Career Path and How to Get a Job by Alex The Analyst" /> (Placeholder)
    *   <YouTube videoId_ MICROSOFT_POWER_BI_CERTIFICATION_PL_300_STUDY_GUIDE_by_Guy_in_a_Cube title="Microsoft Power BI Certification (PL-300) Study Guide by Guy in a Cube" /> (Placeholder)

This completes the expansion for all modules of Course 1. It has been a substantial update.

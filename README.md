# Units-Lib

A spreadsheet of `standardFieldName` values and their corresponding units.

[units.xlsx](https://github.com/user-attachments/files/31976091/units.xlsx)

## Usage

1. Insert the `units` sheet into a loadsheet workbook.
2. In cell `K2`, enter the formula: =VLOOKUP(R2,units!A:B,2,FALSE)


3. Fill the formula down across all cells with a `standardFieldName`.

## Adding to the library

1. Apply the units library to a loadsheet.
2. Filter `standardFieldName` to exclude blanks.
3. Filter the unit column to show only `N/A` values.
4. Add each unique value to the end of the library.
5. Fill in the appropriate unit for each new entry.
6. Save and export the updated units sheet.


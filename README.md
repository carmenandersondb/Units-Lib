# Units-Lib

A spreadsheet of `standardFieldName` values and their corresponding units.

[units.xlsx](https://github.com/user-attachments/files/31976091/units.xlsx)

## Usage

1. Insert the `units` sheet into a loadsheet workbook.
2. In cell `K2`, enter the formula: =VLOOKUP(R2,units!A:B,2,FALSE)


3. Fill the formula down across all cells with a `standardFieldName`.


3. Fill the formula down across all cells with a `standardFieldName`.

## Adding to the library

1. Apply the units library to a loadsheet.
2. Filter `standardFieldName` to exclude blanks.
3. Filter the unit column to show only `N/A` values.
4. Add each unique value to the end of the library.
5. Fill in the appropriate unit for each new entry.
6. Save and export the updated units sheet.

## Submitting changes

New field names and units are welcome. To submit them:

1. Download `units.xlsx` and add your new rows to the **bottom** of the sheet.
   Don't reformat, re-sort, or edit the existing rows.
2. Open a [new issue](../../issues/new/choose) and select the
   **New units submission** template.
3. Drag your updated `units.xlsx` into the attachment box and submit.

Submissions are reviewed and merged into the library manually, so there may be
a short delay before your units appear in the file above. If you're comfortable
with Git, you can also fork the repo, replace `units.xlsx`, and open a pull
request instead.


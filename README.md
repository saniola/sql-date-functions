# SQL Date Functions

A set of MySQL queries demonstrating date and time manipulation functions against an `orders` table.

## Contents (`date_functions.sql`)

1. Extracting year, month, and day components from a date column.
2. Adding an interval to a date with `DATE_ADD`.
3. Converting a date to a Unix timestamp with `UNIX_TIMESTAMP`.
4. Filtering rows by a date range with `BETWEEN`.
5. Building a JSON object from row data with `JSON_OBJECT`.

Query result screenshots are included as PNG files for each step.

## Stack

- MySQL

## Usage

Run `date_functions.sql` against a MySQL server with an `orders` table (containing `id` and `date` columns) already loaded.

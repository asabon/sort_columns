# sort_columns

Sort Excel file columns by openpyxl

## Usage

python sort_columns.py input output columns_id ...

## Example

### Input file (input.xlsx)

| 1 | 2 | 3 | 4 | 5 | ... |
| 1 | 2 | 3 | 4 | 5 | ... |
| 1 | 2 | 3 | 4 | 5 | ... |
| 1 | 2 | 3 | 4 | 5 | ... |
| 1 | 2 | 3 | 4 | 5 | ... |
| 1 | 2 | 3 | 4 | 5 | ... |

### Command

python sort_columns.py input.xlsx output.xlsx 3 1 2 4 5

### Output file (output.xlsx)

| 3 | 1 | 2 | 4 | 5 | ... |
| 3 | 1 | 2 | 4 | 5 | ... |
| 3 | 1 | 2 | 4 | 5 | ... |
| 3 | 1 | 2 | 4 | 5 | ... |
| 3 | 1 | 2 | 4 | 5 | ... |
| 3 | 1 | 2 | 4 | 5 | ... |

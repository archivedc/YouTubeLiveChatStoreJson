# YouTube Live Chat Store Protocol - Index Data
Index data stores offset of each live chat data file and path.

## Struct
- array
    - [offset](###offset): number
    - [path](###path)  : string

### offset
first live chat data's location in seconds with after decimal point.

Example:
- 32.5
- 52.253
- -2.1
- 6

### path
Relative path of Live Chat Data File's location.
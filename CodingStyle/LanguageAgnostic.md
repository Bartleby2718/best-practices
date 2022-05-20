1. Avoid double negatives caused by control flows, as they often confuse the reader.
- Examples:
  - Python: `3 if a == 1 else 2` is better than `2 if a != 1 else 3`.
  - SQL: `IF a IN (2, 3) X ELSE Y` is better than `IF a NOT IN (2, 3) Y ELSE X`
  - C#: `if (a == 1 || a == 2) X else Y` is better than `if (a != 1 && a != 2) Y else X`
- Exceptions
  - Negatives in an if statement is acceptable if you can avoid indenting many lines of else (if) block that follows by adding a guard statement.
  - Because `null` is such a ubiquitous term, `not null` *can* be an exception.

# Regular Expression

## Patterns

> **Note**  
> For now, most of the patterns below come from old notes I'm transferring to the knowledge base. They're not thoroughly tested and might not work as expected.

Match | Pattern
----- | -------
Duplicate lines | `^(.*)(\r?\n\1)+$`
Select URL by scheme grouping | `^(([^:/?#]+):)?(//([^/?#]*))?([^?#]*)(\?([^#]*))?(#(.*))?`

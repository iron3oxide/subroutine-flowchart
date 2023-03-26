# subroutine-flowchart
A simple flowchart to help discern between methods, (pure and impure) functions and procedures.

```mermaid
flowchart TB
  subroutine-->Is it part of a class?
  Is it part of a class?-- Yes -->method
  Is it part of a class?-- No -->Does it return something?
  Does it return something?-- Yes -->Is it pure?
  Does it return something?-- No -->procedure
  Is it pure?-- Yes -->pure function
  Is it pure?-- No -->impure function
```
